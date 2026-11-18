# Visual DNA

**A library of visual design-language skills for AI-assisted interface creation.**

Visual DNA helps an AI understand and reproduce the *visual identity* of a software interface. It describes the design language behind an application—not the application's business logic or feature set.

## What belongs here?

A design language may describe:

- Overall visual identity, workspace composition and information hierarchy
- Window chrome, menus, toolbars, tabs, panels and status areas
- Typography, colour, spacing, borders, shadows and geometry
- Control appearance, interaction states and visual feedback
- Density, alignment, proportions and recurring visual patterns

For example, a Visual DNA skill could describe the visual language of a classic creative desktop application and guide an AI building an unrelated chat or media application.

## Repository structure

Each design language lives in its own folder:

```text
visual-dna/
├── README.md
├── index.html
└── <design-language>/
    └── SKILL.md
```

A skill should be self-contained, readable and reusable. Add supporting resources only when they materially improve the skill and are documented.

## Creating a new skill

1. Choose a specific software reference or visual system.
2. Confirm the product and version when those details materially affect the design.
3. Study the reference and identify its distinctive visual rules.
4. Create a folder for the design language.
5. Add a `SKILL.md` that explains the visual system clearly enough for an AI to apply it.

If the reference or version is ambiguous, resolve that ambiguity before writing the skill. Do not silently guess.

## Portability

The design philosophy should be described independently of any one implementation framework wherever possible. HTML/CSS, PyQt, Rust-based desktop shells and other frameworks may require different implementation techniques.

Do not claim that a skill works identically across frameworks unless each implementation has been tested. Keep framework-specific guidance separate and label its validation status honestly.

## What this project is not

- Not a component framework or UI widget library.
- Not a collection of application features or product requirements.
- Not a source-code generator.
- Not a promise that one implementation technique transfers unchanged to every framework.

## Relationship to BuildCollective

- **Visual DNA** supplies visual direction.
- **BuildSeeds** supplies software concepts and requirements.
- **InterfaceFoundry** supplies working interface references.

The repositories are independent and can be used separately or combined.

## Contributing

Contributions should be based on clearly identified references, distinguish observation from interpretation, and avoid including assets or material that the contributor does not have permission to redistribute. See the repository licence and any third-party notices.

## Licence

This project is intended for public-domain-style reuse under **CC0 1.0 Universal**, subject to the licence file and any separate rights or notices attached to third-party material.
