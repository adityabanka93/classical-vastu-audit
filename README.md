# Classical Vāstuśāstra Audit — AI Skill

**A source-first, open-source skill for questioning Vastu claims using classical Sanskrit architectural literature.**

[Read the skill](SKILL.md) · [Classical source register](references/sources.md) · [Audit worksheet](references/plan-audit-template.md) · [Worked claim review](examples/consultant-claim-review.md)

> **Research preview (v0.1):** This is an AI **instruction skill**—not a fully trained Vastu model, a geometry engine, an accredited architectural assessment, or proof that traditional predictions cause real-life outcomes.

## Why this exists

Vastu advice often mixes ancient writings with recent rules, costly products and claims about unnamed "energy" instruments. This skill makes an assistant ask: **Which text? Which edition and verse? Which exact location? What can actually be measured?**

## What it does

- Uses *Bṛhat Saṃhitā*, *Mānasāra* and (after passage verification) *Mayamata(m)* as textual points of reference.
- Identifies entrance and layout **claims** with source, context and uncertainty.
- Avoids conflating the 9×9 and 8×8 grids or other doorway division systems.
- Distinguishes ancient textual prescriptions from modern treatment sales pitches and independently demonstrable building issues.
- Produces auditable tables rather than declaring someone’s house fortunate or cursed.

## Get started

Download or clone this repository. Use `SKILL.md` as the instruction file in an AI assistant that supports agent skills, or attach the Markdown files to a chat. Include `references/sources.md` to retain edition and verification notes.

Example prompt:

> Use this Classical Vastu Audit skill to examine my redacted floor plan. The north arrow and measurements are included. Check the main doorway against *Bṛhat Saṃhitā* 53 and *Mānasāra* 38; identify exact editions/passages and explain whether the published diagrams permit a reliable location classification. Then evaluate a consultant's doorway-treatment claim separately.

## Important limitations

- Textual interpretation is **not** evidence that a spatial arrangement causes illness, prosperity or misfortune.
- A complete Sanskrit manuscript corpus is **not included**; linked translations should be cross-checked where wording matters.
- *Mayamatam* has been bibliographically identified, but its individual passages are **not yet verified here**.
- A door's exact deity-position cannot responsibly be inferred from a simple photo or from splitting any wall into eight equal pieces. Classical plan diagrams require careful reconstruction.
- Structural changes require qualified architects/engineers and compliance with local rules.
- This repository contains no user's address or floor plan and no commercial endorsements.

## Roadmap

- [ ] Validate Sanskrit passages and edition differences for key entrance verses.
- [ ] Reconstruct and independently check the 81-square and 64-square entrance layouts with source-linked diagrams.
- [ ] Add original-source-backed guidance for selected residential room configurations.
- [ ] Build voluntary, opt-in geometry input/testing using completely fictional example plans.
- [ ] Expand source coverage to other relevant architectural treatises.

## License

[MIT](LICENSE) for this repository's **original** documentation/instructions only. Linked primary works, editions, and translations retain their own copyright and licensing conditions.