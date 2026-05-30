# Design System Document: Digital Ephemera Editorial

## 1. Overview & Creative North Star
**Creative North Star: The Living Archive**

This design system is an intentional rejection of the "modern web" gloss. It treats the digital interface as a piece of high-end, temporal ephemera—an archival document that feels both ancient and futuristic. We move beyond "brutalism" into a space of **Refined Documentarianism**.

The system breaks the "template" look through intentional asymmetry: imagine a researcher’s desk where papers are slightly offset. We use extreme typographic scales and 1-bit dithering to create a high-contrast, tactile experience that feels printed rather than rendered. Every element must feel "stamped" onto the `surface` with 100% ink-black intent.

---

## 2. Colors & Surface Logic
The palette is rooted in the physical reality of newsprint and early computing terminals.

### The Palette
*   **Background (`#f9f9f7`):** The primary paper stock. All experiences begin here.
*   **Primary (`#000000`):** The "Ink." Used for all definitive strokes, text, and 1-bit art.
*   **Secondary/Tertiary (`#5e5e5e` / `#3b3b3b`):** Mid-tones used exclusively for dithered patterns and secondary metadata.

### The "Single-Stroke" Rule
Contrary to modern trends of "no-line" design, this system **demands the line**. However, it must be used with editorial precision.
- Prohibit "soft" sectioning. Do not use shadows or gradients to define blocks.
- Boundaries are defined by a **1px solid `primary` (#000000) stroke**.
- To create depth, use **Internal Offsets**: Instead of a shadow, offset a container by 2px down and 2px right using a `primary` background to create a "hard shadow" block effect.

### Surface Hierarchy
Nesting is achieved through tonal "Paper Stacking":
1.  **Level 0:** `surface` (#f9f9f7) - The base sheet.
2.  **Level 1:** `surface_container_low` (#f4f4f2) - A slightly "aged" paper feel for sidebars.
3.  **Level 2:** `surface_container_highest` (#e2e3e1) - Used for high-contrast "archival" blocks.

---

## 3. Typography
Typography is the core of this system's personality. We use a "Technical-Editorial" pairing.

*   **Display & Headlines (`spaceGrotesk` / Pixelated Fallback):** These are the "Lead Plates." They should be used at `display-lg` (3.5rem) to create an unapologetic, loud hierarchy. In high-end implementations, headers should be set in **All-Caps** with a `letter-spacing` of `-0.05em`.
*   **Body & Titles (`inter` / Monospaced Fallback):** While the tokens suggest Inter, for this system, we treat it as a **Technical Sans**. Use `body-md` for standard reading, but always pair it with `label-sm` monospaced tags for metadata (e.g., "DATE_CREATED", "REF_ID") to maintain the archival feel.

---

## 4. Elevation & Depth: The "Hard-Edge" Principle
We reject the concept of "Z-axis" light sources. In this system, depth is **Physical Stacking**.

*   **The Layering Principle:** Stack containers using the Spacing Scale (e.g., `spacing-4` padding) and enclose them in `1px solid primary` borders.
*   **The "Dithered" Shadow:** If a "lift" is required, do not use an ambient shadow. Use a 1-bit dithered pattern (a checkerboard of pixels) or a solid `secondary_fixed` (#c6c6c6) block offset behind the card.
*   **No Glassmorphism:** We do not use blurs. Information is either present or hidden. Use solid fills to maintain the "bare-bones HTML" integrity.

---

## 5. Components

### Buttons
*   **Primary:** Solid `primary` (#000000) background with `on_primary` (#e2e2e2) text. Square corners (`0px`).
*   **State Change:** On hover, invert the colors (Background: `#f9f9f7`, Text: `#000000`). The transition must be **instant (0ms)** or a **stepped refresh (200ms at 2 frames)**.

### Input Fields
*   **Visual:** A simple `1px` bottom border or full box.
*   **Labeling:** Use `label-sm` (Monospace) positioned outside the box, top-left.
*   **Error State:** Use `error` (#ba1a1a) for the border and a `1-bit` dithered warning icon.

### Cards & Lists
*   **Forbid Dividers:** Do not use `outline_variant` for dividers between list items. Instead, use vertical white space (from the Spacing Scale, specifically `spacing-4`) and `primary` bullet points (2x2 pixel blocks).
*   **Asymmetric Cards:** Experiment with cards that don't align to a 12-column grid. Let a card take up 7.5 columns to create visual tension.

### Signature Component: The "Cellular Canvas"
Every page should feature a `surface_container_low` area where a **Game of Life** simulation runs at a low frame rate (4fps). This acts as a "living" background texture that reinforces the ephemera theme.

---

## 6. Do's and Don'ts

### Do:
*   **Embrace the Pixel:** Use dithered images (Bit-depth reduction) for all photography. It should look like a fax or a 1990s digital camera.
*   **Use Intentional Asymmetry:** If you have two columns, make one `spacing-24` wide and the other `spacing-8`.
*   **Stepped Animation:** All transitions (opacity, movement) should feel like a slow mechanical refresh. Use `steps(4)` in your CSS easing.

### Don't:
*   **No Border Radii:** Never use `rounded`. The world is square (`0px`).
*   **No Gradients:** We use solid colors or dithering. Smooth transitions suggest a "luxury" that this system intentionally avoids in favor of "utility."
*   **No Icons with Curves:** If using icons, use pixel-aligned, 1-bit SVG icons. If it has a curve, it’s wrong.
