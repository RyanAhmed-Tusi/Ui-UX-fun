# The Complete Traditional High-End Immersive Website Workflow
### From Concept to Deployment — Everything a Beginner Needs to Know

---

## Table of Contents

1. The Big Picture — What You're Actually Building
2. Phase 1 — Discovery & Strategy
3. Phase 2 — UX Design: Wireframes to Prototypes
4. Phase 3 — Visual / UI Design
5. Phase 4 — Motion Design Planning
6. Phase 5 — Asset Creation (Every Type Explained)
7. Phase 6 — Animation & Interaction Concepts (Every Technique)
8. Phase 7 — Development Stack & Implementation
9. Phase 8 — Performance, Testing & Optimization
10. Phase 9 — Deployment
11. Master Tools Reference

---

## Part 1 — The Big Picture

A high-end immersive website is not built in one go. It is produced in phases by a team — or today, increasingly by one person using AI tools. Understanding the phases first prevents you from jumping into code without a plan.

The traditional team on an agency project:

```
Creative Director     → Overall vision, art direction
UX Designer           → User flows, wireframes, information architecture
UI Designer           → Visual design, design system, component design
Motion Designer       → Animation direction, Lottie files, After Effects
3D Artist             → 3D models, textures, scene lighting
Frontend Developer    → HTML, CSS, JavaScript, framework code
Creative Developer    → Three.js, GSAP, custom WebGL, shaders
Backend Developer     → CMS, APIs, server logic (if needed)
```

In 2024–2026, a single skilled person with Claude Code handles the developer roles almost entirely. But you still need to understand every role to direct the process well.

---

## Part 2 — Discovery & Strategy

Before any design happens, this phase answers: *What are we building, for whom, and why?*

### 2.1 The Creative Brief

A document (usually 1–4 pages) that defines:
- **Client / Product** — what it is, what it does
- **Target Audience** — who uses it, their age/mindset/behavior
- **Goal** — what should the visitor do or feel after visiting
- **Tone & Personality** — e.g. "luxury, editorial, minimalist" or "bold, energetic, youthful"
- **Competitors** — reference sites to analyze
- **Technical constraints** — budget, deadline, CMS needs

### 2.2 Mood Boarding

A mood board is a visual collage of references — website screenshots, photography, typography, color palettes, textures — that establishes the visual direction before any design starts.

**Tools:** Pinterest, Are.na, Milanote, Notion

This step prevents miscommunication. Before spending 40 hours in Figma, you confirm the direction with a 2-hour mood board.

### 2.3 Competitive Analysis

Look at 5–10 competitor or reference websites and document:
- What visual style do they use?
- What interactions are common in this space?
- What does the best in class do that others don't?
- What gap or opportunity exists to be different?

### 2.4 Information Architecture (IA)

A map of all the pages and how they connect. Like a site map — which pages exist, what content lives on each, how users navigate between them.

**Output:** A sitemap diagram (often in FigJam, Miro, or even pen and paper)

### 2.5 User Flow Mapping

Diagrams that show what a user does step by step — what they see, what they click, what happens next. This is about the journey, not the visuals.

Example for a jet website:
```
Land on homepage → See hero animation → Scroll through story sections
→ Interact with 3D model → View specs section → Click CTA → Contact form
```

**Tools:** Figma FigJam, Miro, Whimsical, Lucidchart

---

## Part 3 — UX Design: Wireframes to Prototypes

UX design is about structure and behavior — not color, not beauty. It answers: *How is the page laid out, what is on it, and how does it flow?*

### 3.1 Wireframing

A wireframe is a black-and-white, no-color, no-images skeletal layout of a page. It shows:
- Where the header is
- Where the hero section is and approximately what it contains
- What the navigation looks like
- Where sections begin and end
- What content blocks exist (text block, image, video, 3D area, cards)

**Low-fidelity wireframes** — rough boxes and text. Made in 30 minutes. Used for quick alignment.

**High-fidelity wireframes** — precise layout with real content structure, spacing, but still no visual design.

**Tools:** Figma (most common), Adobe XD, Sketch, Balsamiq (for low-fi)

### 3.2 Prototyping

A prototype is a clickable wireframe or design mock. Users can click buttons, see page transitions, navigate between screens — without any real code.

**Tools:** Figma Prototype (built into Figma), ProtoPie (for complex interactions), Framer (code-based prototyping with real motion)

Figma prototypes are link-based previews shared with clients. ProtoPie adds scroll animations and interaction states that Figma can't handle.

---

## Part 4 — Visual / UI Design

Now color, typography, imagery, and aesthetic come in. This is what most people think of as "design."

### 4.1 Design System / Style Guide

Before designing screens, a design system is established — the shared rules everything follows.

**Components of a design system:**

**Color Palette**
```
Primary:     #0A0A0A (near black)
Background:  #F5F1EB (off white / warm)
Accent:      #C8A96E (gold)
Text:        #1A1A1A
Muted:       #888888
```

**Typography Scale**
```
Display:     Clash Display Bold, 96px / 110px
Heading 1:   Clash Display Medium, 64px / 76px
Heading 2:   General Sans Semibold, 48px / 60px
Body:        General Sans Regular, 18px / 28px
Caption:     General Sans Regular, 14px / 20px
Label:       General Sans Medium, 12px / 16px, uppercase, tracked
```

**Spacing System**
Usually based on 4px or 8px grid:
4, 8, 12, 16, 24, 32, 48, 64, 80, 96, 128px

**Border Radius:**
Small: 4px | Medium: 8px | Large: 16px | Pill: 999px | Sharp: 0

**Shadows:**
Defined as named tokens: shadow-sm, shadow-md, shadow-lg

**Components:**
Every UI element is designed as a reusable component with all its states:
Button (default, hover, active, disabled, loading)
Input (default, focus, error, success)
Card, Modal, Tooltip, Tag, Nav, Footer, etc.

### 4.2 Designing Each Page

Each page is designed in Figma as a full mockup. For a high-end site this includes:

- Desktop (1440px wide)
- Tablet (768px wide)
- Mobile (390px wide)

Every section is designed: hero, about, features, 3D showcase, specs, testimonials, CTA, footer.

**Design layers in Figma for a high-end site:**
- Background layer (color, gradient, or texture)
- Media layer (images, videos, 3D placeholder)
- Content layer (text, icons, buttons)
- Overlay layer (grain texture, glassmorphism blur, noise)

### 4.3 Typography Selection

For high-end sites, custom or premium fonts are used. Sources:

- **Google Fonts** — free, good selection
- **Fontshare** — free, high quality (Clash Display, General Sans, Switzer)
- **Adobe Fonts** — included with Creative Cloud
- **Fonts In Use** — inspiration for font pairings
- **Klim Type Foundry, Grilli Type, etc.** — premium foundries

Pairing rule: One display/heading font (personality) + one body font (readability). They should contrast — a serif display with a sans-serif body, or a geometric display with a humanist body.

### 4.4 Iconography

Icons are small vector graphics for actions, features, navigation. Sources:

- **Phosphor Icons** — large, consistent, free
- **Lucide** — clean, minimal, free, commonly used with React
- **Heroicons** — from Tailwind CSS team
- **Feather Icons** — thin, minimal
- **Custom icons** — drawn in Figma or Illustrator for brand-specific sets

Icons are exported as SVG (scalable vector graphics — they scale without blur at any size).

---

## Part 5 — Motion Design Planning

Before any animation is built, a motion designer (or the designer with motion skills) creates a **motion brief** or **animation spec** that defines:

- Which elements animate and when
- How they enter and exit
- What easing curves are used (the "feel" — sharp, bouncy, smooth, snappy)
- What scroll interactions exist
- What the 3D sections do
- What the page transitions look like

**Easing Curves Explained**

Easing controls the speed profile of an animation. The most important concept in making motion feel natural vs. robotic.

```
Linear:          ─────────────  Constant speed. Robotic. Almost never used.
ease-in:         ──────────╗   Slow start, fast end. Good for exits (things leaving).
ease-out:        ╔─────────  Fast start, slow end. Good for entrances (things arriving).
ease-in-out:     ─────╗╔──── Slow both ends, fast middle. Smooth transitions.
spring/bounce:   ────╗──╗──  Overshoots and settles. Natural, physical feel.
```

**Timing Guidelines (professional standards)**

```
Micro-interaction (hover, click):    100–200ms
UI transition (modal, dropdown):     200–350ms
Page element entrance:               400–600ms
Page transition:                     600–900ms
Cinematic / story moment:            1000ms+
```

Too fast: feels broken. Too slow: feels sluggish. The sweet spot is quick enough to feel responsive, slow enough to be perceived.

**Stagger**

When multiple elements animate in sequence (e.g. a list of cards appearing one after another), the delay between each is called stagger. Typically 30–80ms between items.

---

## Part 6 — Asset Creation (Every Type Explained)

This is where every type of asset used in a high-end website is created. Understand each one clearly.

---

### 6.1 Photography & Video

**Photography** — the actual image files used on the website.

File formats:
- `.jpg` / `.jpeg` — compressed photo. Good for photographs. Small file size.
- `.png` — lossless. Supports transparency. Used for logos, UI elements, product shots on transparent backgrounds.
- `.webp` — modern format. Same quality as jpg/png at ~30% smaller size. Always convert to webp for production.
- `.avif` — newer still. Even smaller. Not universally supported yet.

Photography is either commissioned (professional shoot), licensed (bought from stock sites like Getty, Shutterstock, Unsplash), or AI-generated (Midjourney, Stable Diffusion, Adobe Firefly).

**Video** — `.mp4` (H.264 or H.265 codec) is the standard for web. Always compress video before using on websites (Handbrake, FFmpeg).

Video is used for:
- Background videos (muted autoplay, loop)
- Section intros
- Source material for image sequences (see 6.5)

---

### 6.2 SVG — Scalable Vector Graphics

SVG is a file format for vector images — illustrations and graphics defined as mathematical paths, not pixels. They scale to any size with zero blur. They're also animated directly in CSS or JavaScript.

What SVGs look like in code:
```html
<svg viewBox="0 0 100 100">
  <circle cx="50" cy="50" r="40" fill="blue"/>
  <path d="M 10 80 Q 50 10 90 80" stroke="red" fill="none"/>
</svg>
```

**Created in:** Adobe Illustrator, Figma (export frames as SVG), Sketch

**Used for:**
- Logos
- Icons
- Illustrations
- Animated line drawings (SVG path animations — the "drawing" effect)
- Background patterns and decorative shapes

**SVG Path Animation** — one of the most iconic effects on creative websites. The SVG path has a stroke-dashoffset property that makes it look like it's being drawn in real time. GSAP animates this.

---

### 6.3 Lottie Animations

**What Lottie is:** A format created by Airbnb that converts After Effects animations into a JSON file. This JSON file is then played on a webpage using the Lottie player library. The result is a smooth, scalable, lightweight animation — like a video but as tiny as a text file.

**The Lottie Pipeline:**

```
Motion Designer
     ↓
Works in Adobe After Effects
  - Designs the animation: animated logo, loading spinner,
    illustrated character, animated icon, transition effect
  - Uses the Bodymovin plugin (free After Effects plugin)
     ↓
Exports the animation as a .json file (the Lottie file)
     ↓
Developer uses LottieFiles player or @lottiefiles/react-lottie-player
  - Plays the animation on the webpage
  - Can trigger it on scroll, on hover, on page load
  - Can control play/pause/speed via JavaScript
```

**What kinds of things are made as Lottie files:**
- Animated logos (the logo draws itself or morphs on load)
- Loading and success state animations
- Animated illustrations (a character waves, a plane flies)
- Animated icons (a menu icon morphs into an X)
- Infographic animations (charts that draw themselves)
- Background atmosphere animations (floating particles, glowing shapes)
- Complex transitions between sections

**Why Lottie instead of video:**
- Lottie files are typically 5–50KB. A video of the same animation would be 500KB–5MB.
- Lottie scales to any size without blur (vector-based)
- Lottie can be controlled programmatically (played at any speed, reversed, paused)

**Where to get Lottie files:**
- LottieFiles.com — huge free library
- Create custom ones in After Effects with Bodymovin plugin
- Or in Rive (see 6.4)

**Tools:** Adobe After Effects + Bodymovin plugin, LottieFiles editor (browser-based), Cavalry (alternative to AE)

---

### 6.4 Rive Animations

**What Rive is:** A newer, more powerful alternative to Lottie. Rive is both a design tool (browser-based, like Figma for animation) and a runtime that plays in browsers. Its key advantage over Lottie is **state machines** — the animation can react to user input intelligently.

**The Rive advantage over Lottie:**

Lottie: plays a pre-recorded animation. It can be triggered, but it plays the same way every time.

Rive: the animation has a state machine. Hover a button → the button lights up. Click it → it plays a press animation. Hold it → it plays a hold animation. The animation responds to user interaction in real time with designed transitions between states.

**What gets made in Rive:**
- Interactive buttons with animated states
- Characters that react to mouse position (eyes follow cursor)
- Loading screens with progress-aware animations
- Game-like UI elements
- Product configurators with animated state changes
- Hero sections where an animated illustration reacts to scroll or cursor

**Tools:** Rive.app (browser-based, free tier available)

---

### 6.5 Image Sequences (The Apple Scroll Effect)

This is the technique used in Apple product pages, luxury brand sites, and automotive sites. As you scroll, it looks like a video is playing — the camera slowly zooms in, a product rotates, a plane window zooms toward you.

**What it actually is:** A series of still image frames (like film frames), displayed one at a time on an HTML Canvas element, with scroll position determining which frame is shown.

**The Image Sequence Pipeline:**

```
Step 1: Source Video
  A video clip of the scene: plane window zoom, car turning,
  phone screen lighting up — professionally shot or stock footage.
  Duration: typically 5–15 seconds of footage.

Step 2: Extract Frames (FFmpeg)
  ffmpeg -i source_video.mp4 -vf fps=30 frames/frame_%04d.jpg
  At 30fps for 10 seconds: 300 frames extracted as JPEG images.

Step 3: Optimize the Frames
  - Resize to correct dimensions (match the canvas size)
  - Convert to WebP format (30-50% smaller than JPEG)
  - Target ~10-30KB per frame
  - 300 frames × 20KB = 6MB total (manageable with lazy loading)

Step 4: Upload to CDN
  All frames uploaded to a CDN (Cloudflare, AWS CloudFront, Vercel)
  Naming: frame_0001.webp, frame_0002.webp, ... frame_0300.webp

Step 5: Canvas Implementation
  <canvas> element placed on the page.
  GSAP ScrollTrigger pins the section and maps scroll progress to frame index.
  JavaScript preloads all frames, then draws the correct frame on every scroll tick.
```

**What Canvas is:** Canvas is an HTML element that acts like a blank drawing surface. JavaScript can draw images, shapes, text, and pixels onto it in real time. It's the underlying technology for games, data visualizations, and image sequence animations.

---

### 6.6 3D Models & Files

3D models are the actual three-dimensional objects used in the browser. A jet aircraft you can spin, a bottle you can rotate, a chair you can view from all angles.

**3D File Formats:**

`.glb` — Binary GLTF. The standard format for 3D on the web. It packs geometry, textures, materials, and animations into a single binary file. Always use this.

`.gltf` — Text-based GLTF. Same as GLB but split into separate files (the 3D data is JSON, textures are separate). Less common for web use.

`.fbx` — Autodesk's format. Used in game engines and 3D software. Not web-native. Convert to GLB before using on web.

`.obj` — Old format. Geometry only (no materials in the file). Still used but mostly legacy.

`.usd` / `.usdz` — Apple's format. Used for AR on iOS. Sometimes relevant for product showcases.

**What's Inside a 3D Model File:**
- **Mesh / Geometry** — the actual 3D shape (vertices, edges, polygons that define the surface)
- **Materials** — what the surface looks like (color, roughness, metalness, transparency)
- **Textures** — images baked onto the 3D surface (see 6.7)
- **Bones/Rig** — if the model is animated, a skeleton structure
- **Animations** — pre-baked movement data (a door opening, a character walking)

**Where 3D models come from:**

Created from scratch in Blender, Cinema4D, Maya, or 3ds Max — this is a skilled 3D artist's job that takes hours to days per model.

Downloaded for free: Sketchfab (free section), Poly Haven, KenShape, Quaternius (stylized low-poly), Google Poly archive.

Purchased: TurboSquid, CGTrader, Fab (Epic Games marketplace).

AI-generated: Meshy.ai, Tripo3D — text/image to 3D model in minutes. Quality is improving but still needs cleanup in Blender.

**3D Optimization for Web:**
Raw 3D models from artists are often 50–200MB with millions of polygons. Web needs them below 5MB ideally, with under 100K polygons.

Tools to optimize:
- **Blender** — manual polygon reduction (Decimate modifier)
- **gltf-transform** / **gltfpack** — CLI tools that apply Draco compression (reduces file size by 70–90%), compress textures, remove unused data
- **Draco compression** — an algorithm specifically for compressing 3D geometry. Nearly universal now.

---

### 6.7 Textures & PBR Materials

**What textures are:** Images that are projected onto the surface of a 3D model to give it appearance. Without textures, a 3D model looks like a gray plastic blob. With textures, it looks like metal, leather, painted steel, brushed aluminum.

**PBR — Physically Based Rendering**

PBR is the standard shading system for realistic 3D. It simulates how light behaves on real surfaces. Each material in PBR is defined by a set of texture maps:

**Albedo Map (Base Color)** — the raw color of the surface. What color is the paint? Is the leather brown or black?

**Normal Map** — a blue-purple image that encodes surface detail (bumps, scratches, seams) without adding actual geometry. Makes a flat surface look bumpy and detailed.

**Roughness Map** — grayscale. White = rough (matte), Black = smooth (glossy). A worn surface is rough in the worn areas, smooth elsewhere.

**Metalness Map** — grayscale. White = metal, Black = non-metal. Used to define which parts of a surface are metallic.

**Ambient Occlusion (AO) Map** — adds contact shadows in crevices and corners. Makes the model look grounded and detailed.

**Emissive Map** — defines areas that glow (cockpit lights, screen displays, neon accents).

**HDRI (High Dynamic Range Image)** — a 360° panoramic photograph of a real environment (a sunny field, a studio, a city) used to light 3D scenes realistically. Freeresources: Poly Haven.

**Where textures come from:**
- Created in Substance Painter (industry standard for 3D texturing)
- Generated procedurally in Blender (mathematical patterns, no image files)
- Downloaded: Poly Haven (free CC0 PBR materials)
- Photogrammetry: scanned from real objects

---

### 6.8 Fonts & Typography Files

Font files used on websites:

`.woff2` — Web Open Font Format 2. The standard for web. Compressed, fast-loading. Always use woff2.

`.woff` — Older version. Keep as fallback for very old browsers.

`.ttf` / `.otf` — Desktop formats. Can be used on web but larger than woff2. Convert to woff2 using transfonter.org.

Variable fonts — a single font file that contains a range of weights, widths, and optical sizes. Dramatically reduces file size (one file instead of 8 weight files). Also enables smooth animated weight transitions.

---

## Part 7 — Animation & Interaction Concepts (Every Technique)

This is the core of what makes high-end websites feel high-end. Each technique is explained from scratch.

---

### 7.1 CSS Transitions & Animations

The simplest form of animation. Built directly into CSS. No JavaScript libraries needed.

**Transition** — animates a property change when a CSS state changes (hover, focus, active).

```css
.button {
  background: #000;
  transform: scale(1);
  transition: background 300ms ease-out, transform 200ms ease-out;
}
.button:hover {
  background: #333;
  transform: scale(1.04);
}
```

When you hover the button, it transitions smoothly to the hover state. That smoothness is the transition.

**CSS Animation** — plays a defined keyframe animation automatically.

```css
@keyframes float {
  0%   { transform: translateY(0px); }
  50%  { transform: translateY(-12px); }
100%  { transform: translateY(0px); }
}

.floating-element {
  animation: float 3s ease-in-out infinite;
}
```

This makes an element gently float up and down forever.

**CSS is used for:**
- Hover effects on all interactive elements
- Simple entrance animations
- Ambient looping animations
- Loading spinners
- Skeleton loading states

**CSS is NOT used for:**
- Scroll-triggered animations (you need JavaScript for that)
- Complex sequenced timelines
- 3D interactions
- Anything requiring dynamic control

---

### 7.2 GSAP — GreenSock Animation Platform

GSAP is the most widely used professional animation library for the web. It is to web animation what Photoshop is to image editing — the industry standard that nearly every serious web studio uses.

**Why GSAP over CSS:**
- 20x more performant on complex animations
- Works on any property (CSS, SVG attributes, Canvas, Three.js objects, DOM values, custom objects)
- Complete control: play, pause, reverse, seek, speed up, slow down
- Precise timeline sequencing
- The ScrollTrigger plugin (see 7.4) is unmatched

**Core Concept 1: Tween**

A tween is a single animation instruction. "Move this element from A to B."

```javascript
import gsap from 'gsap';

// gsap.to — animate FROM current state TO the values you specify
gsap.to('.hero-title', {
  opacity: 1,
  y: 0,           // translateY
  duration: 0.8,
  ease: 'power3.out'
});

// gsap.from — start FROM the values you specify, animate TO current state
gsap.from('.hero-title', {
  opacity: 0,
  y: 60,
  duration: 0.8,
  ease: 'power3.out'
});

// gsap.fromTo — specify both start and end explicitly
gsap.fromTo('.hero-title',
  { opacity: 0, y: 60 },   // FROM
  { opacity: 1, y: 0, duration: 0.8, ease: 'power3.out' }  // TO
);
```

**Core Concept 2: Timeline**

A timeline sequences multiple tweens with precise timing control.

```javascript
const tl = gsap.timeline({ delay: 0.5 });

tl.from('.hero-label',   { opacity: 0, y: 20, duration: 0.5 })
  .from('.hero-title',   { opacity: 0, y: 40, duration: 0.7 }, '-=0.3')
  // '-=0.3' means start 0.3 seconds before the previous animation ends (overlap)
  .from('.hero-subtitle',{ opacity: 0, y: 30, duration: 0.6 }, '-=0.2')
  .from('.hero-cta',     { opacity: 0, scale: 0.9, duration: 0.5 }, '-=0.1');
```

This creates a staggered entrance where the label, title, subtitle, and button appear in sequence with overlapping timing — the signature look of high-end web animation.

**Core Concept 3: Stagger**

Animate multiple elements in sequence without writing individual tweens.

```javascript
gsap.from('.card', {
  opacity: 0,
  y: 50,
  duration: 0.6,
  ease: 'power2.out',
  stagger: 0.1  // 100ms delay between each card
});
```

**GSAP Eases:**

```
power1, power2, power3, power4  → increasingly sharp ease curves
back.out(1.7)                   → slight overshoot/bounce on arrival
elastic.out(1, 0.3)             → elastic spring effect
bounce.out                      → ball bounce at end
expo.out                        → very fast start, very slow finish (dramatic)
circ.out                        → circular easing
```

---

### 7.3 GSAP Plugins

GSAP has premium plugins that add major capabilities:

**SplitText**
Splits text into individual characters, words, or lines for per-character animation.

```javascript
const split = new SplitText('.headline', { type: 'chars,words' });

gsap.from(split.chars, {
  opacity: 0,
  y: 80,
  rotateX: -90,
  stagger: 0.03,
  duration: 0.6,
  ease: 'back.out(1.7)'
});
```

This creates the effect of characters flipping or falling in individually — one of the most iconic effects on creative agency websites.

**MorphSVG**
Morphs one SVG shape into another. Example: a play button morphing into a pause button, or a circle morphing into a star.

**DrawSVG**
Animates SVG strokes as if being drawn by a pen in real time.

**Flip**
Animates layout changes smoothly (a grid reorganizing itself, a card expanding to fullscreen) using the FLIP technique (First, Last, Invert, Play).

**MotionPath**
Moves elements along a custom SVG path — a particle orbiting in a curve, a dot traveling along a line.

---

### 7.4 GSAP ScrollTrigger

ScrollTrigger is the most important plugin in professional web development today. It connects GSAP animations to scroll position.

**The Four Modes of ScrollTrigger:**

**Mode 1: Fire Once on Enter**
Animation plays when the element enters the viewport. Like a one-shot entrance.

```javascript
gsap.from('.section-title', {
  scrollTrigger: {
    trigger: '.section-title',
    start: 'top 80%',  // trigger fires when top of element hits 80% down the viewport
  },
  opacity: 0,
  y: 50,
  duration: 0.8
});
```

**Mode 2: Toggle — Play Forward and Reverse**
Animation plays when entering, reverses when leaving.

```javascript
gsap.to('.sidebar', {
  scrollTrigger: {
    trigger: '.sidebar',
    start: 'top center',
    toggleActions: 'play reverse play reverse'
    // onEnter onLeave onEnterBack onLeaveBack
  },
  x: 0,
  opacity: 1
});
```

**Mode 3: Scrub — Tied Directly to Scroll Position**
The animation progress is directly tied to how far you've scrolled within a zone. Scroll forward → animation moves forward. Scroll back → animation moves back. This is the cinematic scrub effect.

```javascript
gsap.to('.plane-model', {
  scrollTrigger: {
    trigger: '.plane-section',
    start: 'top top',
    end: 'bottom bottom',
    scrub: 1,  // 1 second smoothing lag (higher = smoother/slower response)
  },
  rotationY: 360,  // plane rotates a full 360° as you scroll through the section
  ease: 'none'     // linear mapping to scroll = direct scrub feel
});
```

**Mode 4: Pin**
An element is pinned (fixed in position) while the page scrolls around it. This allows a section to "hold" on screen while scroll progress drives the animation within it.

```javascript
ScrollTrigger.create({
  trigger: '.story-section',
  start: 'top top',
  end: '+=3000',   // pin for 3000px worth of scroll
  pin: true,       // the section stays fixed
  scrub: true
});
```

Pinning is used for the image sequence sections (the canvas stays full screen while scroll progress changes frames), for scroll-driven 3D scenes, and for chapter-by-chapter storytelling layouts.

---

### 7.5 Smooth Scrolling — Lenis

Browsers have native scroll — it works, but it feels mechanical and instantaneous. High-end websites use a smooth scroll library that adds inertia and easing to scroll movement.

**Lenis** is the current standard. It intercepts native scroll events and replaces them with a smooth, eased version — scroll feels like it's sliding through butter.

```javascript
import Lenis from '@studio-freight/lenis';

const lenis = new Lenis({
  duration: 1.2,
  easing: (t) => Math.min(1, 1.001 - Math.pow(2, -10 * t)),
  smooth: true,
});

function raf(time) {
  lenis.raf(time);
  requestAnimationFrame(raf);
}
requestAnimationFrame(raf);
```

Lenis is always connected to GSAP ScrollTrigger so both systems use the same scroll values.

---

### 7.6 Parallax Effects

Parallax is when different elements move at different speeds relative to scroll — creating the illusion of depth. Foreground elements move faster, background elements move slower.

```javascript
// Fast-moving foreground element
gsap.to('.foreground-img', {
  scrollTrigger: { trigger: '.section', scrub: true },
  y: -100  // moves 100px upward across the scroll zone
});

// Slow-moving background element
gsap.to('.background-img', {
  scrollTrigger: { trigger: '.section', scrub: true },
  y: -30   // moves only 30px — creates depth perception
});
```

Parallax comes in many forms:
- Vertical parallax (classic — background slides slower than content)
- Horizontal parallax (used in horizontal-scroll layouts)
- Mouse parallax (elements shift based on mouse position — see 7.7)
- Layer parallax (multiple layers at different depths)

---

### 7.7 Cursor & Mouse Interactions

High-end websites often react to mouse position in subtle ways that create a feeling of depth and aliveness.

**Custom Cursor**
A custom-designed cursor replaces the default browser cursor. It often has two layers — a small dot that follows exactly, and a larger ring that follows with a delay (creating a magnetic, organic feel).

**Mouse Parallax / Magnetic Effect**
Elements subtly shift toward or away from the cursor, as if magnetically attracted.

```javascript
document.addEventListener('mousemove', (e) => {
  const x = (e.clientX / window.innerWidth - 0.5) * 2;  // -1 to 1
  const y = (e.clientY / window.innerHeight - 0.5) * 2;

  gsap.to('.hero-content', {
    x: x * 20,  // move 20px in cursor direction
    y: y * 10,
    duration: 0.8,
    ease: 'power2.out'
  });
});
```

**Hover Effects on Cards**
The 3D tilt effect — cards rotate in 3D to follow the cursor position, as if they have physical depth. This is done with CSS transform rotateX/rotateY values calculated from mouse position relative to the card.

---

### 7.8 Page Transitions

When navigating between pages, instead of an instant white flash, high-end sites have designed transitions. Common approaches:

**Curtain/Wipe** — a colored block sweeps across the screen, covering the old page, then sweeps away to reveal the new page.

**Fade** — the page fades to black, then the new page fades in.

**Morph** — a clicked element (like a card) expands to fill the screen and becomes the new page.

**Implementation:**
Page transitions in React are typically handled with Framer Motion's AnimatePresence (wraps pages, handles exit animations) combined with Next.js App Router's route transition hooks.

For non-React sites, **Barba.js** is the standard library. It hooks into link clicks, handles the transition animation, then swaps the page content.

---

### 7.9 Framer Motion (Motion)

Framer Motion (now called simply Motion) is the React-native animation library. While GSAP works on any webpage, Framer Motion is specifically designed for React components.

**Key concepts:**

`motion.div` — a GSAP-like animated version of any HTML element.

```jsx
import { motion } from 'motion/react';

<motion.div
  initial={{ opacity: 0, y: 30 }}
  animate={{ opacity: 1, y: 0 }}
  transition={{ duration: 0.6, ease: [0.25, 0.46, 0.45, 0.94] }}
>
  Hello World
</motion.div>
```

`AnimatePresence` — handles exit animations when components unmount (crucial for page transitions, modals closing, lists items removing).

`useScroll` — gives a scroll progress value (0 to 1) you can tie to any motion value.

`useSpring` — converts a value to a spring-physics-based smoothed version (creates that natural, physical feel).

Framer Motion is used for: component-level animations (modals, dropdowns, tooltips), page transitions, hover states on interactive elements, scroll-linked UI effects.

GSAP is used for: complex scroll-driven sequences, timeline-based storytelling, the image sequence canvas effect, SVG animations. The two complement each other on the same site.

---

### 7.10 Three.js & WebGL — 3D in the Browser

**WebGL** — a low-level browser API that talks directly to the device's GPU to render 3D graphics. Without a library, working with WebGL is like programming in assembly language — extremely powerful, extremely complex.

**Three.js** — the library that makes WebGL accessible. It provides an abstraction of cameras, scenes, meshes, lights, and materials that you compose in JavaScript to create 3D experiences.

**React Three Fiber (R3F)** — Three.js expressed as React components. Instead of imperative Three.js code, you write declarative JSX. Most production React apps use R3F over raw Three.js.

**The Components of a 3D Scene:**

**Scene** — the container everything lives in. Think of it as the 3D world.

**Camera** — the viewpoint. PerspectiveCamera (mimics human eye with depth/perspective) or OrthographicCamera (no perspective — objects stay the same size regardless of distance, like a blueprint view). The position, rotation, and field of view of the camera determine what you see.

**Renderer** — the engine that draws the scene to the canvas. WebGLRenderer handles all the GPU calls.

**Mesh** — any 3D object. Made of two parts:
- **Geometry** — the shape (sphere, box, torus, plane, or loaded from GLB)
- **Material** — how it looks (color, texture maps, reflectivity, transparency)

Common built-in geometries:
```javascript
new THREE.BoxGeometry(1, 1, 1)          // cube
new THREE.SphereGeometry(1, 32, 32)     // sphere with 32 segments of detail
new THREE.TorusGeometry(1, 0.3, 16, 100) // donut shape
new THREE.PlaneGeometry(10, 10)          // flat plane
new THREE.CylinderGeometry(0.5, 0.5, 2) // cylinder
```

**Lighting:**
- **AmbientLight** — uniform light from all directions. Prevents pure shadow.
- **DirectionalLight** — parallel rays, like sunlight. Creates defined shadows.
- **PointLight** — light radiates from a point in all directions, like a bulb.
- **SpotLight** — cone of light, like a theatrical spotlight.
- **HemisphereLight** — sky color from above, ground color from below.
- **Environment Map (HDRI)** — an image of a real environment used to provide realistic reflections and ambient lighting on materials. Loaded from Poly Haven .hdr files.

**Loading a 3D Model (GLB):**

```jsx
// React Three Fiber
import { useGLTF } from '@react-three/drei';

function PlaneModel() {
  const { scene } = useGLTF('/models/jet.glb');
  return <primitive object={scene} />;
}
```

**Connecting 3D to Scroll (The Jet Example):**

```jsx
import { useScroll } from '@react-three/drei';
import { useFrame } from '@react-three/fiber';

function JetScene() {
  const scroll = useScroll();  // gives scroll.offset: 0 to 1

  useFrame(() => {
    // As scroll goes 0→1, jet rotates 0→360 degrees
    jetRef.current.rotation.y = scroll.offset * Math.PI * 2;

    // Camera moves in a path around the jet
    camera.position.x = Math.sin(scroll.offset * Math.PI) * 5;
    camera.position.z = Math.cos(scroll.offset * Math.PI) * 5;
    camera.lookAt(0, 0, 0);
  });
}
```

---

### 7.11 Post-Processing Effects

Post-processing adds cinematic visual effects on top of the rendered 3D scene, similar to color grading and effects in film editing.

**Bloom** — makes bright areas glow and bleed light into surrounding areas. Used on emissive surfaces (glowing cockpit lights, neon accents). Creates the cinematic "lens light" look.

**Depth of Field (DoF)** — blurs objects that are not in focus, like a camera lens. Creates the illusion of real camera optics and directs attention.

**Vignette** — darkens the edges of the frame, drawing focus to center.

**Chromatic Aberration** — slightly splits the red and blue color channels, mimicking cheap lenses. Adds a gritty, analog feel.

**Film Grain** — adds noise texture over the scene. Removes the artificial cleanliness of CGI.

**SSAO (Ambient Occlusion)** — adds contact shadows in crevices of 3D objects in real time. Makes scenes look more grounded.

**Color Grading / LUT** — applies a color lookup table (like Instagram filters, but for the 3D scene). Warm, cool, desaturated, high contrast — changes the entire mood.

```jsx
// React Three Fiber + @react-three/postprocessing
import { EffectComposer, Bloom, DepthOfField, Vignette } from '@react-three/postprocessing';

<EffectComposer>
  <Bloom luminanceThreshold={0.8} intensity={1.5} />
  <DepthOfField focusDistance={0.01} focalLength={0.02} bokehScale={3} />
  <Vignette offset={0.3} darkness={0.7} />
</EffectComposer>
```

---

### 7.12 GLSL Shaders — The Deep Layer

Shaders are programs that run directly on the GPU, written in GLSL (OpenGL Shading Language). They are the source of the most visually stunning effects on the web — liquid metal, aurora effects, noise-based distortion, water ripples, heat haze.

**Two types of shaders:**

**Vertex Shader** — runs once per vertex (corner) of a 3D mesh. Controls the position of each point in 3D space. Used to make meshes wave, distort, breathe.

**Fragment Shader** — runs once per pixel on the rendered surface. Controls the color of each pixel. Used to generate procedural textures, gradients, patterns, and visual effects entirely in math — no image files.

A simple wave effect on a plane geometry:
```glsl
// Vertex shader
void main() {
  vec3 pos = position;
  pos.z += sin(pos.x * 3.0 + uTime * 2.0) * 0.2;  // wave along X axis
  gl_Position = projectionMatrix * modelViewMatrix * vec4(pos, 1.0);
}
```

**Shaders are used for:**
- Animated backgrounds (noise fields, flowing gradients)
- Liquid and fluid effects
- Particle systems
- Distortion effects on images (hover distortions, reveal effects)
- Custom materials on 3D objects

---

### 7.13 Particle Systems

Thousands to hundreds of thousands of small points animated in 3D space. Used for:
- Atmospheric starfields
- Dust, smoke, or ember effects around 3D models
- Reactive particles that respond to mouse or scroll
- Data visualization in 3D space
- Morphing particle clouds (particles in one shape morph to another)

In Three.js, particles use `Points` geometry — a geometry of vertices rendered as dots, with a shader controlling their size and appearance.

```javascript
const geometry = new THREE.BufferGeometry();
const positions = new Float32Array(10000 * 3);  // 10,000 particles × xyz

for (let i = 0; i < positions.length; i++) {
  positions[i] = (Math.random() - 0.5) * 20;   // random positions in a 20-unit cube
}

geometry.setAttribute('position', new THREE.BufferAttribute(positions, 3));

const material = new THREE.PointsMaterial({ size: 0.02, color: 0xffffff });
const particles = new THREE.Points(geometry, material);
scene.add(particles);
```

---

### 7.14 Combined Effects — How It All Comes Together

The most impressive websites layer multiple techniques simultaneously. For your jet website, a realistic implementation might be:

**Section 1: Hero**
- Lenis smooth scroll active
- Hero text enters with GSAP SplitText character animation
- Background: particle system in Three.js with ambient particles floating
- GSAP ScrollTrigger begins the cinematic scroll zone

**Section 2: Window Zoom (Scroll-Scrubbed Image Sequence)**
- ScrollTrigger pins the section for 4000px of scroll
- Canvas draws the correct video frame based on scroll progress
- Text overlays fade in/out at specific scroll positions via GSAP timelines

**Section 3: 3D Jet Model**
- R3F renders the jet GLB with PBR materials and HDRI lighting
- Bloom post-processing on engine glow emissive areas
- ScrollTrigger scrubs camera around the jet (front → side → top → rear)
- OrbitControls activates when scroll is not in progress (drag to inspect)
- Depth of Field blurs background elements
- GSAP animates text/spec overlays appearing at scroll milestones

**Section 4: Features/Specs**
- Framer Motion handles component entrances as cards come into view
- CSS hover effects on each feature card
- Lottie animations for each feature icon (animated icon illustrations)
- SplitText on section headings for character-by-character reveals

**Section 5: Page Transition to Interior Section**
- Barba.js or Framer Motion AnimatePresence handles the transition
- A custom curtain effect wipes between sections

---

## Part 8 — Development Stack & Implementation

### 8.1 Choosing the Framework

**Next.js (React)** — the standard for 2024–2026. App Router, built-in image optimization, server-side rendering, file-based routing, huge ecosystem. Use this unless there's a reason not to.

**Vanilla JS + Vite** — no framework. Simpler setup, smaller bundle. Good for pure creative experiments, single-page experiences. Still common in creative studios.

**Astro** — newer framework focused on performance. Minimal JavaScript by default. Good for content-heavy sites with some interactive islands.

**Nuxt.js** — Next.js equivalent for Vue.js. Used if the team prefers Vue.

### 8.2 CSS Strategy

**Tailwind CSS** — utility-first CSS. No writing custom CSS, everything is class-based. Fastest for layout and common styles. Industry standard in 2025.

**CSS Modules** — scoped CSS files per component. Good when you need complex custom styles.

**Styled Components / Emotion** — CSS-in-JavaScript. Less common now with Tailwind's dominance.

For creative effects (custom clip-paths, CSS variables driven by JS, complex gradients), raw CSS custom properties alongside Tailwind is the standard approach.

### 8.3 Project Folder Structure

```
/project
├── /public
│   ├── /fonts          ← .woff2 font files
│   ├── /models         ← .glb 3D model files
│   ├── /frames         ← image sequence WebP files
│   ├── /textures       ← texture images
│   └── /lottie         ← .json Lottie animation files
├── /src
│   ├── /components
│   │   ├── /ui         ← reusable UI components (Button, Card)
│   │   ├── /sections   ← page sections (Hero, Features, JetModel)
│   │   └── /three      ← Three.js/R3F components
│   ├── /hooks          ← custom React hooks (useScrollProgress, useMousePosition)
│   ├── /lib            ← utility functions
│   ├── /styles         ← global CSS, Tailwind config
│   └── /app            ← Next.js App Router pages
└── package.json
```

### 8.4 Performance Fundamentals

**Core Web Vitals** — Google's performance metrics that affect SEO:
- **LCP (Largest Contentful Paint)** — how fast the main content loads. Target: < 2.5s
- **FID/INP (Interaction to Next Paint)** — how responsive the page is. Target: < 200ms
- **CLS (Cumulative Layout Shift)** — how much the layout shifts during load. Target: < 0.1

**Key optimizations:**
- All images in WebP or AVIF format
- Lazy loading (images below the fold load only when approached)
- 3D models compressed with Draco/gltfpack
- Image sequences preloaded progressively (load first/last 20 frames first)
- Code splitting (JavaScript only loads when the component is needed)
- Web Workers for heavy computation (particle systems, physics) off the main thread
- 60fps target for all animations — never animate non-GPU-accelerated properties (width, height, top, left — these cause layout reflow). Only animate: `transform`, `opacity`, `filter`.

---

## Part 9 — Deployment

### 9.1 Hosting Options

**Vercel** — the standard for Next.js. One-click deploy from GitHub. Automatic preview deployments on every PR. Global CDN. Free tier is generous. The default choice for 95% of Next.js projects.

**Netlify** — similar to Vercel. Works well for any framework. Slightly more flexible for complex build configurations.

**Cloudflare Pages** — extremely fast global CDN. Free tier. Good for static/JAMstack sites.

**AWS Amplify / S3 + CloudFront** — enterprise-grade. More configuration required. Used when deep AWS integration is needed.

**Self-hosted (VPS)** — DigitalOcean, Hetzner, Linode. Full control. Docker containers. Nginx reverse proxy. More DevOps work.

### 9.2 Deployment Workflow

```
Local Development
      ↓
Git push to GitHub
      ↓
Vercel automatically detects push
      ↓
Runs build command (next build)
      ↓
Deploys to preview URL (share with client for review)
      ↓
Client approves
      ↓
Merge to main branch
      ↓
Auto-deploys to production URL
      ↓
Vercel CDN distributes globally
```

### 9.3 Domain & DNS

Custom domain connected via DNS records pointing to Vercel/Netlify's servers. SSL certificate (HTTPS) is automatically provisioned free via Let's Encrypt.

---

## Part 10 — Master Tools Reference

Every tool mentioned, organized by category:

### Design
| Tool | Purpose | Cost |
|---|---|---|
| Figma | UI/UX design, prototyping, design systems | Free tier / $12/mo Pro |
| Adobe XD | Older alternative to Figma | CC subscription |
| Framer | Code-based design + prototyping | Free tier / $20/mo |
| Google Stitch | AI-generated design systems | Free |
| Milanote | Mood boarding and project planning | Free tier |
| Coolors.co | Color palette generation | Free |
| Fontpair.co | Font pairing inspiration | Free |
| Fontshare | Free high-quality fonts | Free |

### Motion & Lottie
| Tool | Purpose | Cost |
|---|---|---|
| Adobe After Effects | Motion graphics, Lottie source | CC subscription |
| Bodymovin (AE Plugin) | Export AE animations as Lottie JSON | Free |
| LottieFiles | Lottie library and editor | Free tier |
| Rive | Interactive animation design | Free tier |
| Cavalry | Motion graphics alternative to AE | Free tier |

### 3D
| Tool | Purpose | Cost |
|---|---|---|
| Blender | 3D modeling, rigging, animation | Free |
| Spline | Browser-based 3D for web | Free tier |
| Cinema4D | Professional 3D (studio standard) | ~$750/yr |
| Substance Painter | 3D texturing | CC subscription |
| Sketchfab | 3D model marketplace | Free tier |
| Poly Haven | Free HDRI, textures, models | Free |
| Meshy.ai | AI text-to-3D model generation | Free tier |
| Tripo3D | AI image-to-3D model generation | Free tier |
| gltf-transform | CLI 3D model optimization | Free |

### Development
| Tool | Purpose | Cost |
|---|---|---|
| VS Code | Code editor | Free |
| Node.js | JavaScript runtime | Free |
| Git + GitHub | Version control | Free |
| Next.js | React framework | Free |
| Tailwind CSS | Utility CSS | Free |
| GSAP | Animation library | Free (plugins need Club) |
| React Three Fiber | Three.js in React | Free |
| @react-three/drei | R3F helper library | Free |
| @react-three/postprocessing | 3D post-processing effects | Free |
| Framer Motion (Motion) | React animation library | Free |
| Lenis | Smooth scrolling | Free |
| Lottie Player | Play Lottie animations | Free |
| Rive Runtime | Play Rive animations | Free |
| Barba.js | Page transitions | Free |
| FFmpeg | Video processing CLI | Free |

### Performance & Deployment
| Tool | Purpose | Cost |
|---|---|---|
| Vercel | Hosting + CI/CD for Next.js | Free tier |
| Netlify | Hosting alternative | Free tier |
| Cloudflare | CDN + DNS + optimization | Free tier |
| Lighthouse | Performance auditing (in Chrome DevTools) | Free |
| Squoosh | Image compression | Free |
| Handbrake | Video compression | Free |
| PageSpeed Insights | Google's performance scorer | Free |

---

## Summary: The Full Flow at a Glance

```
DISCOVERY
  Creative brief → Mood board → Competitive analysis
  → Information architecture → User flow mapping

UX DESIGN
  Low-fi wireframes → High-fi wireframes → Prototype
  Tools: Figma, ProtoPie

VISUAL DESIGN
  Design system (colors, type, spacing, components)
  → Full page mockups (desktop/tablet/mobile)
  Tools: Figma

MOTION PLANNING
  Animation spec: what moves, when, how
  Easing curves, timing, stagger values defined
  Tools: Figma, ProtoPie, reference videos

ASSET CREATION
  ├── Photography/Video → .webp / .mp4
  ├── SVG illustrations → .svg
  ├── Lottie animations → .json (After Effects + Bodymovin)
  ├── Rive animations → .riv (Rive.app)
  ├── Image sequences → .webp frames (FFmpeg from video)
  ├── 3D models → .glb (Blender → gltf-transform)
  ├── Textures/PBR → .webp maps (Substance Painter / Poly Haven)
  └── Fonts → .woff2

DEVELOPMENT
  Framework: Next.js + Tailwind + TypeScript
  CSS: transitions, hover effects
  UI animation: Framer Motion
  Scroll: Lenis + GSAP ScrollTrigger
  Image sequence: Canvas API + GSAP
  Lottie: @lottiefiles/react-lottie-player
  3D: React Three Fiber + drei + postprocessing
  Shaders: GLSL via ShaderMaterial / drei/shaderMaterial
  Page transitions: Framer Motion AnimatePresence

OPTIMIZATION
  Images: WebP, lazy loading, correct sizing
  3D: Draco compressed, LOD, lazy loaded
  JS: code splitting, dynamic imports
  Core Web Vitals: LCP < 2.5s, CLS < 0.1

DEPLOYMENT
  Git → GitHub → Vercel auto-deploy
  Custom domain + SSL
  CDN distribution
```

---

*This document covers the complete traditional production workflow for high-end immersive websites. Every concept here has a modern AI-assisted equivalent — Claude Code handles the development phases, Figma MCP bridges design and code, and tools like Meshy/Spline accelerate 3D asset creation. The workflow is the same; the labor distribution has shifted dramatically.*
