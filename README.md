# @raex-ui/thread-unravel

A single continuous stroke path that unravels and restitches to form each digit. Uses SVG stroke-dashoffset animation for a hand-drawn effect.

![thread-unravel](https://raex-ui.vercel.app/components/thread-unravel)

## Install

```bash
npm install @raex-ui/thread-unravel
```

## Usage

```tsx
import { ThreadUnravel } from "@raex-ui/thread-unravel";

function MyComponent() {
  const [digit, setDigit] = useState(0);
  return <ThreadUnravel value={digit} size={64} />;
}
```

## Props

| Prop | Type | Description |
|------|------|-------------|
| `value` | `number` | Digit to display (0–9) |
| `size` | `number` | Width in pixels. Height is automatically 1.5× width. |

## Peer Dependencies

- `react` >=18
- `react-dom` >=18
- `framer-motion` >=10

No Tailwind CSS required.

## License

MIT
