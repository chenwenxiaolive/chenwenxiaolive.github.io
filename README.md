# Wenxiao Chen's personal website

A static English resume and research profile, published through the existing GitHub Pages workflow. The visual reference is the [Claude articles index](https://claude.com/resources/articles) and its article pages: warm paper, dark text, large serif headings, generous margins, subtle borders, and restrained editorial illustrations.

## Content record

`profile.json` preserves the resume facts, source notes, and editorial preferences. Update the record before changing the corresponding page content. The owner confirmed **Huawei, July 2022–May 2026**, followed by **IQuestLab, June 2026–present**. Do not infer an IQuestLab job title. The IQuest-Q1 credit remains the single sentence “I made IQuest-Q1.” with its official link.

Scholar totals and all six featured paper citation counts were checked on October 23, 2026. Keep the verification date attached to the statistics. Other career facts and project outcomes come from the owner's existing resume.

All public page copy, navigation, accessible labels, dates, and contribution titles are in English. Preserve original-language source facts in `profile.json` and keep their English presentation alongside them. Translated award and project names are descriptive translations, not newly verified official names. Do not turn project performance gains into broader system-level claims.

## Page structure

1. An editorial introduction, current affiliation, portrait, and the exact IQuest-Q1 credit.
2. Selected work, with original vector covers and concrete project outcomes.
3. Employment and education in chronological order, newest first.
4. Research metrics and six selected publications.
5. Community roles and an expandable list of contribution links.
6. Honors and a direct email contact.

The full content is present in HTML without JavaScript. Native anchors and disclosure elements provide navigation and optional detail. Small screens use a single column; print styles produce a compact resume and omit decorative covers and the contribution appendix. Respect reduced-motion preferences and provide visible keyboard focus. Use freely available fonts with system fallbacks; retain this site's own identity and artwork.

## Development and review

Edit `index.html`, `style.css`, and `profile.json` in this checkout. There is no dependency installation or application build. Keep the existing GitHub Pages deployment workflow.

Publish committed snapshots and the human-readable career record through `/preview`. Check desktop and mobile layouts, keyboard navigation, disclosure behavior, local assets, print rendering, and consistency with `profile.json`. Browser tooling and verification artifacts belong outside the repository.
