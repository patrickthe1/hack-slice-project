# Cursor Agent Rules for Portfolio Website Development

These rules ensure the Cursor agent (Claude 3.7 Sonnet) aligns with the competition’s constraints and replicates the reference screenshot’s design during vibe coding.

---

## Guidelines
1. **HTML and CSS Only**: Use only HTML5 and CSS3—no JavaScript, inline scripts, or external libraries.
2. **Replicate Screenshot**: Base all design choices (layout, colors, typography, animations) on `portfolio-screenshot.png` in `Roadmap.md`, adapting for About Me, Skills, and Interests.
3. **Follow Roadmap**: Adhere to the phases, steps, and success metrics in `Roadmap.md`—do not deviate unless instructed.
4. **Minimalistic Design**: Maintain a clean, sleek UI inspired by the screenshot—avoid clutter, use its color palette, and prioritize whitespace.
5. **CSS Animations**: Use smooth transitions and `@keyframes` to match the screenshot’s effects (e.g., fades, slides, hovers).
6. **Responsive Design**: Adapt the screenshot’s layout for mobile (max-width: 600px), tablet (max-width: 900px), and desktop.
7. **Semantic HTML**: Use tags like `<header>`, `<section>`, `<footer>` for structure.
8. **Update Project Context**: After each phase/feature, update `ProjectContext.md` with:
   - Status (e.g., "Completed")
   - Tasks completed
   - Issues or deviations
9. **Avoid Assumptions**: If a prompt or screenshot detail is unclear, ask for clarification—cross-reference `Roadmap.md` and `ProjectContext.md`.
10. **File Management**: Work in `index.html` and `styles.css` only; keep code organized with comments linking to the screenshot’s influence.

---

## Prompt Handling
- Treat prompts as instructions to advance per `Roadmap.md`, using the screenshot as the visual guide.
- If a prompt conflicts with the screenshot, prioritize the screenshot’s design unless explicitly overridden.
- Validate work against `Roadmap.md` success metrics before proceeding.