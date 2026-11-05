# AGENTS.md — Rules for Sophie Zhang's personal site

These are the rules I follow when working on this site. The source of truth for content is `Sophie Zhang PM Resume.pdf`.

## Never publish
- Home address, phone number, or any other street-level or personal contact detail from the CV.
- Anything marked confidential. The CV mentions a "confidential AI client" at Gensler; that client stays unnamed.
- Credentials, API keys, tokens, or private files from this folder (cover letters, job list spreadsheet, other resume versions, `Summer 2027 Roles.html`).
- Invented facts: no made-up metrics, titles, dates, employers, testimonials, or links.
- Nothing is pushed to GitHub, deployed, or shared via a public URL unless Sophie says so in that moment. Earlier approval does not carry over to later pushes.

## Ask first
- Before any `git push`, deploy, publish, or commit.
- Before adding contact details (including email) to a page that will be public.
- Before changing the wording, numbers, or order of CV content. Fixing an obvious typo is fine, but I will mention it.
- Before adding new sections, photos, third-party scripts, analytics, or contact forms.
- Before deleting or overwriting any existing file.
- When a CV number looks questionable (for example, a percentage over 100%). I flag it instead of silently changing it.

## Style
- **Vibe:** professional and casual. Warm and confident, with no jargon walls and no stiff corporate tone.
- **Colors:** off-white background (`#F7F3EC`), black text (`#151515`), burgundy accent (`#6D1A2B`). No other accent colors.
- **Navigation:** streamlined. One sticky bar with a handful of section links, in the same order as the CV: Education, Experience, Projects, Skills.
- **Layout:** tiles for experience and projects so sections are easy to scan. Mobile-friendly.
- **Content:** same section order as the CV. Keep Sophie's wording; trim nothing that matters.
- **Code:** a single static `index.html` with inline CSS and no frameworks or external dependencies. It is accessible: semantic HTML, sufficient contrast, visible focus states.
- **Writing in chat:** short and direct. I list every file I create at the end of each task.
