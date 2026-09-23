# WarisWorks GitHub Profile

## Purpose and audience
Personal GitHub profile for Waris Ruzi, a designer and developer in Japan. Introduces his work in AI products, multilingual UX, and cultural technology to collaborators and visitors.

## Core features
- Custom orbital banner and signature artwork.
- Concise introduction, four selected products, toolkit, working principles, and contact links.
- Uyghur-first product focus grounded in the existing profile.

## Stack and architecture
GitHub Flavored Markdown and GitHub-supported HTML in `README.md`; self-contained SVGs in `assets/`. No application runtime, package dependencies, or build step.

## Technical decisions and constraints
- Keep artwork in the repository; avoid externally generated badges or statistics images.
- SVG animation is decorative; respect `prefers-reduced-motion` and retain a complete static composition.
- Provide meaningful image alt text and keep essential information in ordinary README text.
- Use native Markdown and HTML rather than scripts, embedded apps, or custom page CSS.
- Preserve verified profile facts and existing product/contact destinations. Do not invent metrics, employment, or achievements.

## Deployment
The default branch is `main`. GitHub displays its README on `https://github.com/WarisWorks` because the public repository matches the account name. Relative asset URLs resolve from this repository. Changes are reversible through Git history.
