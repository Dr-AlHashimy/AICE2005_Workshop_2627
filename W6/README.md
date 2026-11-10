# W6

## Instructions

1. **Apply MoSCoW to your requirements specification** — take every functional (FR) and non-functional (NFR) requirement from your W2 tables and assign each one a MoSCoW priority. Use [`_template/moscow-requirements-template.md`](_template/moscow-requirements-template.md).
2. **Justify each priority** in one line — tie it back to a persona, a stakeholder or a use case (e.g. *"Must — Persona 1 can't capture notes without it"*). A priority with no reason is a guess.
3. **Check the balance** — if almost everything is a *Must*, you haven't prioritised. Aim for roughly **no more than 60% Must**, and make sure you have at least one **Won't (this time)** so your scope is explicit.
4. **Update your specification** — your *Must* requirements are your minimum viable app: these are what you'll build first when you start vibe-coding, and what your test plan from W4 must cover.
5. Bring your prioritised requirements table to the next session for discussion.

## MoSCoW for requirements

| Priority | Meaning for a requirement | Ask yourself |
| --- | --- | --- |
| **Must have** | The app fails without it — not usable, not safe, or not legal. | *"If we ship without this, is the app pointless?"* |
| **Should have** | Important and expected, but there's a workaround if it's missing. | *"Painful to leave out, but the app still works?"* |
| **Could have** | Desirable; improves the experience but nobody is blocked without it. | *"Nice if time allows?"* |
| **Won't have (this time)** | Agreed to be out of scope for this release — recorded, not forgotten. | *"Are we deliberately saying not now?"* |

- Guide: https://www.agilebusiness.org/dsdm-project-framework/moscow-prioritisation.html

> In W4 you used MoSCoW (or T-shirt sizing) on your **implementation tasks**. This week you apply it to the **requirements themselves** — deciding *what* the app must do, before deciding *how much work* it is.

## `_template/` — MoSCoW requirements template

- `_template/moscow-requirements-template.md` — your FR and NFR tables with Priority and Justification columns added.
