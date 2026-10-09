<p align="center">
  <img src="assets/brand/header.jpg" alt="Overshoot — motion, made in code" width="100%" />
</p>

<h1 align="center">Overshoot</h1>

<p align="center">
  <b>Motion graphics for your edits, written in code.</b><br />
  Kinetic titles, counters, lower thirds and transitions, rendered frame by frame so every export comes out identical.
</p>

<p align="center">
  <a href="https://overshoot-motion.vercel.app"><b>Website</b></a> ·
  <a href="https://www.instagram.com/overshoot.motion/">Instagram</a> ·
  <a href="https://www.youtube.com/@overshootmotion">YouTube</a>
</p>

---

## The clips

| Hello | Stop scrolling | Odometer |
|:---:|:---:|:---:|
| <img src="assets/gifs/hello.gif" width="240" alt="An orange dot whips in, slams each letter of Hello into place, overshoots the full stop and floods the frame orange" /> | <img src="assets/gifs/stop-scrolling.gif" width="240" alt="STOP drops in, a wall of SCROLLING rips upward and stops on one line, NOW slams in on an orange slab" /> | <img src="assets/gifs/odometer.gif" width="240" alt="A number rolls up to 12,480 like a car odometer while a bar chart grows underneath" /> |
| The dot writes the word, overshoots, and floods the frame. | A feed that rips upward and stops dead on one line. | Every digit spins like an odometer and overshoots its number. |

Every clip is 9:16 for Shorts and Reels, with sound, and ends on the Overshoot outro:

<p align="center"><img src="assets/gifs/trailer.gif" width="260" alt="The Overshoot trailer: a heartbeat dot, slammed words, a slot-machine logo and links to Instagram, YouTube and the website" /></p>

New clips land on [Instagram](https://www.instagram.com/overshoot.motion/) and [YouTube](https://www.youtube.com/@overshootmotion) every day.

## Get the pack

The pack has everything you need to use these in your own videos:

- Every clip in 9:16 and 16:9
- Transparent versions (ProRes 4444) to lay over your footage
- **The prompt behind each clip**
- The editable source, so you can change the words and colours and re-render
- New clips added every week

👉 **[overshoot-motion.vercel.app](https://overshoot-motion.vercel.app)**

## Free sample: the odometer

To show how it works, one clip is free with its full source and prompt: [`samples/odometer`](samples/odometer).

It's a single HTML file. A headless browser draws it frame by frame with [HyperFrames](https://hyperframes.heygen.com), and the text, number and colours are variables you can change without touching the code:

```bash
cd samples/odometer
npx hyperframes render . -o odometer.mp4
npx hyperframes render . --variables '{"label":"Subscribers","value":"98,214","chip":"▲ 12% this week"}' -o subscribers.mp4
```

## How it's made

1. **Describe the motion.** What moves, in what order, and how it should feel when it lands.
2. **It becomes code.** Every move is a line of code with an exact timing and easing curve.
3. **Rendered frame by frame.** A browser draws each frame in order, so the export never drops a frame or changes between renders.

## License

The code in [`samples/`](samples) is MIT licensed. Use it, change it, ship it.
The Overshoot name, logo and the clips in `assets/` are © 2026 Overshoot and not licensed for reuse.
