---
description: "Project-specific Copilot guidance for the breatheco-de exercise-postcard repository: a beginner HTML/CSS postcard exercise."
---

# Repository guidance

This repository is a beginner-level HTML/CSS exercise named **Postcard**.

- Primary work happens in `index.html`.
- The goal is to build a static postcard layout using HTML5 structure and CSS3 styling.
- There is no JavaScript application, no build system, and no package manager required.
- `.learn/` contains lesson assets and should generally not be modified unless explicitly requested.

# What to focus on

- Use semantic HTML elements where appropriate.
- Use CSS selectors, box model rules, layout containers, and basic typography.
- Prefer a simple, static solution rather than adding frameworks or dependencies.
- If styling is added, use either an inline `<style>` block or a linked CSS file from `index.html`.

# What not to do

- Do not add npm/yarn configuration files, build scripts, or dependency installations.
- Do not change repository metadata (`learn.json`) unless the user explicitly asks for it.
- Avoid any server-side code or advanced tooling for this exercise.

# Behavior for Copilot

- When asked to fix or improve the postcard, change only the HTML/CSS needed to meet the exercise requirements.
- When asked about running the project, explain that this is a static HTML page and can be previewed in a browser.
- When giving suggestions, keep them beginner-friendly and aligned with the exercise fundamentals.

# Example prompts

- "Help me build the postcard layout in `index.html`."
- "Fix the CSS so the postcard content is centered and readable."
- "Suggest a Google Font import and use it in the postcard design."
