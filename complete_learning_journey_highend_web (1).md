# Complete Learning Journey: High-End Immersive Website Development
### Personalized for Ryan — From Where You Are to Where You Want to Be

---

## Before You Start: How to Use This Guide

This is not a checklist to complete sequentially before you build anything.
It is a **phased roadmap** where you build real things from month 3 onward,
and fill in knowledge gaps in context as projects demand them.

**Your starting position:**
- React, Node.js, Python, Flask — already comfortable
- Basic websites built manually — foundation exists
- AI/agent development background — massive advantage for the modern workflow
- Goal: High-end immersive websites with 3D, scroll storytelling, and motion

**What this guide covers:**
1. The full domain map — every concept, every tool
2. Two parallel paths — Code-based and No-Code (Webflow/Framer)
3. Phase-by-phase learning with time estimates
4. What to build at each stage
5. Resources for every topic
6. The traditional workflow vs. the modern AI-assisted workflow
7. The complete tools ecosystem

**Time investment to high competency: 6–8 months of consistent practice.**
Not full-time — 1.5–2 hours per day alongside your current work.

---

## Part 1 — The Full Domain Map

### The Three Paths in This Space

Understanding these three paths prevents you from confusing tools that serve
different purposes.

---

#### Path A: Code-Based (Your Primary Path)
**Stack:** Next.js + Tailwind + GSAP + React Three Fiber + Claude Code

Full control. Highest ceiling. Steepest initial learning curve.
Every effect is possible. Performance is in your hands.
This is what creative agencies, award-winning studios, and freelancers
building $10k–$50k websites use.

**You are learning this path.**

---

#### Path B: No-Code / Low-Code — Webflow
**Stack:** Webflow CMS + Webflow Interactions + Finsweet libraries

Webflow is a visual website builder where you drag and drop,
but the underlying model is real CSS and HTML — not templates.
You design in a visual editor, Webflow generates clean semantic HTML/CSS.

**What Webflow can do:**
- Complex multi-page websites with CMS (blog, portfolio, e-commerce)
- Scroll animations via Webflow Interactions (their built-in animation system)
- Parallax, hover effects, page transitions — all without code
- Custom code embeds (you can inject GSAP or Three.js into a Webflow project)

**What Webflow cannot do natively:**
- Real-time 3D (Three.js/R3F)
- Canvas image sequences
- Custom GLSL shaders
- Complex multi-stage scroll timelines at GSAP's level

**When to use Webflow:**
- Client sites where content editors need to update copy without touching code
- Marketing sites, landing pages, portfolios for non-technical clients
- Rapid prototyping of multi-page layouts
- Projects where CMS is the main requirement

**Webflow's role in your skill set:**
A valuable second tool. Many freelancers build Webflow sites for clients
(fast to deliver, CMS built-in) while reserving the full code stack
for immersive showcase/brand experiences. Knowing both makes you more versatile.

---

#### Path C: No-Code / Low-Code — Framer
**Stack:** Framer (design + publish in one tool)

Framer is the most design-forward no-code tool. It started as a prototyping
tool and became a full website builder. The key difference from Webflow:
Framer has React components built in. You can write actual React code
inside Framer components. The line between design and code is intentionally blurred.

**What Framer can do:**
- Beautiful, animation-forward websites extremely fast
- Built-in physics-based animations (spring, inertia)
- Scroll-linked animations via their visual timeline
- Real React code components embedded anywhere
- CMS for blog-style content
- Publish directly from Framer — no separate hosting needed

**What Framer cannot do:**
- Full Three.js/WebGL 3D scenes (you embed an iframe or use code components)
- Custom shader effects
- Complex canvas sequences at GSAP's level

**When to use Framer:**
- Your own portfolio website
- Design-heavy marketing pages where you want to move fast
- When a client wants something beautiful but not immersive/3D
- Prototyping motion concepts before implementing in code

**Framer's role in your skill set:**
Framer is the fastest way to build a beautiful website. Many professionals
use Framer for their own portfolio/personal brand while using the full code
stack for client work. It's also the best tool for designing and testing
motion concepts before bringing them into code.

---

### How the Three Paths Relate

```
COMPLEXITY & CONTROL
        ↑
        |  Code Path (Next.js + GSAP + R3F)
        |  — Full 3D, shaders, canvas sequences
        |  — Maximum control, maximum effort
        |
        |  Framer (Low-Code, Design-First)
        |  — Beautiful animations, React components
        |  — Fast for portfolios and marketing
        |
        |  Webflow (No-Code, CMS-First)
        |  — Multi-page sites with content management
        |  — Fast for client delivery
        ↓
SPEED OF DELIVERY
```

For high-end immersive websites: **Code Path is the answer.**
For client sites needing CMS and fast turnaround: **Webflow.**
For your own portfolio: **Framer or Code Path.**

You should learn all three eventually. The order: Code Path → Framer → Webflow.

---

## Part 2 — Foundations Audit

What you already have vs. what you need.

### You Already Have (Don't Re-Learn)
✅ React — component model, hooks, state, props
✅ JavaScript — async/await, ES6+, DOM manipulation
✅ Node.js / npm ecosystem
✅ Python (less relevant here but useful for tooling)
✅ Git / GitHub — version control
✅ Basic HTML/CSS — block model, flexbox basics
✅ Working with APIs and integrations
✅ AI tool familiarity — massive advantage for the modern workflow

### Gaps to Fill (The Learning Path Below)
❌ Design fundamentals — typography, color, composition, visual hierarchy
❌ Advanced CSS — custom properties, grid, clip-path, animations
❌ GSAP — the core animation engine
❌ Three.js / React Three Fiber — 3D in the browser
❌ Blender basics — 4 specific skills for the asset pipeline
❌ Design tools — Figma at a working level
❌ Next.js App Router — you may know pages router, App Router is different
❌ Tailwind CSS v4 — utility-first CSS
❌ Lenis, Framer Motion, and the supporting animation libraries
❌ Webflow — as a second tool
❌ Framer — as a third tool
❌ AI asset pipeline — Midjourney, Runway, Meshy

---

## Part 3 — The Learning Path

### Phase 0: Design Eye & Visual Fundamentals
**Duration: 2–3 weeks | Daily: 1 hour**

You cannot direct Claude, a designer, or any tool well without
a trained eye for design. This is the most underestimated skill
in web development. Developers who can't judge design quality
build things that look "developer-made." This phase fixes that.

**What to learn:**

**Typography**
- Type anatomy: serif vs sans-serif vs display vs monospace
- Type scale: how sizes relate (Major Third, Perfect Fourth scales)
- Line height and its effect on readability
- Letter spacing: when to use it and when not to
- Pairing fonts: display + body, how to make them complement each other
- Loading fonts correctly on web (.woff2, preload, font-display: swap)

**Color Theory**
- HSL color model (more useful than RGB for web design)
- Contrast ratios — accessibility (WCAG AA: 4.5:1 minimum)
- Creating a palette: primary, surface, text, accent, error
- Dark mode palettes — why pure black (#000) is wrong
- Gradients: linear, radial, mesh gradients
- How color creates mood (warm vs cool, saturated vs muted)

**Composition & Layout**
- Visual hierarchy: what the eye sees first, second, third
- The 8px grid system — why everything aligns to multiples of 8
- Whitespace: using negative space intentionally, not wastefully
- Z-axis: depth, layering, overlapping elements
- Reading patterns: F-pattern, Z-pattern, center-stage

**Visual Inspiration (daily habit, 20 minutes)**
- **Awwwards.com** — daily winner. Deconstruct every site: what technique is this?
- **Dribbble** — UI/product design inspiration
- **Behance** — full case studies of design projects
- **Godly.website** — curated creative web collection
- **Brutalist Websites** — extreme design direction reference

**Resources:**
- *Refactoring UI* by Adam Wathan & Steve Schoger — the best design book for developers. Practical, example-heavy, no abstract theory. Read this.
- Google Fonts Knowledge (fonts.google.com/knowledge) — typography specifically
- Shift Nudge (shiftnudge.com) — UI design course for developers
- Kevin Powell (YouTube) — CSS layout and design for developers

**Practice:**
Every day, pick one site from Awwwards. Write 3 sentences:
what's the visual direction, what technique creates the main effect,
what makes it feel premium vs generic. 21 days of this trains your eye faster
than any course.

---

### Phase 1: Figma — Design Tool Foundation
**Duration: 2 weeks | Daily: 45 minutes**

You need Figma at a working level to use the Figma MCP effectively,
to communicate with designers, and to create your own layouts.
You do not need to be a Figma expert — just proficient.

**What to learn in Figma:**

**Core Skills**
- Frames vs Groups — understanding the difference
- Auto Layout — Figma's flexbox equivalent (the most important feature)
- Components and variants — creating reusable design elements
- Styles — color styles, text styles, effect styles (proto-design-tokens)
- Variables — Figma's design token system (maps to CSS custom properties)
- Prototype mode — linking frames, creating scroll interactions
- Dev Mode — reading the CSS values Figma generates

**For the AI Workflow Specifically**
- Naming conventions: name layers clearly (Button/Primary/Hover, not Rectangle 23)
  because Figma MCP reads layer names to understand component structure
- Exporting: SVG for icons/illustrations, PNG for photos, WebP via export settings
- Design tokens: setting up local variables that become your design.md

**Resources:**
- Figma's official YouTube channel — free, comprehensive, made by the team
- *Figma for Beginners* by Flux Academy (YouTube) — practical projects
- designcourse.com — Gary Simon's Figma + design fundamentals

**Practice:**
Redesign the layout of one page you admire — not visually copying it,
but recreating the *structure* in Figma. Do this 3 times with different sites.

---

### Phase 2: Advanced CSS — The Layer Between Design and Code
**Duration: 2–3 weeks | Daily: 1 hour**

You know basic CSS. What you need is the advanced CSS that powers
the visual effects in high-end sites, and Tailwind CSS which is the
standard utility framework for 2025–2026.

**Advanced CSS Topics**

**CSS Custom Properties (Variables)**
```css
:root {
  --color-accent: #C8A96E;
  --space-4: 16px;
  --duration-fast: 150ms;
}
.button { background: var(--color-accent); }
```
These are the CSS equivalent of design tokens. Every high-end site uses them.
They can be updated by JavaScript (enabling scroll-driven color changes,
theme switching, and animation state management).

**CSS Grid — Advanced**
- Named grid areas
- Overlapping elements (place items on the same grid cell)
- Subgrid (new, powerful for aligned nested layouts)
- This is how editorial, magazine-style layouts are built

**CSS Clip-Path**
Creates non-rectangular element shapes — diagonal cuts, angled sections,
circular reveals, polygon shapes. Used extensively in creative layouts.
```css
.section { clip-path: polygon(0 0, 100% 0, 100% 90%, 0 100%); }
```

**CSS Transforms and 3D**
`transform: perspective(1000px) rotateX(15deg)` creates CSS 3D effects.
Used for card tilt effects, depth layers, and perspective grids.

**CSS Filters and Backdrop-Filter**
`backdrop-filter: blur(20px)` creates the glassmorphism/frosted glass effect.
`filter: brightness(0.8) contrast(1.2)` for image color grading.

**CSS Animations (@keyframes)**
Used for ambient loops (floating, pulsing, rotating) that run continuously
without JavaScript. Offloads simple animations from the JS thread.

**CSS Scroll-Snap**
Native scroll snapping between sections. Useful for fullscreen section layouts.

**Tailwind CSS v4**
The utility-first CSS framework. Instead of writing custom CSS classes,
you apply pre-defined utility classes directly in HTML/JSX.

Why it matters: Every modern Next.js project uses Tailwind.
Claude Code generates Tailwind by default. You need to be able to
read and write Tailwind fluently.

Key Tailwind concepts:
- Utility classes: `flex`, `items-center`, `gap-4`, `text-xl`, `font-bold`
- Responsive prefixes: `md:flex-row`, `lg:text-5xl`
- Hover/focus states: `hover:scale-105`, `focus:outline-none`
- Arbitrary values: `w-[437px]`, `top-[73px]` (when standard scale doesn't fit)
- CSS variables integration: `bg-[var(--color-accent)]`
- v4 changes: CSS-first config, @theme directive replaces tailwind.config.js

**Resources:**
- Kevin Powell (YouTube) — the best CSS educator on the internet, free
- CSS Tricks (css-tricks.com) — reference and deep dives
- Tailwind CSS official docs (tailwindcss.com) — excellent, start with "Core Concepts"
- Josh Comeau (joshwcomeau.com) — interactive CSS articles, extremely high quality

**Practice:**
Build 5 CSS-only UI components: a glassmorphism card, a diagonal section break,
a CSS-only animated gradient background, a card tilt effect (CSS 3D),
and a clip-path reveal on hover. No JavaScript allowed. Pure CSS.

---

### Phase 3: Next.js App Router
**Duration: 1–2 weeks | Daily: 1 hour**

You know React. Next.js App Router is the production framework.
The App Router (Next.js 13+) is different enough from Pages Router
to deserve explicit attention.

**What to learn:**

**App Router Structure**
```
/app
  layout.tsx      ← Persistent shell (nav, footer, providers)
  page.tsx        ← Route content
  loading.tsx     ← Suspense loading UI
  error.tsx       ← Error boundary
  /about
    page.tsx      ← /about route
```

**Server vs Client Components**
- Default: Server Components (rendered on server, no React hooks, no browser APIs)
- `'use client'` directive: Client Components (have hooks, event handlers, browser access)
- Rule: Keep components server by default. Add `'use client'` only when needed.
- GSAP and Three.js are always client-side. Wrap in `'use client'`.

**Dynamic Imports (Critical for 3D)**
Three.js cannot run on the server (no `window`, no WebGL). Use dynamic import:
```tsx
const JetScene = dynamic(() => import('@/components/three/JetScene'), {
  ssr: false,
  loading: () => <div className="h-screen bg-black" />
});
```

**Image Optimization**
Next.js `<Image>` component handles WebP conversion, lazy loading,
blur placeholders, and responsive sizes automatically.
Never use `<img>` for content images in Next.js.

**Font Loading**
```tsx
import { localFont } from 'next/font/local';
const clashDisplay = localFont({ src: './fonts/ClashDisplay.woff2' });
```

**Resources:**
- Next.js official docs — excellent (nextjs.org/docs)
- Jack Herrington (YouTube, "PedroTech") — practical Next.js tutorials
- Josh tried coding (YouTube) — Next.js App Router specifically

**Practice:**
Rebuild a basic 3-page site you've built before using Next.js App Router.
Focus on the routing, layout system, and correct use of Server vs Client components.

---

### Phase 4: GSAP — The Core Skill
**Duration: 5–6 weeks | Daily: 1.5 hours**

This is the most important technical skill in this entire guide.
Spend the most time here. Get genuinely good at it.

**Week 1–2: Core GSAP**

Tweens: gsap.to(), gsap.from(), gsap.fromTo()
Timelines: gsap.timeline(), sequencing, labels, overlaps ('-=0.2')
Easing: power1–4, expo, circ, back, elastic, bounce — and when each is right
Properties: transform (x, y, scale, rotation, skewX), opacity, filter
Stagger: animating multiple elements in sequence
Callbacks: onStart, onComplete, onUpdate

Spend one week only in CodePen. No framework, no build tool.
Just GSAP CDN + HTML. Build 10 small experiments:
- A text entrance animation with stagger
- A timeline that sequences 5 different elements
- A card flip animation
- A loading sequence
- A button hover with spring easing

**Week 3–4: ScrollTrigger**

This changes everything. Learn it deeply.

Core concepts:
- trigger, start, end — defining the scroll zone
- toggleActions — what happens on enter/leave/enterBack/leaveBack
- scrub — connecting animation progress to scroll position
- pin — fixing an element while scroll continues
- markers — debugging scroll positions
- snap — snapping scroll to waypoints
- batch — animating groups of elements as they enter viewport

Patterns to master:
- Trigger-on-enter: element animates when it enters the viewport (once)
- Scrub animations: animation tied directly to scroll position
- Pinned sections: element stays fixed while content animates inside it
- Horizontal scroll sections: content scrolls sideways while page scrolls down
- Parallax: different elements at different scroll speeds

Build these 5 scroll projects in CodePen:
1. A page where each section's heading word-by-word on enter
2. A horizontal scrolling gallery inside a vertical scroll page
3. A number counter that counts up as you scroll to it
4. A progress bar that fills based on page scroll position
5. A pinned section where 3 images swap out as you scroll

**Week 5: GSAP Plugins**

SplitText — splitting text into characters/words/lines for per-unit animation.
This is the single most used plugin for high-end text effects.

DrawSVG — animating SVG strokes as if being drawn.
Used for animated line illustrations, path reveals.

MorphSVG — morphing between SVG shapes.
Used for icon transitions, shape-shifting hero elements.

Flip — animating layout changes smoothly.
Used for expanding cards, grid → list view transitions.

MotionPath — moving elements along an SVG path.
Used for particles along a curve, animated arrows.

Note: SplitText, DrawSVG, MorphSVG, Flip are GSAP Club plugins.
GSAP Club is $99–$150/year. It is worth it for professional work.
You can use free trial versions for learning.

**Week 6: GSAP + React Integration**

Using GSAP inside React requires specific patterns:
- useRef instead of querySelector to reference elements
- useGSAP hook (from @gsap/react) for proper cleanup
- ScrollTrigger.refresh() after layout changes
- Connecting ScrollTrigger to Lenis smooth scroll

Lenis setup:
```tsx
// lib/lenis.ts
const lenis = new Lenis();
gsap.ticker.add((time) => lenis.raf(time * 1000));
gsap.ticker.lagSmoothing(0);
ScrollTrigger.scrollerProxy(document.body, { ... });
```

**Resources:**
- GreenSock official docs (gsap.com/docs) — read every page in the Core section
- GreenSock CodePen collection — 1000+ examples, all interactive
- GreenSock YouTube — tutorial series, start from the beginning
- Creative Coding Club (Cassie Evans, YouTube) — GSAP tips and creative patterns
- Kyle Wetton / CreativeSpark YouTube — real-world GSAP projects

**The milestone test:**
Can you look at a website on Awwwards, identify the GSAP techniques being used,
and recreate the core scroll behavior in CodePen without looking anything up?
When yes, you've passed Phase 4.

---

### Phase 5: React Three Fiber & Three.js Concepts
**Duration: 6–8 weeks | Daily: 1.5 hours**

You don't need to master raw Three.js. You need to understand the concepts
and work fluently in React Three Fiber (R3F) — the React wrapper.

**Week 1–2: Three.js Core Concepts (via R3F)**

Do NOT start with raw Three.js. Start with R3F because your React knowledge
transfers directly. The concepts are the same.

Essential concepts:
- Canvas — the WebGL rendering surface
- Scene — the container for everything
- Camera — PerspectiveCamera (human-eye view) vs OrthographicCamera (no depth)
- Mesh = Geometry + Material — every 3D object
- Built-in geometries: BoxGeometry, SphereGeometry, PlaneGeometry, TorusGeometry
- Materials: MeshBasicMaterial (no lighting), MeshStandardMaterial (PBR, needs light)
- Lights: AmbientLight, DirectionalLight, PointLight, SpotLight
- The render loop — useFrame runs every frame (60fps) — this is where animation lives

Your first R3F scene:
```tsx
<Canvas camera={{ position: [0, 0, 5], fov: 60 }}>
  <ambientLight intensity={0.5} />
  <directionalLight position={[10, 10, 5]} />
  <mesh rotation={[0, time, 0]}>
    <boxGeometry args={[1, 1, 1]} />
    <meshStandardMaterial color="hotpink" />
  </mesh>
</Canvas>
```

Build 5 small R3F experiments:
1. A spinning cube with a colored material
2. A sphere with metalness and roughness (PBR material)
3. Multiple objects in a scene with different lights
4. A plane with a texture image applied
5. Camera movement on mouse position (lerp the camera toward cursor)

**Week 3: Loading 3D Models**

This is the core practical skill — loading your Meshy/Blender GLB files.

useGLTF hook from @react-three/drei:
```tsx
import { useGLTF } from '@react-three/drei';
function JetModel() {
  const { scene } = useGLTF('/models/jet.glb');
  return <primitive object={scene} />;
}
```

Key topics:
- Suspense boundary for loading states
- Draco decoder setup (for compressed models)
- Traversing the model to modify materials after load
- Clone instances (useGLTF.clone) for multiple instances of same model
- useAnimations for playing built-in GLB animations

**Week 4: Lighting & Environment**

This transforms your 3D from "looks like code" to "looks real."

- Environment maps (HDRI) — `useEnvironment` from drei or `<Environment>` component
- Loading .hdr files from Poly Haven for realistic reflections
- `<Environment preset="studio" />` — built-in presets for quick lighting
- Adjusting material envMapIntensity for reflection strength
- Tone mapping — how colors are rendered (ReinhardToneMapping, ACESFilmicToneMapping)
- Exposure — overall brightness of the scene

**Week 5: drei Helper Library**

@react-three/drei is a collection of helpers that make common tasks easy.
Essential components:

- `<OrbitControls>` — mouse drag to orbit around a model
- `<Environment>` — HDRI environment lighting
- `<ContactShadows>` — realistic soft shadows under objects
- `<Float>` — gentle floating animation wrapper
- `<Html>` — render HTML inside 3D space (for 3D labels/tooltips)
- `<Text>` — 3D text using troika-three-text
- `<Preload>` — preload assets before rendering
- `<useScroll>` — scroll progress value for scroll-linked 3D
- `<ScrollControls>` — scroll container for R3F scenes
- `<Sparkles>` — particle sparkle effect
- `<MeshDistortMaterial>` — distorting/morphing material
- `<MeshReflectorMaterial>` — realistic reflective floor

**Week 6: Post-Processing Effects**

@react-three/postprocessing adds cinematic effects.

```tsx
import { EffectComposer, Bloom, DepthOfField, 
         Vignette, ChromaticAberration } from '@react-three/postprocessing';

<EffectComposer>
  <Bloom luminanceThreshold={0.9} intensity={1.5} mipmapBlur />
  <DepthOfField focusDistance={0.01} focalLength={0.02} bokehScale={3} />
  <Vignette offset={0.3} darkness={0.6} />
  <ChromaticAberration offset={[0.002, 0.002]} />
</EffectComposer>
```

Effects to understand:
- Bloom — glow on bright surfaces. Essential for emissive materials.
- Depth of Field — camera lens blur for objects out of focus
- Vignette — darkened edges, cinematic frame
- Chromatic Aberration — color channel split, analog lens feel
- Film Grain — adds noise, removes CGI sterility
- SSAO — ambient occlusion, adds contact shadows in real time
- Color Grading / LUT — overall color mood of the scene

**Week 7: Scroll-Driven 3D (The Key Integration)**

Connecting your 3D scene to GSAP ScrollTrigger is the technique
that makes scroll-storytelling sites work.

Two approaches:

Approach 1: drei ScrollControls
```tsx
<ScrollControls pages={5}>
  <Scroll>
    <JetModel />
  </Scroll>
</ScrollControls>
```
Uses scroll.offset (0–1) inside useFrame to drive 3D properties.

Approach 2: GSAP refs
Create a ref to your Three.js object, then use GSAP to animate it:
```tsx
const jetRef = useRef();
gsap.to(jetRef.current.rotation, {
  scrollTrigger: { trigger: '.jet-section', scrub: 1 },
  y: Math.PI * 2  // full rotation
});
```

Patterns to build:
1. A 3D model that rotates as you scroll (basic scrub)
2. A camera that moves along a path as you scroll
3. A model where each scroll section highlights a different part
4. A scene where lights change color based on scroll position
5. A 3D model section combined with HTML text panels that sync

**Week 8: Shaders & Particles (Intro Level)**

You don't need to master shaders. But you need to understand enough
to direct Claude effectively and recognize when something needs a shader.

**What a shader is:**
A program that runs on the GPU, written in GLSL (C-like language).
Two types: vertex shaders (control 3D geometry) and fragment shaders (control pixel color).

Basic shader structure:
```glsl
// Fragment shader — controls pixel color
uniform float uTime;
varying vec2 vUv;

void main() {
  // Create an animated gradient based on UV coordinates and time
  vec3 color = mix(vec3(0.0, 0.0, 0.5), vec3(1.0, 0.5, 0.0), vUv.x + sin(uTime));
  gl_FragColor = vec4(color, 1.0);
}
```

Learn enough to:
- Understand what uTime, uResolution, vUv uniforms do
- Read a shader and roughly understand its effect
- Modify values in existing shaders to adjust effects
- Ask Claude for specific shader effects with accurate language

**Particle systems:**
```tsx
// 10,000 points in 3D space
const positions = useMemo(() => {
  const arr = new Float32Array(10000 * 3);
  for (let i = 0; i < arr.length; i++) arr[i] = (Math.random() - 0.5) * 10;
  return arr;
}, []);

<points>
  <bufferGeometry>
    <bufferAttribute attach="attributes-position" array={positions} itemSize={3} />
  </bufferGeometry>
  <pointsMaterial size={0.02} color="white" />
</points>
```

**Resources:**
- Three.js Journey by Bruno Simon (threejs-journey.com) — $95, the best 3D web course.
  Complete the first 50% (foundations + shaders intro). This alone is worth the cost.
- Wawa Sensei (YouTube) — R3F tutorials, free, very high quality
- Anderson Mancini (YouTube) — R3F + GSAP integration
- R3F official docs (docs.pmnd.rs/react-three-fiber)
- Three.js official docs (threejs.org/docs) — reference, not tutorial

**The milestone test:**
Can you take a GLB model from Meshy, load it in R3F with proper
HDRI lighting and bloom postprocessing, and connect its rotation
to a GSAP ScrollTrigger scrub? When yes, you've passed Phase 5.

---

### Phase 6: Blender Basics
**Duration: 1.5 weeks | Focus: 4 specific skills**

You are not becoming a 3D artist. You are learning exactly what
the AI-assisted pipeline requires from Blender. Nothing more.

**Skill 1: The Interface (2 hours)**
- Navigation: middle mouse to orbit, scroll to zoom, shift+middle to pan
- The 3D viewport, outliner, properties panel
- Object mode vs Edit mode (Tab to toggle)
- N panel (press N) — transform values and add-ons

**Skill 2: Importing and Inspecting a Model (1 hour)**
File → Import → glTF 2.0 (.glb/.gltf)
- How to see the polygon count (statistics in viewport overlay)
- How to identify broken geometry (face normals — Overlay menu → Face Orientation)
- How to inspect UV maps (UV Editor in workspace tabs)

**Skill 3: Polygon Reduction — Decimate Modifier (2 hours)**
The most important Blender skill for your workflow.
Most Meshy-generated models are 500K–1M polygons. Web needs under 100K.

1. Select the model
2. Go to Properties → Modifier properties (wrench icon)
3. Add Modifier → Generate → Decimate
4. Set Ratio to 0.1 (10% of original polygons)
5. Watch the polygon count drop
6. Apply the modifier when satisfied
7. Check the model still looks correct from a normal viewing distance

**Skill 4: Export as Optimized GLB (30 minutes)**
File → Export → glTF 2.0 (.glb/.gltf)

Export settings to always use:
- Format: glTF Binary (.glb)
- Include: Selected Objects
- Geometry: Apply Modifiers checked
- Compression: Draco Geometry Compression checked (this halves file size again)

Then run through gltf-transform CLI for final optimization:
```bash
npx gltf-transform optimize input.glb output.glb --compress draco
```

**Bonus: Setting Origin Point (30 minutes)**
The origin point is the pivot/center of a 3D object — the point it rotates around.
For a jet model, you want the origin at the geometric center, not a corner.

Object → Set Origin → Origin to Geometry

This ensures the model rotates correctly in Three.js.

**Resources:**
- Blender Guru's Beginner Tutorial (YouTube) — the donut. Do Part 1 only (the interface).
  You don't need to finish the donut series — just learn the interface.
- Blender official manual (docs.blender.org) — use as reference
- "Decimate modifier Blender tutorial" — just YouTube search this specifically
- "Export GLB from Blender for Three.js" — YouTube search this specifically

---

### Phase 7: Asset Creation with AI Tools
**Duration: 1 week | Daily: 1 hour of experimentation**

This is the most hands-on phase — you're learning by generating, reviewing,
and iterating with each tool.

**Midjourney v8 — Cinematic Photography**

Getting started:
1. Join Midjourney Discord or use Midjourney.com web interface
2. Start with: `/imagine [description]`

Prompting for web assets:
```
cinematic wide shot, [subject], [lighting description], [mood],
shot on [camera type], professional photography, high resolution,
dark atmospheric --ar 16:9 --v 7
```

Aspect ratios for web:
- `--ar 16:9` — landscape hero
- `--ar 4:3` — section images
- `--ar 1:1` — square cards
- `--ar 9:16` — mobile hero

Midjourney style parameters:
- `--style raw` — more photographic, less AI-stylized
- `--q 2` — higher quality (slower)
- `--s 0` — low stylization (accurate to prompt)
- `--s 750` — high stylization (Midjourney's artistic interpretation)

**Flux 2 Pro — Precise Compositions**

Access via: fal.ai, Replicate, or Leonardo AI (all have Flux available)
Best for: when you need exact framing and Midjourney keeps interpreting differently.

**Recraft v3 — SVG Icons and Illustrations**

recraft.ai — generate icons, illustrations, UI assets as actual SVG.
Prompt: "minimal line icon, [subject], consistent stroke weight, single color"
Generate 6–8 icons at once for visual consistency across a set.

**Runway Gen-4 — Video for Image Sequences**

runwayml.com
Generate 10-second cinematic clips, then extract frames.

Prompting for image sequence source footage:
- Be specific about camera movement: "slow push-in", "gentle orbit left", "static shot"
- Be specific about speed: "very slow", "smooth continuous motion"
- Avoid: faces, text, hands (AI video is weakest here)
- Best subjects: environments, objects, architectural elements, abstract visuals

Post-generation:
```bash
# Extract 24fps frames as WebP
ffmpeg -i generated_clip.mp4 -vf fps=24 -q:v 85 frames/frame_%04d.webp

# If frames are JPG first, batch convert to WebP
for f in frames/*.jpg; do cwebp -q 80 "$f" -o "${f%.jpg}.webp"; done
```

**Meshy 6 — AI 3D Generation**

meshy.ai — free tier gives 200 credits/month.

Text-to-3D prompt structure:
```
[object name], [material description], [style: realistic/stylized/low-poly],
[detail level: highly detailed/clean/minimal], web-optimized, PBR materials
```

Image-to-3D: upload a photo or Midjourney render → get a 3D model.
Often more accurate than text-to-3D for specific objects.

After generation:
1. Download as .fbx or .glb
2. Open in Blender (Meshy Blender plugin makes this one click)
3. Run Decimate modifier
4. Fix any obvious geometry issues
5. Export as optimized .glb
6. Run gltf-transform

**Adobe Firefly — Commercially Safe Images**

firefly.adobe.com — use when commercial licensing matters.
Images are generated from licensed content — safe for client commercial use.
Integrates directly into Photoshop for retouching.

---

### Phase 8: Webflow
**Duration: 3–4 weeks | Start after Phase 4 (GSAP)**

**Why Learn Webflow**

Webflow unlocks a completely different category of client work:
marketing sites, business websites, portfolios for clients who need
a CMS. You can deliver these faster than code and charge professionally.
Many freelancers bill $3k–$10k for Webflow sites.

**Core Webflow Concepts**

The Designer:
- The Webflow Designer is a visual CSS editor. Every interaction in the panel
  corresponds to a real CSS property. Knowing CSS makes Webflow feel logical,
  not like a mystery box.
- Box Model: margin, padding, width, height work exactly as in CSS
- Flexbox and Grid: Webflow's layout tools mirror CSS Flexbox and Grid
- Position: static, relative, absolute, fixed, sticky — same as CSS

Webflow Interactions:
Webflow's animation system. Visual timeline for element animations triggered by:
- Page load (entrance animations)
- Scroll position (parallax, reveal on enter)
- Mouse position (hover effects, cursor tracking)
- Click (toggles, reveals, tabs)

What Webflow Interactions can replicate:
- GSAP trigger-on-enter patterns (elements entering viewport)
- Basic parallax (different scroll speeds)
- Staggered entrance animations
- Hover state transitions

What it cannot replicate:
- Complex GSAP timelines with precise timing control
- Scroll scrub (animation directly tied to scroll progress, not triggered)
- Canvas image sequences
- 3D anything

CMS (Content Management System):
- Collections: database-like content types (Blog Posts, Projects, Products)
- Dynamic pages: auto-generated from CMS items
- Client editors can add/edit content without touching the designer

Webflow + Custom Code:
You can embed `<script>` tags in Webflow. This is how you add:
- GSAP for scroll animations beyond what Interactions support
- Custom JavaScript for interactive features
- Three.js embed (via iframe or script embed)

This hybrid approach — Webflow for structure + custom code for advanced effects
— is how many agencies add immersive elements to Webflow projects.

**Resources:**
- Webflow University (university.webflow.com) — free, made by Webflow, comprehensive
  Complete: Web design 101, Flexbox, Grid, Interactions
- Flux Academy (YouTube) — high-quality Webflow tutorials
- Timothy Ricks (YouTube) — advanced Webflow interactions
- Finsweet (finsweet.com) — free Webflow libraries for advanced features

**Practice:**
Build a 4-page Webflow site: Home, About, Work (CMS-powered portfolio), Contact.
Add scroll entrance animations on all sections using Interactions.
Add a CMS collection for portfolio items.

---

### Phase 9: Framer
**Duration: 2–3 weeks | After Webflow**

**Why Learn Framer**

Framer is where design and code meet most naturally. It's the best tool
for personal portfolios and design-heavy marketing pages. The built-in
animation system is excellent, the output is fast and clean, and publishing
is one click.

**Core Framer Concepts**

Canvas:
- Framer's design surface looks like Figma. Same concepts: frames, components, auto-layout.
- The key difference: everything you design can also be animated and published.

Animations:
- Smart animations: Framer automatically animates between component variants.
  Design a button in Default and Hover variants, Framer generates the transition.
- Scroll effects: visual interface for parallax, opacity, and transform changes tied to scroll.
- Transitions: page transitions with predefined and custom motion.

Code Components:
The killer feature. Inside any Framer project:
```tsx
// This is a real React component inside Framer
export function AnimatedCounter({ value }: { value: number }) {
  const [count, setCount] = useState(0);
  // ... React code works here
  return <div>{count}</div>
}
```

This means: use Framer's visual tools for layout and design,
drop in React + GSAP code components for anything requiring advanced animation.
You get the best of both worlds.

CMS:
Similar to Webflow CMS — dynamic content collections for blogs, portfolios.

**Resources:**
- Framer's official tutorials (framer.com/learn)
- Framer University (YouTube) — official channel
- Sam Shrimpton (YouTube) — advanced Framer techniques
- Framer Templates — study how premium templates are structured

**Practice:**
Rebuild your personal portfolio in Framer. Add a code component
that does a GSAP text reveal animation on the hero heading.

---

### Phase 10: The Modern AI Workflow — Full System Setup
**Duration: 1 week | After Phase 5 (R3F)**

This is where everything comes together. Set up your personal Claude Code
system from the setup guide. Practice the full workflow:

1. Brief → Claude research
2. Figma design → Figma MCP → Claude implementation
3. Stitch design.md → Claude consistency
4. Asset generation (Midjourney, Runway, Meshy) → integration
5. Claude Code + Motion AI Kit → animation implementation
6. Browser MCP → live testing and iteration
7. GitHub → Vercel → deployment

**Practice:**
Build the jet website you described in the original conversation.
Use every phase of the AI workflow. This is your Phase 10 project.

---

### Phase 11: Advanced Techniques (Ongoing — No Time Limit)

These are learned as projects require them. Not prerequisites.

**Advanced GLSL Shaders**
- Book of Shaders (thebookofshaders.com) — the definitive free resource
- Patricio Gonzalez Vivo's interactive shader learning environment
- Understand: noise functions, domain warping, UV manipulation, SDF shapes
- Goal: be able to describe an effect precisely enough that Claude writes it correctly

**Advanced Particle Systems**
- GPU particles via shader materials
- Physics simulations (gravity, wind, turbulence)
- Particle morphing (one shape to another)
- Instanced mesh for 10,000+ objects with individual animation

**Physics in 3D**
- @react-three/rapier — Rapier physics engine for R3F
- Rigid bodies, colliders, constraints
- Used for: interactive product exploded views, physics-based interactions

**Advanced Scroll Patterns**
- Horizontal scroll sections inside vertical pages
- 3D camera paths (CatmullRomCurve3 in Three.js)
- Multi-layer parallax (5+ depth layers)
- Scroll-driven shader uniforms

**WebGL without Three.js — raw GLSL**
- OGL library (lightweight WebGL)
- Full-screen shader effects (background animation, cursor effects, transitions)
- Used for: texture distortion effects on images, full-screen noise backgrounds

**Performance at Scale**
- Web Workers for physics/particle computation
- OffscreenCanvas for moving WebGL off main thread
- LOD (Level of Detail) — swapping models based on distance/device
- Instanced mesh — rendering 10,000 identical objects in one draw call
- Texture atlases — combining multiple textures into one to reduce draw calls

---

## Part 4 — Project Roadmap

### Project 1 (End of Phase 4 — GSAP Month)
**A scroll-driven storytelling page. No 3D.**

Requirements:
- Smooth Lenis scroll
- Pinned section with scrub-based text reveal
- Image parallax (foreground/background at different speeds)
- SplitText headline animation
- Staggered card entrance
- Custom cursor

This tests your GSAP foundation without 3D complexity.

---

### Project 2 (End of Phase 5 — R3F Month)
**A 3D product showcase page.**

Requirements:
- Load a GLB model (use Meshy for a simple product)
- HDRI environment lighting
- Bloom postprocessing
- OrbitControls for drag-to-inspect
- Scroll-connected model rotation (scrub)
- HTML text panels synced to scroll position

This tests 3D integration and scroll connection.

---

### Project 3 (End of Phase 10 — Full AI Workflow)
**The jet website (or equivalent immersive brand experience).**

Requirements:
- Full design system (Stitch → design.md)
- Designed in Figma → implemented via Figma MCP
- Hero with entrance animation (SplitText, stagger)
- Canvas image sequence (video source from Runway)
- 3D model section (Meshy → Blender → R3F)
- Scroll-driven camera path around the model
- Post-processing (bloom, depth of field)
- Lottie animated icons (from LottieFiles)
- Page transitions (Framer Motion AnimatePresence)
- Deployed on Vercel

This is a portfolio-quality piece.

---

### Project 4 (Ongoing — Client-Level Work)
**A Webflow site for a real or hypothetical client.**

Requirements:
- 4+ pages
- CMS-powered portfolio or blog section
- Webflow Interactions for scroll animations
- Custom GSAP code embed for advanced effects
- Responsive (desktop + mobile)
- Client-editable content

---

## Part 5 — Traditional vs Modern Side-by-Side

| Phase | Traditional Method | Modern AI-Assisted |
|---|---|---|
| Research & mood board | Manual browser browsing, Pinterest | Claude + web search, curated output |
| Wireframing | Figma by hand | v0 by Vercel, Claude Code layout |
| Design system | Built manually in Figma | Google Stitch → design.md → Claude |
| Design-to-code | Developer reads Figma manually | Figma MCP → Claude Code reads live |
| Photography | Stock license or commission | Midjourney v8 / Flux 2 Pro |
| Video source | Commission or stock footage | Runway Gen-4 / Kling 3.0 |
| 3D models | Blender modeling (days) | Meshy 6 → Blender cleanup (hours) |
| Lottie animations | After Effects + Bodymovin | Rive.app / LottieFiles library |
| All animation code | Developer writes by hand | Claude Code + Motion AI Kit |
| All 3D code | Developer writes by hand | Claude Code |
| Testing | Manual browser testing | Browser MCP + manual device testing |
| Deployment | Manual server setup | Vercel auto-deploy from GitHub |

---

## Part 6 — Complete Tools Reference

### Design
| Tool | Purpose | Cost | When to Use |
|---|---|---|---|
| Figma | UI/UX design, components, prototyping | Free / $12 mo Pro | Primary design tool |
| Google Stitch | AI design system generation | Free | Generating design.md |
| Framer | Design + publish, portfolio sites | Free / $15 mo | Personal portfolio |
| Webflow | Multi-page sites with CMS | Free / $14 mo | Client sites needing CMS |
| v0 by Vercel | AI component generation | Free tier | Rapid UI prototyping |
| Coolors.co | Color palette generation | Free | Quick palette exploration |
| Fontshare | Free premium fonts | Free | Clash Display, General Sans |
| Google Fonts | Open-source fonts | Free | Body text fonts |
| Fontsource | npm-installable fonts | Free | Next.js font integration |

### Animation & Motion
| Tool | Purpose | Cost | When to Use |
|---|---|---|---|
| GSAP | Professional animation engine | Free (Club $99/yr for plugins) | All scroll + complex animation |
| Motion (Framer Motion) | React animation library | Free | Component-level animation |
| Motion AI Kit MCP | Correct Motion API for Claude | Motion+ subscription | Every R3F/Motion project |
| Lenis | Smooth scroll inertia | Free | Every project |
| Rive | Interactive animation design | Free tier | Animated UI components |
| LottieFiles | Lottie animation library | Free | Animated icons |

### 3D
| Tool | Purpose | Cost | When to Use |
|---|---|---|---|
| React Three Fiber | Three.js in React | Free | All 3D web projects |
| @react-three/drei | R3F helper library | Free | Every R3F project |
| @react-three/postprocessing | Visual effects | Free | Bloom, DoF, grade |
| Blender | 3D editing, optimization, export | Free | Asset cleanup and optimization |
| Spline | Browser-based 3D for web | Free tier | Quick 3D without Blender |
| Meshy 6 | AI text/image to 3D model | Free (200 credits/mo) | 3D asset generation |
| Tripo3D | Alternative AI 3D generator | Free tier | Second option for 3D gen |
| gltf-transform | CLI 3D model optimization | Free | Compressing every .glb |
| Poly Haven | Free HDRI, PBR textures, models | Free | Environment lighting |
| Sketchfab | 3D model marketplace | Free tier | Pre-made models |

### AI Asset Generation
| Tool | Purpose | Cost | When to Use |
|---|---|---|---|
| Midjourney v8 | Artistic/cinematic photography | $10–30/mo | Hero images, atmosphere |
| Flux 2 Pro | Exact-composition image gen | Pay-per-use | Precise product shots |
| Adobe Firefly | Commercially safe image gen | CC subscription | Client commercial work |
| Recraft v3 | SVG vectors, icons, illustrations | Free / $10 mo Pro | Icon sets, SVG illustrations |
| Runway Gen-4 | AI video generation | $15 mo Standard | Source footage for image sequences |
| Kling 3.0 | Multi-shot AI video | Free tier | Longer, multi-angle sequences |

### Development
| Tool | Purpose | Cost | When to Use |
|---|---|---|---|
| Next.js | React framework | Free | All code-based projects |
| Tailwind CSS v4 | Utility CSS | Free | Styling |
| TypeScript | Typed JavaScript | Free | Always |
| Claude Code | AI development agent | Claude subscription | All development |
| pnpm | Package manager | Free | Faster than npm |
| VS Code | Code editor | Free | Primary editor |

### Infrastructure
| Tool | Purpose | Cost | When to Use |
|---|---|---|---|
| GitHub | Version control | Free | Every project |
| Vercel | Hosting + CI/CD | Free tier | All Next.js deployments |
| Cloudflare | CDN, DNS, optimization | Free tier | Domain and CDN |
| FFmpeg | Video frame extraction | Free | Image sequence creation |
| Squoosh CLI | Batch image optimization | Free | Converting frames to WebP |

### MCPs for Claude Code
| MCP | What it gives Claude | Setup |
|---|---|---|
| Figma MCP | Live read/write access to Figma files | figma.com/developers/mcp |
| Puppeteer MCP | Opens browser, screenshots, tests | npx @modelcontextprotocol/server-puppeteer |
| GitHub MCP | Commits, branches, PRs | npx @modelcontextprotocol/server-github |
| Motion AI Kit | Correct Motion animation API + 400 examples | motion.dev/plus |

---

## Part 7 — Monthly Schedule

### Month 1: Design Eye + CSS + Figma
Week 1–2: Design fundamentals (Refactoring UI, daily Awwwards analysis)
Week 3–4: Advanced CSS (Kevin Powell) + Tailwind CSS

Daily Awwwards habit starts now and never stops.

### Month 2: GSAP
Week 1–2: Core GSAP (CodePen experiments, no frameworks)
Week 3–4: ScrollTrigger (5 scroll projects)

### Month 3: Next.js + First Project
Week 1: Next.js App Router
Week 2: GSAP in React (useGSAP, Lenis integration)
Week 3–4: Build Project 1 (scroll storytelling, no 3D)

### Month 4: Three.js / R3F
Week 1–2: Core R3F concepts (geometry, materials, lighting)
Week 3: Loading models, drei library
Week 4: Post-processing, scroll-driven 3D

### Month 5: R3F Advanced + Blender + Second Project
Week 1: Shaders intro + particles
Week 2: Blender (the 4 skills)
Week 3–4: Build Project 2 (3D product showcase)

### Month 6: AI Workflow + Asset Tools + Third Project
Week 1: Midjourney, Flux, Recraft, Runway, Meshy — hands-on experimentation
Week 2: Full Claude Code system setup (CLAUDE.md, design.md, MCPs)
Week 3–4: Build Project 3 (the jet site / full immersive experience)

### Month 7: Webflow
Complete Webflow University core tracks.
Build a client-ready 4-page site.

### Month 8: Framer + Portfolio
Build personal portfolio in Framer.
Complete Project 4 (Webflow client site).
Start showing work publicly.

### Month 9+: Advanced + Real Projects
Advanced shaders, particles, physics as needed by actual projects.
Build for real clients or create portfolio pieces for public attention.

---

## Part 8 — The Non-Technical Skills That Determine Your Ceiling

The technical stack is learnable. These are what separate the people
who build impressive things from those who build technically correct but
visually forgettable things.

**Taste / Aesthetic Judgment**
You develop this through consumption. Awwwards daily. Dribbble daily.
Following the right designers on Twitter/X. Analyzing what makes something
feel premium vs generic. This is never finished — it's an ongoing practice.
Read: *The Design of Everyday Things*, *The Elements of Typographic Style*.

**Storytelling**
High-end websites tell a story. The sequence of sections, the reveal of information,
the emotional arc from hero to CTA — this is narrative structure applied to web.
Study film and editorial design for how stories are paced.

**Animation Intuition**
Knowing whether an animation feels right. This comes from watching hundreds of
examples and building hundreds of experiments. The GSAP CodePen collection
and Awwwards sites are your training data. Watch animation on every device,
in every context. Start noticing: does this feel fast? Slow? Springy? Mechanical?

**Communicating With Claude Effectively**
Your ability to get good output from Claude Code is a skill.
The clearer your brief — specific easing values, specific reference sites,
specific scroll behavior descriptions — the better the output.
Vague: "add a cool animation." Specific: "add a GSAP entrance animation,
fade-up pattern, 600ms, power3.out easing, stagger 80ms between items,
triggered when the section top hits 80% of the viewport."

---

## The One Thing

If you could only take one thing from this guide:

**Start GSAP in week one. Build something every single day, no matter how small.**
Everything else in this guide depends on that foundation, and every day
you delay it is a day you're not compounding that skill.

The rest follows. The domain is big, but it's not deeper than you can reach.
You already think in systems, you already build with AI, you already know React.
The specific tools are the easy part. The hard part is consistent daily practice
until the concepts become intuition — and that only comes from building things,
not from reading about building things.

---

*Last updated: June 2026*
*Stack versions: Next.js 15, Tailwind v4, GSAP 3.12, R3F 8.x, Three.js r167*
