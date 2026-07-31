# Design workspace

Use `inspiration/` for local visual references. This folder is ignored by Git so reference images are not committed accidentally.

Use `directions/` for palette studies and generated mockups that are appropriate to keep with the project.

Production-ready images, video, fonts, and other site assets belong in `src/assets/`, not in this workspace.

## Reference notes

Add one row for each image placed in `inspiration/`. Source URLs marked as missing need to be supplied by the project owner.

| Filename | Source URL | What I like | What not to copy |
| --- | --- | --- | --- |
| `_110357667_c40b0a37-125e-479f-97b9-81475215f700.jpg` | [The Verge](https://www.theverge.com/2017/9/24/16345612/syd-mead-art-design-book-blade-runner) | **Composition:** one large engineered object anchors the foreground while small figures establish scale; the scene stays legible despite environmental detail. **Typography:** functional destination lettering is integrated into the machine. **Color temperature:** cool cyan-green atmosphere with a concentrated yellow headlamp and cabin glow. **Texture:** painted, weathered, wet, and mechanical. **Density and mood:** cinematic urban infrastructure that feels used, plausible, and quietly mysterious. | Do not reproduce the vehicle silhouette, checker pattern, destination wording, background architecture, figures, symbols, or the image’s exact framing. Do not imitate identifiable film-production design or artwork line-for-line. |
| `cjVCUo6fTLaCZTOPHHa8_A.jpg` | [Ohio State DESIS Lab](https://desis.osu.edu/seniorthesis/index.php/2021/09/07/syd-meads-impact-on-design-and-the-future/) | **Composition:** a strong diagonal vehicle leads into layered architecture and enormous distant structures; people make the scale human. **Typography:** little visible type, allowing form and color blocking to carry hierarchy. **Color temperature:** warm coral-orange machinery against pale lavender, cream, and atmospheric sky tones. **Texture:** clean illustrated surfaces balanced by planted areas and expansive light. **Density and mood:** optimistic, civic, spacious retro-futurism rather than dystopia. | Do not copy the orange vehicle, uniforms, tower shapes, elevated structures, landscape arrangement, or exact palette placement. Avoid reproducing the illustration’s distinctive architecture or composition. |
| `images-1.jpg` | [BBC News](https://www.bbc.com/news/entertainment-arts-50955699) | **Composition:** a single rugged service vehicle dominates a low, frontal three-quarter view; the background recedes into fog and industrial shadow. **Typography:** utilitarian labels and markings feel operational rather than decorative. **Color temperature:** cold blue-gray environment with restrained yellow, red, and blue machine accents. **Texture:** hand-rendered metal, grime, reflections, exposed equipment, and wet pavement. **Density and mood:** technical, workmanlike, resilient, and grounded. | Do not copy the vehicle body, equipment arrangement, markings, lettering, wheel configuration, industrial setting, or exact camera angle. Avoid turning LaserSETI equipment into a fictional vehicle or prop. |
| `images.jpg` | [Instagram](https://www.instagram.com/p/DP_ytQ7k7dT/) | **Composition:** a paired reference contrasting an isolated machine portrait with a crowded street-level scene; both use foreground machinery to organize human activity. **Typography:** illuminated signs and transit lettering become environmental wayfinding. **Color temperature:** blue night and gray weather offset by amber, yellow, and neon warmth. **Texture:** rain, reflective pavement, haze, fabric, painted metal, and luminous signage. **Density and mood:** lived-in, multicultural, nocturnal, and cinematic, with technology embedded in everyday life. | Do not copy the taxis, costumes, characters, neon lettering, recognizable film imagery, logos, street composition, or exact lighting setup. Do not reproduce the collage format unless independently justified by LaserSETI content. |

## Shared signal

Across the four references, the strongest common qualities are believable engineered objects, human scale, atmospheric depth, weathered materials, and a cool environment interrupted by warm operational light. The references support an optimistic-but-serious technical mood when their cinematic language is translated into LaserSETI’s real instruments and observatories rather than copied literally.

## Approved homepage direction

**Direction:** Signal Horizon  
**Selected mock:** `design/directions/02-direction.png`  
**Status:** Approved for implementation handoff

### Composition

- A thin, full-width navigation rail establishes a precise technical frame without competing with the hero.
- The headline spans most of the viewport as one dominant horizontal event.
- A spectral signal line separates the headline from the supporting copy and actions.
- The introductory paragraph and action group share a compact horizontal band beneath the headline.
- A wide photographic horizon crosses the lower hero, interrupted by one controlled vertical equipment detail.
- The visible second fold resolves into a spacious two-column system rather than repeating the hero composition.
- The desktop mock uses a `1536 × 1024` frame. Implementation must preserve its scale relationships while adapting responsively rather than scaling the screenshot literally.

### Hierarchy

1. LaserSETI identity and primary navigation
2. “All the Sky, All the Time”
3. Short project explanation
4. “Help LaserSETI” primary action
5. “Follow on Facebook” secondary action
6. Real instrument and observatory imagery
7. “LaserSETI Instrument” and “Observatory Network” second-fold entry points

The Help action must remain unmistakably primary. The second fold should feel discoverable but quieter than the hero.

### Imagery

- Use the real LaserSETI station photographs already stored in `src/assets/site/`.
- Preserve the equipment, environment, and photographic truth; do not invent or materially alter machinery.
- Treat the first image as a broad landscape/horizon crop and the second as a narrower equipment detail.
- Image crops may change responsively, but the wide-plus-vertical relationship should survive at desktop scale.
- Any additional production imagery must depict real LaserSETI instruments, observatories, or work.

### Typography

- Display character: **Rajdhani SemiBold** for the large headline, compact navigation emphasis, and technical section labels.
- Body character: **Atkinson Hyperlegible** for explanatory copy, links, and readable supporting text.
- The headline should remain condensed, uppercase, and dominant without becoming decorative display art.
- Body copy must remain comfortably readable for both general audiences and scientists.

### Locked palette

- Background — deep nocturnal navy: `#07131F`
- Primary — technical cyan: `#25C7D9`
- Accent — optimistic coral: `#FF6B57`
- Support — operational yellow: `#FFD166`
- Signal — electric blue: `#3568FF`

Coral identifies the primary action and the word “Sky.” Cyan carries structure, headings, and measurement language. Yellow and blue are supporting operational signals, not competing accents.

### Distinctive details

- A thin horizontal spectral trace acts as the homepage’s signature divider.
- Fine calibration ticks, rule lines, and precise rectangular seams provide the field-equipment character.
- Dark matte surfaces should feel clean and engineered rather than glossy or glass-like.
- Controlled image overlaps provide depth without floating-card styling.
- The interface should feel nocturnal and technical while remaining optimistic and welcoming.

### Inspiration, not literal specification

- Do not rasterize or trace the mock’s text, navigation, buttons, rules, or spectral line; implement them as semantic HTML and scalable CSS/SVG.
- The exact crop boundaries, line lengths, tick spacing, and pixel positions are compositional guidance, not fixed measurements.
- The mock’s generated rendering of the LaserSETI wordmark is not a replacement logo; use the real project asset.
- Do not reproduce any accidental image-generation distortions, altered equipment details, invented labels, or implied specifications.
- Do not hard-code the desktop arrangement for smaller screens. Preserve hierarchy and relationships through responsive recomposition.
- The mock is a north star for topology, density, and mood; it is not a background image or a screenshot to reproduce pixel-for-pixel.

### Implementation boundary

This approval authorizes Signal Horizon as the later implementation target. It does not authorize site edits until a separate implementation request is given.
