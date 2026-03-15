# Thread Unravel

Animated digit component using a single continuous stroke path that unravels and restitches to form each digit. SVG stroke-dashoffset creates a flowing, hand-drawn drawing effect.

[Live Demo →](https://vbuilds.vercel.app/components/thread-unravel)

## Usage

```tsx
import { ThreadUnravel } from "./thread-unravel";

function MyComponent() {
  const [digit, setDigit] = useState(0);
  return <ThreadUnravel value={digit} size={64} />;
}
```

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| `value` | `number` | `0` | Digit to display (0–9) |
| `size` | `number` | `64` | Width in pixels. Height is 1.5× width. |

## Built With

- React
- Framer Motion
- TypeScript

## License

MIT
