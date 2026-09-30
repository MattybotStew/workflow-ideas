# Astra + Elementor Process Playbook — speaker notes

Twenty slides, five phases. The sibling deck (`gerotech-process-playbook.html`) teaches the same
discipline on a build where we own the design system; this one teaches it where we don't.

**The worked example is anonymised throughout.** A fifteen-page non-profit site built on a fixed
theme and page builder. Structure, counts and mechanisms are real. The client, the town, the phone
number and the palette are not, and shouldn't be said aloud if the deck is shown outside the team.

- **← / →** navigate (also Prev/Next, space, or swipe)
- **N** toggles these notes
- **P** prints — each slide on its own landscape page
- Deep-link any slide with `#slide-12`

---

## The one-line thesis

> We don't own the design system on a page-builder build — we rent one. The starter decides how it
> looks. Everything else is a question of whether the idea already exists inside it.

If someone remembers one slide, it should be **03 — Who decides what**.

---

## Per slide

| # | Slide | Say this |
|---|---|---|
| 01 | Title | Open in 45s. Name the inversion immediately — same agency, opposite constraint. |
| 02 | The premise | "A layout you want doesn't exist in the starter, so we drop the idea." That one sentence settles most arguments. |
| 03 | **Who decides what** | **Linger here.** Three lanes: the starter decides, the wire decides, the build inherits. Everything after is a consequence. |
| 04 | The five phases | It's a pipeline, not a loop. Show the canvas row — the file's own structure states which artefact is provisional. |
| 05 | Theme and starter | The sequencing claim: starter **before** sitemap. The reverse is how you get 15 pages and a template that expresses 8. |
| 06 | Why this starter | Read the four rejections aloud. They're the answer to every future "why can't we just…". |
| 07 | Six layouts, 15 pages | The arithmetic is the point. Nothing on the list is built from a blank canvas. |
| 08 | Sitemap, in code | Page-vs-section is the most expensive thing to reverse. Build the sitemap as a real page, not a diagram. |
| 09 | The inventory | Three marks carry the weight: parent, scope cut, merged. Each prevents a later conversation. |
| 10 | Lock what's expensive | The unusual item is the last: tell the build what it **can't** do. |
| 11 | Wireframes, in code | "Looks greyed out" is a feature. Plain HTML is the enforcement of "not the product". |
| 12 | **Not the product** | Say it at kickoff, in those words. The ⚠/✅ convention and the Bin are the team agreeing before anyone policed it. |
| 13 | Placeholders | Pushback is guaranteed: "let's write the real paragraphs." Unapproved copy is a liability, not a saving. |
| 14 | Design follows content | Direction is **opposite** the bespoke deck. Also: agree the frame width up front — 1920 wires vs 1440 designs cost real work. |
| 15 | The ladder | Free / call / never. The never rung is short and absolute — that's where a fixed build becomes unbounded. |
| 16 | Expect the homepage | The uncomfortable slide, and the most useful one. Repeated homepage rounds = the process working. |
| 17 | What the build inherits | Three columns, three owners. The middle one leaks into the left — that's how a design system quietly forks. |
| 18 | Build order | Globals before pages, pages before forms. Step 3 (create every page empty) is the one people skip. |
| 19 | **What it cost** | **Show this.** Friction is what makes the method credible. The footer is the sharpest item. |
| 20 | Reusable either way | Close on the transfer, not the tool. What survives a different build target? |

---

## Likely questions

**"Why not just build it bespoke in code?"**
Sometimes you should — the sibling deck covers that. Choose a page builder when the client needs to
edit their own content and the design is a variation on a template rather than a new idea. If the
design is genuinely bespoke, a page builder will fight you the whole way.

**"What if the client insists on a layout the starter doesn't have?"**
That's a scope conversation, not a build conversation. It means custom CSS, or a different starter,
or a bespoke build. Name the cost of each; let the client choose with the trade-off visible.

**"Isn't a wireframe in code just reinventing design in the wrong tool?"**
It'd be, if the wire were the product. It's a disposable decision surface — plain HTML, no framework,
nothing to port. It exists so content and structure can be reviewed in a browser instead of in a
diagram that costs an afternoon to rearrange.

**"What did this actually cost?"**
Honest answer: the accent colour took three passes, a left-align lost to a generic centred rule, a
child theme got created for a real accessibility need, a paid addon got installed, and three
documents drifted apart. None of those are reasons not to use the template — they're the reason to
write the rules down first.

---

## Terms to avoid out loud

- **Don't say** "the template" when you mean a specific product. "The starter" or "the theme" is
  precise enough for a slide.
- **Don't say** "Elementor" as if it were the process. The process works on any page builder; the
  tool is incidental.
- **Don't say** "wireframe prototype" without saying it's disposable. That's the whole point of it.
- **Don't** name the worked-example client, its town, or its phone number. The deck is anonymised;
  keep it that way out loud.
- **Don't** describe the palette as the client's. The deck shows CloudMellow's own tokens.
