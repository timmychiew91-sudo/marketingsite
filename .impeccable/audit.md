# Homepage technical audit

Target: `index.html` · 16 September 2026 · Persuade mode

| Dimension | Score | Evidence |
| --- | ---: | --- |
| Accessibility | 3/4 | Semantic landmarks and one H1, labelled mobile menu, visible focus, reduced motion support. No full screen-reader session was run. |
| Performance | 4/4 | Static page, no framework or remote runtime dependency; fonts are local and there are no content images to load. |
| Responsive design | 4/4 | Browser emulation at 1440px and 390px showed no horizontal overflow. Visible mobile links and buttons were checked at 44px or more in each dimension. |
| Theming | 3/4 | Main colours and type use documented tokens; several one-off tonal values remain in CSS for the dark panel and diagram. |
| Implementation integrity | 3/4 | The page reflects the confirmed service brief without invented results. The mechanical detector reported many design-token advisories and a few small-text/border warnings; the material small-text and spacing issues were corrected in source. |
| **Total** | **17/20** | **Good** |

## Findings and follow-up

- **P2 — Design tokens:** Impeccable's detector listed 25 colour and 48 font-size advisories because the documented token scale is narrower than the actual CSS. The palette and typography are visually coherent, but the formal token record should be updated as the system grows. `DESIGN.md` is the source for that follow-up.
- **P2 — Browsers and assistive technology:** The site was inspected in headless Chrome at desktop and phone widths. Safari, VoiceOver, and a physical touch device were not exercised in this pass.
- **P2 — Metadata:** A canonical URL, social image, and sitemap wait for a confirmed domain.

## Positive checks

- Local fonts, CSS, JavaScript, and favicon load successfully.
- All in-page navigation targets resolve.
- The mobile menu opens and closes; its state label updates.
- The email link uses the owner-provided address and a prefilled brief outline.
- Sampled body/accent colour pairs meet 4.5:1 contrast; large display accents also exceed 3:1.

The raw Impeccable detector output for this pass was captured outside the repository at `/tmp/timmy-final-detect.json`. The review screenshots are under `.impeccable/review/` and are intentionally ignored by Git.
