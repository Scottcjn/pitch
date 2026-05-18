# Contributing to pitch

Thanks for improving the Elyan Labs pitch deck. This repository is a static
Reveal.js-style HTML deck with speaker notes, so changes should keep the deck
easy to review in a browser and consistent with the notes.

## Setup

1. Fork the repository and create a branch:

   ```sh
   git checkout -b fix/short-description
   ```

2. Open `index.html` directly in a browser, or serve the directory locally:

   ```sh
   python -m http.server 8000
   ```

3. Review `SPEAKER_NOTES.md` alongside any slide changes so the spoken pitch
   stays aligned with the visual deck.

## Pull Request Guidelines

- Keep copy, layout, and data updates focused and easy to review.
- Explain which slide or speaker-note section changed.
- Include the browser and viewport size used for visual review.
- Update `SPEAKER_NOTES.md` whenever slide claims, sequencing, or timing change.
- Do not commit screenshots, local server logs, or generated export files unless
  they are explicitly requested.

## Code Style

- Keep the deck self-contained unless a dependency is already used.
- Preserve readable HTML structure for each slide section.
- Use concise copy that fits the existing slide layout.
- Keep financial, market, and traction numbers consistent across slides and
  speaker notes.
- Avoid layout changes that make the deck harder to present on standard
  projector or laptop aspect ratios.

## Validation Checklist

- [ ] `index.html` opens without console errors in a current browser.
- [ ] Changed slides were checked at presentation size and a narrow viewport.
- [ ] `SPEAKER_NOTES.md` matches the slide content.
- [ ] Links and external assets still load where network access is required.
- [ ] No generated exports or local-only files are included.
