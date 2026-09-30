# Workflow ideas

CloudMellow process playbooks. Two decks on the same discipline from opposite ends: one where we own
the design system, one where a template owns it for us.

Both are self-contained HTML — no build step, no dependencies. Open either in a browser.

## The decks

| Deck | Slides | What it teaches |
|---|---|---|
| [`astra-elementor-process.html`](astra-elementor-process.html) | 20 | Running a design engagement on a **fixed theme and page builder**. The starter is imported first and decides how the site looks; the sitemap and wireframes are built in plain code to map it; the design is brought up to the content; the build inherits the constraints. |
| [`gerotech-process-playbook.html`](gerotech-process-playbook.html) | 21 | The bespoke counterpart — **we own the design system**. Wireframes, design and the build are all made in code and presented in Figma, so a content change takes minutes. Seven phases, discovery to hand-off. |

Start at [`index.html`](index.html).

## Reading a deck

- **← / →** navigate (also Prev/Next, space, or swipe)
- **N** toggles speaker notes
- **P** prints — each slide on its own landscape page, so "Save as PDF" gives a handout
- Deep-link any slide with `#slide-7`

The Astra/Elementor deck also has a full [speaker-notes file](astra-elementor-notes.md) with
per-slide talking points, likely Q&A, and the worked example's anonymisation rules.

## The shared idea

The two decks look different but run the same loop: **agree the structure and the constraints early,
while changing them is still free.** On the page-builder build that means the starter comes before
the sitemap. On the bespoke build it means the wireframes are code, so a content change is an edit
rather than a rebuild.

Both end the same way — a build team that inherits written-down decisions, not a folder of assets.

## Anonymisation

`astra-elementor-process.html` and its notes are **anonymised**. The worked example is a real
fifteen-page non-profit rebuild, and the structure, page counts and mechanisms are accurate — but the
client name, location, contact details and brand palette have been removed, and the deck shows
CloudMellow's own design tokens. Keep it that way if the deck is shown outside the team.

The Gerotech deck names its own worked example and is not anonymised.

## Files

| File | What it is |
|---|---|
| `index.html` | Landing page linking both decks |
| `astra-elementor-process.html` | The 20-slide fixed-template playbook |
| `astra-elementor-notes.md` | Speaker notes for the fixed-template deck |
| `gerotech-process-playbook.html` | The 21-slide bespoke playbook |
| `speaker-notes.md` | Speaker notes for the bespoke deck |
| `images/` | Screenshots and one-pagers used by the bespoke deck |
