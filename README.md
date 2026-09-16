# apple-revamp

An animated experience modeled after Apple's website, built to practice design and GSAP + ScrollTrigger animation. 

## Sections

1. **Hero** — pinned intro with autoplaying animation and the "Oh. So. Pro." title.
2. **Smoke text** — feature copy that lights up word-by-word as you scroll, over a looping smoke video.
3. **Split phones** — Pro Max / Pro slide apart on scroll while the size labels fade in.
4. **Color gallery** — clickable Sierra Blue / Silver / Gold / Graphite swatches that slide the gallery and cross-fade the close-up.
5. **Product video** — a video scrubbed by scroll position, with display specs fading in.
6. **Camera** — parallax layering of the portrait, phone frame, and camera video.

## Built with

- Vanilla JavaScript
- Blender
- [GSAP 3.8](https://greensock.com/gsap/) + ScrollTrigger (via CDN)
- Poppins (Google Fonts)

## Running

No tooling required:

```bash
# from the repo root
open index.html      # macOS
# or just double-click index.html
```

For the scroll-scrubbed video to behave, serve over a local server rather than
`file://`:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

