# TARGET FOLDER: [REPLACE_WITH_SOFTWARE_NAME]

You are creating a reusable AI design skill for the software or visual design reference identified by the target folder name.

## Objective

Study the visual design language of the named software and create a comprehensive `SKILL.md` inside the target folder.

The purpose is to teach AI coding agents how to reproduce the software's visual appearance, interface structure, styling conventions and interaction presentation when designing entirely different applications.

**Important:** This is about visual design language, not recreating the software's original functionality.

For example, a messaging application can use Photoshop-inspired visual styling. The resulting skill should teach the AI to reproduce that visual language, regardless of whether the application being developed is a chat client, image editor, browser or something else.

## 1. Understand the design reference

Identify the software represented by the target folder name.

Study its characteristic visual language, including:

- Overall visual identity and aesthetic.
- Application window and title bar.
- Menu bars and dropdown menus.
- Toolbars and command strips.
- Tabs and document navigation.
- Panels, sidebars and inspectors.
- Buttons, inputs, dropdowns and controls.
- Borders, separators, shadows and gradients.
- Typography, font sizes and hierarchy.
- Icons and icon placement.
- Colour palettes and surface treatments.
- Spacing, alignment and information density.
- Hover, active, selected, disabled and focus states.
- Window layout and workspace organisation.

Consider the software's relevant versions and visual evolution where necessary. Do not mix substantially different design generations without explaining the distinction.

## 2. Create a reusable design skill

Create:

`[TARGET_FOLDER]/SKILL.md`

The skill must be sufficiently detailed for an AI coding agent to implement the visual style without needing to study the original software independently.

Include:

1. Design philosophy and visual identity.
2. Colour palette and semantic colour usage.
3. Typography and sizing conventions.
4. Window and application shell design.
5. Layout and workspace organisation.
6. Component styling.
7. Menus, tabs and toolbar conventions.
8. Panel and inspector design.
9. Interaction states and feedback.
10. Spacing, dimensions and geometry.
11. Icons and visual assets.
12. Common design mistakes to avoid.
13. Implementation and validation instructions.

## 3. Keep the skill framework-aware

The primary objective is describing the visual language in a reusable manner.

Do not assume that CSS instructions automatically translate to PyQt, Rust, Slint, Qt or other UI frameworks.

Where implementation guidance is included, distinguish between framework-independent visual principles and framework-specific implementation techniques.

Do not claim cross-framework compatibility unless it has actually been tested.

## 4. Quality requirements

- Be specific rather than using vague descriptions such as "modern and clean".
- Provide practical dimensions, colours and styling guidance wherever reasonably established.
- Explain why particular visual conventions exist.
- Distinguish essential characteristics from optional decorative details.
- Preserve the distinctive identity of the reference.
- Do not blindly copy proprietary assets, logos or copyrighted resources.
- Do not turn the design into a generic SaaS dashboard.
- Do not impose responsive web conventions on desktop interfaces unnecessarily.
- Do not invent features or visual characteristics without evidence.

## 5. Uncertainty and clarification

If the target software is ambiguous, has multiple substantially different interface generations, or the intended visual reference cannot be established confidently, ask me before creating the skill.

Do not guess and generate a potentially incorrect skill.

If there are minor uncertainties that do not prevent useful work, state reasonable assumptions and proceed.

## 6. Execution rules

- Work only inside the specified target folder.
- Inspect existing files before making changes.
- Preserve existing content unless modification is explicitly necessary.
- Do not create application code or a demo application.
- Do not create additional documentation files unless requested.
- Create or update only `SKILL.md`.
- Do not overwrite unrelated files.

## Final output

Report:
- The visual reference and version/generation used.
- The main design characteristics captured.
- The file created or updated.
- Any assumptions or unresolved limitations.

The result should be a reusable design skill, not a description or review of the original software.
