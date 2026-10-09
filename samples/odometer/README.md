# Odometer (free sample)

<img src="../../assets/gifs/odometer.gif" width="240" alt="A number rolls up to 12,480 like a car odometer while a bar chart grows underneath" />

A 5.5 second count-up for 9:16 videos. Each digit is a spinning strip; the rightmost one spins the most, and every digit overshoots its number before it settles. A seven-bar chart grows underneath while a trend line draws across the tops. Sound effects are included.

## The prompt

> Count up to 12,480 like a car odometer: each digit is a spinning strip, the rightmost spins the most, and every digit overshoots its number before it settles. A 7-bar chart grows underneath while a trend line draws across the tops. Label above in a mono font, a "+" that pops in orange when the count lands, and a dark chip with the month-on-month change. Cream background, dark ink, one orange accent. Exit: every wheel keeps rolling up out of view.

## Render it

You need Node.js and ffmpeg.

```bash
npx hyperframes render . -o odometer.mp4
```

Change the content with variables:

| Variable | Default |
|---|---|
| `label` | `Monthly readers` |
| `value` | `12,480` |
| `suffix` | `+` |
| `chip` | `▲ 38% this month` |
| `background` | `#F4EEE3` (use `transparent` with `--format mov` for an overlay) |
| `ink` | `#16130F` |
| `accent` | `#E8471C` |

```bash
npx hyperframes render . --variables '{"label":"Subscribers","value":"98,214"}' -o subscribers.mp4
```

Want the other clips and their prompts? **[Get the pack →](https://overshoot-motion.vercel.app)**
