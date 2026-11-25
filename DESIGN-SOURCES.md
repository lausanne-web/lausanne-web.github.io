# Free design sources the builder may use

All of these are free for commercial client work. Licence notices live in /assets/vendor/.

## Magic UI (MIT) — animated effects
Clone: `git clone --depth 1 https://github.com/magicuidesign/magicui /tmp/magicui`
Components: `/tmp/magicui/apps/www/registry/magicui/<name>.tsx` (React + Tailwind + Motion).
Our demos are plain HTML, so **re-implement the effect in vanilla CSS/JS** (or GSAP), and add this comment
near the code: `<!-- Effect adapted from Magic UI (MIT) — see /assets/vendor/LICENSE-magicui.txt -->`.

Good picks for local businesses (pick at most 2 per demo, and never the same pair as a recent demo in /designs.json):
- Text: text-reveal, hyper-text, morphing-text, word-rotate, sparkles-text, aurora-text, line-shadow-text, spinning-text, kinetic-text, text-3d-flip, highlighter, typing-animation, video-text
- Surfaces: magic-card, glare-hover, neon-gradient-card, border-beam, shine-border, backlight, progressive-blur, lens
- Backgrounds: dot-pattern, grid-pattern, flickering-grid, retro-grid, striped-pattern, hexagon-pattern, noise-texture, dither-field, light-rays, meteors, particles, ripple, warp-background
- Motion: marquee, scroll-based-velocity, orbiting-circles, number-ticker, blur-fade, scroll-progress, smooth-cursor, pointer
- Objects: globe, icon-cloud, dotted-map, pixel-image, floating-3d-particles, glyph-matrix

## three.js (MIT) — 3D
Self-hosted at /assets/js/three.module.min.js (r170). Examples: `npm i three@0.170.0` then `node_modules/three/examples/jsm/`.
Keep scenes light (mobile!), always provide a static fallback, and pause rendering when off-screen.

## GSAP 3.13 (free, incl. ScrollTrigger and SplitText)
Self-hosted at /assets/js/. Licence: GSAP "no charge" standard licence (commercial use allowed).

## Not allowed (paid / no licence)
GetLayers, Aceternity Pro, React Bits Pro, Magic UI Pro, Framer/Webflow templates, Shadertoy shaders (often non-commercial), Codrops demos copied as-is.
