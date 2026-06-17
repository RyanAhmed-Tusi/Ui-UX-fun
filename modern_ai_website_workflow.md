# The Modern AI-Assisted High-End Website Workflow
### Every Phase, Every Concept — Traditional vs. Modern, What's Automated, What Stays Manual

---

## How to Read This Guide

Each phase shows:
- **What changed** from the traditional workflow
- **What's automated** and which AI tool does it
- **What stays manual** and why (creative judgment, quality gates)
- **The exact modern tool** replacing or augmenting the old one

---

## Phase 1 — Discovery & Strategy

### Traditional
Manual research, mood boarding in Pinterest, competitor analysis in a browser, IA drawn in FigJam by hand.

### Modern

**What's automated:**
Claude handles competitive research entirely. Give it your project brief and it web-searches competitor sites, analyzes patterns, identifies design trends in your niche, and produces a structured analysis document. What took a half-day of manual browsing takes 15 minutes of conversation.

**Mood boarding** is still partly visual and creative — you still need to find images that capture the feeling you want. But Claude can web-search reference sites, pull aesthetic directions, and help you articulate a visual direction in words that becomes a design prompt.

**Information architecture** — Claude generates a full sitemap and user flow diagram from a project description. You review and adjust, but the skeleton is built instantly.

**What stays manual:**
The creative vision itself. What story does the site tell? What emotion should a visitor feel? These remain human decisions. Claude assists, researches, and structures — but the directional choice is yours.

**Tools replacing the old:**
| Old | New |
|---|---|
| Manual browser research | Claude Code + web search |
| Pinterest mood boarding | Claude + web search + manual curation |
| Miro/FigJam IA diagrams | Claude generates IA as markdown/text, you refine in FigJam |

---

## Phase 2 — UX Design: Wireframes & Prototypes

### Traditional
Days of manual wireframing in Figma. Low-fi to high-fi, multiple iterations.

### Modern

**What's automated:**
**v0 by Vercel** — you describe a UI section in plain language ("a hero section with a large headline, two CTAs, and a background that has a subtle grain texture") and v0 generates a production-ready React + Tailwind component with clean markup. Not a wireframe — actual code. You paste it into your project.

**Claude Code** — given a text description of a layout or a rough sketch described in words, Claude Code generates a full HTML/React page structure. It's faster than Figma for structural decisions.

**For prototyping interactions:** Describe the behavior you want ("when you hover a card, it should lift and reveal a second line of text") and Claude writes the code. The prototype is the working product.

**What stays manual:**
The actual UX decisions — what content goes on which page, what the navigation structure is, what the user journey looks like, where friction points are. These require thinking about your user and your content. Claude can suggest, but you decide.

**Tools:**
| Old | New |
|---|---|
| Figma wireframes | v0 for rapid component generation / Claude Code for full pages |
| ProtoPie prototypes | Working code directly — the prototype IS the site |
| Weeks of iteration | Days |

---

## Phase 3 — Visual / UI Design

### Traditional
Full design system built manually in Figma. Every color, type scale, spacing token, and component designed by hand. Then a developer reads the Figma and manually translates it to code.

### Modern

**What's automated — the revolutionary part:**

**Google Stitch** — describe your design intent in plain language ("luxury aviation brand, dark background, gold accents, editorial feel, geometric sans-serif type") and Stitch generates a complete design system with color palette, typography scale, spacing, and component variants — exported as a `design.md` file.

The `design.md` file is plain markdown containing all your design tokens — colors as hex values, type roles with font names, sizes, and weights, spacing scale, shadow definitions. It is designed specifically to be consumed by AI coding agents. You hand this file to Claude Code and it has everything it needs to generate UI that matches your design without you spelling out specs in every prompt. Every component Claude generates across every session pulls from the same tokens — a button and a card built two weeks apart look like they came from the same designer.

**Figma MCP (bidirectional sync):**
Once your Figma design is connected via the Figma MCP server, Claude Code gets structured access to your file — not a screenshot, actual component data: component hierarchy, design tokens, layout constraints, auto-layout properties. Claude Code reads your Figma and implements it in code. You update the design in Figma, Claude Code rewrites the code to match. Bidirectional — Claude can also write code that pushes component proposals back to the Figma canvas.

**What stays manual:**
The art direction itself — choosing the font that fits the brand personality, deciding whether the aesthetic is dark and editorial or light and minimalist, establishing the visual identity. Stitch generates the system; you provide the direction. You still need to know what you want before Stitch can execute it.

For high-end work, a real designer still makes Figma decisions. The workflow is: designer makes creative choices in Figma, Figma MCP bridges those choices to Claude Code automatically.

**Tools:**
| Old | New |
|---|---|
| Manual design system in Figma | Google Stitch → design.md |
| Developer reads Figma manually | Figma MCP → Claude Code reads live |
| Design-to-code translation (days) | Figma MCP implementation (hours) |

---

## Phase 4 — Motion Design Planning

### Traditional
Motion designer writes an animation spec in a Google Doc. Easing values are guesses. Developer manually implements, guesses wrong, iterates endlessly.

### Modern

**What's automated:**

**Motion.dev AI Kit MCP** — this connects to Claude Code and gives it the full, current Motion library documentation plus 400+ real animation examples queryable by the LLM. The historical problem: Claude's training data has outdated API knowledge. It imports from "framer-motion" instead of "motion/react". It guesses easing curves that feel wrong. With the AI Kit connected:
- Claude always uses correct, current import paths
- Easing curves are selected from real, named, professional examples
- Animation patterns (staggered entrance, scroll-linked parallax, spring physics) are implemented correctly on the first try
- MotionScore audits your animation code for performance problems

**What stays manual:**
Deciding *what* should animate. The creative motion design brief — "the headline should feel like it's being revealed behind a curtain" or "the 3D model should feel like it's breathing" — is still a human creative choice. Claude executes the brief; you write the brief.

---

## Phase 5 — Asset Creation (The Modern AI Pipeline Per Type)

This is where the biggest changes have happened. Every asset type now has an AI-assisted creation path.

---

### 5.1 Photography & Hero Images

**Traditional:** Commission a photographer ($500–$5000) or license from stock sites ($50–$500 per image).

**Modern:**

**Midjourney v8** — the artistic quality leader in 2026. Produces photorealistic, cinematic imagery with exceptional lighting, composition, and atmosphere. Best for: hero backgrounds, atmospheric textures, lifestyle imagery, concept art. $10–$30/month subscription. Unlimited generations.

**Flux 2 Pro** — open-source champion. Strongest prompt adherence of any model — it follows detailed instructions faithfully. Best for: precise product shots, specific compositions where you need exact framing, situations where you keep re-generating to get a specific result. Flux gets there in fewer tries.

**Adobe Firefly** — commercially safe (trained on licensed content). Best for: client work where IP licensing matters, brand imagery, anything going into commercial campaigns.

**The professional strategy:** Many professionals use two generators — Midjourney for hero visuals where artistic quality is the priority, Flux 2 Pro for everyday content where accuracy to spec matters more.

**Recraft v3** — specializes in design-ready assets: icons, illustrations, SVG vectors. Generates consistent visual styles across multiple assets — a settings icon and a user profile icon in the same style with consistent line weights and proportions. SVG output that scales perfectly and can be styled with CSS.

**What stays manual:** Art direction. Knowing what prompt to write. Selecting the best output from 4–8 generated options. Iterating the prompt to get from 70% to 100%. Final retouching in Photoshop or Figma.

---

### 5.2 SVG & Vector Illustrations

**Traditional:** Illustrator or Figma, drawn by hand. Hours per illustration.

**Modern:**

**Claude directly** — for geometric SVG elements, decorative patterns, UI illustration components, Claude writes SVG code directly. No image generation needed. Ask for "a minimalist SVG illustration of a jet in flight, wireframe style, 400×300" and Claude writes the SVG markup. Clean, scalable, immediately usable.

**Recraft v3** — for stylized illustrations, icon sets, and brand graphics where you want an AI-generated image output as actual SVG (not rasterized PNG). Produces editable vector output.

**What stays manual:** Brand-defining custom illustrations that require a specific artistic style. For generic or geometric illustration needs, Claude or Recraft covers it.

---

### 5.3 Video (For Image Sequences & Background Video)

**Traditional:** Commission a video production company ($2000–$20000) or source stock footage (Artgrid, Envato).

**Modern — the biggest unlock for scroll storytelling:**

**Runway Gen-4** — the professional standard. Gen-4.5 currently sits at the top of the Artificial Analysis Text-to-Video benchmark. For professional video production, advertising, and commercial content, Runway Gen-4 is the most reliable choice — the consistency and control are unmatched. Best for: cinematic sequences, product visualizations, atmospheric motion clips. You generate the video in Runway, then run FFmpeg to extract frames for your image sequence.

**Kling 3.0** — the dark horse that keeps getting better. Version 3.0 introduced multi-shot sequences with subject consistency across different camera angles — a genuine technical breakthrough. Best for: longer sequences, multi-angle product shots.

**The image sequence pipeline with AI video:**
```
You describe: "A slow zoom toward a commercial jet window from 
outside, cinematic, dusk lighting, clouds in background"
       ↓
Runway Gen-4 generates a 10-second clip (~$2–5 in credits)
       ↓
ffmpeg -i generated_clip.mp4 -vf fps=24 frames/frame_%04d.jpg
       ↓
Convert to WebP: squoosh-cli batch convert
       ↓
Claude Code builds the canvas + ScrollTrigger implementation
```

What used to require sourcing or commissioning custom video footage now costs $2–5 and 10 minutes.

**What stays manual:** The creative direction of the shot, reviewing the output, regenerating if needed. AI video is not frame-perfect on the first try — budget for 3–5 iterations to get the right clip.

---

### 5.4 Lottie Animations

**Traditional:** Motion designer in After Effects, hours per animation, Bodymovin export.

**Modern:**

**Rive.app** — still the best tool for interactive animations. It is both a design tool (browser-based, no After Effects needed) and a runtime. You design animation states visually, set up state machines, and export to web. The learning curve is lower than After Effects. For non-interactive Lottie: LottieFiles has a browser-based editor with AI-assist for simpler animations.

**Claude for simple Lottie JSON** — for very simple animations (a loading spinner, a checkmark animation, an icon morph), Claude can write Lottie JSON directly. Lottie format is documented and Claude understands it. This covers maybe 30% of use cases where simplicity is acceptable.

**What stays manual:** Complex character animations, highly crafted motion graphic sequences, brand animations requiring specific personality — these still need a skilled motion designer in After Effects or Rive. The AI tools speed up the simple cases; complex cases still need a human.

---

### 5.5 3D Models

**Traditional:** Blender, hours to days per model. High skill floor.

**Modern:**

**Meshy 6 (January 2026)** is now the go-to AI 3D generation tool. Meshy-6 ships watertight outputs with cleaner topology, sharper hard-surface edges, and a new Low Poly Mode aimed at game-ready output. The workflow that works: get 80% of the way there in Meshy in a minute, take the FBX into Blender for the last 20% — face cleanup, UV refinement.

Meshy supports text-to-3D, image-to-3D, retexturing, animation, and has official Blender, Unity, and Unreal plugins. Output formats include .fbx, .glb, .obj, .usdz.

**The honest pipeline for web-quality 3D:**

```
Step 1: Meshy AI
  Prompt: "Commercial jet aircraft, clean PBR surfaces,
  metallic fuselage, detailed engines, web-optimized"
  → Download .glb (the AI-generated base, ~80% quality)

Step 2: Blender (20 minutes of cleanup)
  - Fix any broken geometry with Merge by Distance
  - Reduce polygon count with Decimate modifier (target: under 100K tris)
  - Check UV maps for texture alignment
  - Set correct origin point (center of mass, not a corner)
  → Export as .glb

Step 3: gltf-transform optimize (CLI, 30 seconds)
  gltf-transform optimize jet.glb jet_optimized.glb --draco
  → File size drops 70-90% with Draco compression

Step 4: Claude Code integrates it into R3F
  → Writes all scene setup, lighting, scroll animation, interaction code
```

**For hero 3D assets where quality is non-negotiable:** The AI generates the base, a human does the finishing. For secondary or atmospheric 3D elements (background props, decorative geometry), AI generation alone is often sufficient.

**Spline for web-native 3D:** If your 3D doesn't need Blender-level detail and you want visual control without code, Spline (spline.design) is a browser-based 3D tool. Design scenes visually, add hover/click interactions, export a React component. `@splinetool/react-spline` turns a Spline scene into a React component that Claude Code wraps with scroll logic, layout, and UI.

**What stays manual:** High-fidelity hero models where every polygon matters. Technical 3D (rigged characters, animated assemblies with moving parts). Custom ultra-detailed models that are the centrepiece of the experience. Budget for Blender cleanup time on any hero asset.

---

### 5.6 Textures & PBR Materials

**Traditional:** Substance Painter (expensive, complex), or manual UV mapping in Blender.

**Modern:**

**Meshy's AI Texturing** — Meshy can retexture a 3D model from a text prompt. "Brushed aluminum fuselage with scratches, matte cockpit window frames" → generates PBR texture maps (albedo, roughness, metalness, normal) applied to your model.

**Poly Haven** (polyhaven.com) — still the best source for free CC0 PBR materials, HDRI environment maps, and textures. Nothing has replaced this for HDRI lighting specifically. Always start here for environment lighting.

**What stays manual:** Custom branded textures, photorealistic materials for hero close-up shots, and any texture where the AI result doesn't meet quality bar.

---

### 5.7 Fonts

**No AI automation here — and that's correct.** Font selection is a branding decision. Free high-quality sources:
- Fontshare (fontshare.com) — Clash Display, General Sans, Switzer, Satoshi
- Google Fonts — reliable, huge selection
- Fontsource — npm-installable fonts for Next.js

Self-host fonts as .woff2 for performance. Never link to Google Fonts CDN in production — it blocks rendering.

---

## Phase 6 — Animation & Interaction (Modern Implementation)

This is 100% Claude Code territory. Every animation technique from the previous guide is implemented by Claude. The key enablers:

**GSAP + ScrollTrigger** — Claude writes all of this. Provide the animation brief (what moves, when, what easing) and Claude produces production-quality GSAP code.

**Motion.dev (Framer Motion) + AI Kit MCP** — Claude writes all component animations with correct current API. The AI Kit MCP eliminates hallucinated props and wrong import paths.

**Three.js / React Three Fiber** — Claude handles full scene setup, model loading, lighting, post-processing, and scroll connection.

**Canvas Image Sequences** — Claude writes the preloading strategy, canvas rendering loop, and ScrollTrigger scrub connection.

**Shaders (GLSL)** — Claude writes vertex and fragment shaders for custom visual effects. Provide a description of the effect you want.

**The session pattern for each animation feature:**

```
1. Tell Claude the effect you want (reference a site or describe it clearly)
2. Confirm it has the design.md (design system context)
3. Claude writes the code
4. Review in browser (Browser MCP or manual)
5. Iterate: "The easing feels mechanical, make it springier"
         "The stagger is too fast, slow it down to 150ms between items"
6. Claude adjusts
```

This loop replaces weeks of developer iteration with hours.

---

## Phase 7 — Development

**Traditional:** A developer reads the Figma, hand-codes every component, every page, every animation — 3–8 weeks.

**Modern:** Claude Code is the developer. Your role is creative direction and review.

**The modern development session pattern:**

```
Morning: Define what you're building today (1 section or 1 feature)
         Give Claude the context (design.md, CLAUDE.md, relevant files)
         Claude builds it
         
Midday:  Review in browser, note what's wrong
         Describe corrections in plain language
         Claude iterates
         
Evening: Review final version, approve or note final changes
         Claude commits via GitHub MCP
```

One person can build in a week what used to take a team three weeks.

**What stays manual:** Reviewing Claude's output. Catching UI bugs. Deciding when something looks "right." Testing on real devices. Writing the creative brief clearly enough that Claude builds the right thing.

---

## Phase 8 — Performance & Testing

**What's automated:**
Browser MCP lets Claude open your site, take screenshots, and audit. You can ask Claude to run Lighthouse and implement the suggested fixes.

For 3D performance: Claude knows to apply Draco compression, lazy loading, LOD (level of detail), and texture compression. Tell it your performance target and it builds toward it.

**What stays manual:** Testing on real mobile devices. Checking on lower-powered hardware. Final review of Core Web Vitals in real-world conditions.

---

## Phase 9 — Deployment

**Semi-automated — the good news is it's already very easy.**

Vercel deployment from GitHub is effectively one-time setup then automatic:
1. Connect your GitHub repo to Vercel (one-time, 5 minutes)
2. Every push to `main` auto-deploys to production
3. Every other branch gets a preview URL automatically

Custom domain, SSL, CDN — all automatic on Vercel.

Claude Code can set up the GitHub Actions CI/CD pipeline, write the Vercel config, and handle environment variables. You just need to push to GitHub.

---

## The Modern Tools Map

### Asset Creation
| Asset Type | Best AI Tool | Quality Note |
|---|---|---|
| Hero photography | Midjourney v8 | Artistic/cinematic excellence |
| Exact-spec images | Flux 2 Pro | Best prompt adherence |
| Commercially safe | Adobe Firefly | IP-licensed training data |
| SVG / vector | Recraft v3 | Clean SVG output |
| Video (image seq source) | Runway Gen-4 | Professional standard |
| Multi-shot video | Kling 3.0 | Subject consistency across angles |
| 3D base mesh | Meshy 6 | 80% quality, needs Blender finish |
| 3D texturing | Meshy AI Texture | PBR maps from text prompt |
| Lottie / interactive anim | Rive.app | Browser-based, state machines |
| Environment lighting | Poly Haven | Still the best free HDRI source |

### Design & Code
| Task | Tool |
|---|---|
| Design system generation | Google Stitch |
| UI component generation | v0 by Vercel |
| Design-to-code bridge | Figma MCP |
| All animation code | Claude Code + Motion AI Kit |
| All Three.js / R3F code | Claude Code |
| All GSAP code | Claude Code |
| Full site development | Claude Code |

### The Non-Negotiables (Still Manual)
- Art direction and creative vision
- Font selection and type pairing
- Reviewing and quality-gating all AI outputs
- Final design decisions in Figma
- Real device testing
- Deployment approval

---

## Quality Rule

Never ship an AI asset without reviewing it and asking: "Does this meet the quality bar of what I'm trying to build?" AI tools speed up creation. Human judgment ensures quality. The workflow is: AI creates, human curates, Claude Code integrates.
