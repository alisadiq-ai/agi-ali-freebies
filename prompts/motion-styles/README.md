# 20 motion-design styles for Claude

Paste one of these into Claude (Claude Code works best, because it can save and open the file) and it writes the whole animation as code: one `index.html` you open in a browser.

Replace `YOUR LOGO` with your logo text or wordmark. These are the exact prompts behind the examples in the reel.

**GSAP:** the prompts load GSAP from `./gsap.min.js`. Put [gsap.min.js](https://cdn.jsdelivr.net/npm/gsap@3.12.5/dist/gsap.min.js) next to `index.html`, or add "load GSAP from the jsDelivr CDN" to the prompt.

## The template

Every prompt below is this template with a style and a direction filled in:

```text
Animate my logo in a {STYLE} style. The logo is the wordmark "{LOGO}". {DIRECTION} Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

## The 20 prompts

### 1. Particles

```text
Animate my logo in a particles style. The logo is the wordmark "YOUR LOGO". Hundreds of small particles swirl in from the edges and settle into the letterforms, with a soft glow and a few stray sparks still drifting at the end. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 2. Liquid morph

```text
Animate my logo in a liquid morph style. The logo is the wordmark "YOUR LOGO". A glossy liquid blob stretches, splits and merges, then morphs into the letters with a gooey metaball look. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 3. Holographic

```text
Animate my logo in a holographic style. The logo is the wordmark "YOUR LOGO". Iridescent rainbow foil that shifts as a light sweep passes over it, on a dark background, with a faint scanline shimmer. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 4. Neon glow

```text
Animate my logo in a neon glow style. The logo is the wordmark "YOUR LOGO". A neon sign on a dark brick-like wall: the tubes flicker on letter by letter, buzz once, then glow steady with a coloured halo. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 5. Wireframe 3D

```text
Animate my logo in a wireframe 3D style. The logo is the wordmark "YOUR LOGO". The letters are built as 3D wireframe outlines in perspective, rotating slowly into a front-facing view, with a vector-grid floor. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 6. Glassmorphism

```text
Animate my logo in a glassmorphism style. The logo is the wordmark "YOUR LOGO". Frosted glass cards with blur, soft borders and coloured blobs drifting behind them; the logo sits on the front card. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 7. Kinetic typography

```text
Animate my logo in a kinetic typography style. The logo is the wordmark "YOUR LOGO". Bold type that slams, stretches, stacks and repeats in rhythm before locking into the final wordmark. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 8. Isometric

```text
Animate my logo in a isometric style. The logo is the wordmark "YOUR LOGO". An isometric scene where the letters rise out of a platform as extruded blocks, with clean flat shading. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 9. Clay 3D

```text
Animate my logo in a clay 3D style. The logo is the wordmark "YOUR LOGO". Soft, rounded, matte clay letters with a playful squash-and-stretch bounce as they drop in, pastel colours, soft shadows. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 10. ASCII art

```text
Animate my logo in a ASCII art style. The logo is the wordmark "YOUR LOGO". A terminal-style grid of monospace characters that scrambles, then resolves into the logo drawn in ASCII characters. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 11. Gradient mesh

```text
Animate my logo in a gradient mesh style. The logo is the wordmark "YOUR LOGO". A slow, rich multicolour gradient mesh flowing in the background, with the logo cut out in clean white type. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 12. Comic book

```text
Animate my logo in a comic book style. The logo is the wordmark "YOUR LOGO". Halftone dots, a bold black outline, a burst shape and a POW-style impact frame as the logo punches in. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 13. Split-flap

```text
Animate my logo in a split-flap style. The logo is the wordmark "YOUR LOGO". An airport split-flap board where each tile flips through characters until it lands on the logo, with a slight shadow on each flap. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 14. Retro VHS

```text
Animate my logo in a retro VHS style. The logo is the wordmark "YOUR LOGO". A VHS tape look: tracking lines, colour bleed, chromatic aberration and a PLAY timestamp, the logo glitching into place. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 15. Halftone

```text
Animate my logo in a halftone style. The logo is the wordmark "YOUR LOGO". A two-colour halftone print look where dot sizes animate to reveal the logo, like a printed poster. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 16. Bauhaus

```text
Animate my logo in a Bauhaus style. The logo is the wordmark "YOUR LOGO". Primary-colour circles, squares and triangles slide, rotate and snap into a balanced Bauhaus composition around the logo. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 17. Pixel art

```text
Animate my logo in a pixel art style. The logo is the wordmark "YOUR LOGO". Chunky 8-bit pixels that build the logo block by block on a small grid, with a retro game-style sparkle. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 18. Blueprint

```text
Animate my logo in a blueprint style. The logo is the wordmark "YOUR LOGO". A technical blueprint: white line drawing on blue paper, construction lines and dimension markers drawing the logo. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 19. Art deco

```text
Animate my logo in a art deco style. The logo is the wordmark "YOUR LOGO". Gold and black art deco linework: symmetric fans, sunbursts and stepped frames drawing in around an elegant wordmark. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

### 20. Neo-brutalism

```text
Animate my logo in a neo-brutalism style. The logo is the wordmark "YOUR LOGO". Flat, loud colours, thick black borders, hard offset shadows and blocky cards that jolt into place around the logo. Write it as one self-contained index.html: a 720x720 stage, CSS and JavaScript inline, animated with GSAP from ./gsap.min.js (no other libraries, no network). Build one GSAP timeline, 4 seconds long, paused, and expose it as window.__tl so it can be rendered frame by frame: no requestAnimationFrame loops, no CSS animations, and if you need randomness use a seeded random. Every frame should look designed, and the logo must be clearly readable from 2.5 s to the end. Save it as index.html.
```

All 20 are also in [prompts.json](prompts.json) if you want to loop over them.
