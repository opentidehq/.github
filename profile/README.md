<p align="center">
  <img src="https://raw.githubusercontent.com/OpenTideHQ/.github/main/assets/svg/logo-normal.svg" alt="opentide" width="280">
</p>

<p align="center">
  <strong>Open Threat-Informed Detection Engineering</strong>
</p>

OpenTide is the DetectionOps engine for detection-as-code — validate, generate, deploy, and document rules across seven security platforms.

```bash
pip install opentide
opentide setup
opentide validate --strict
```

Docs, blog, and specs: **[opentide.org](https://opentide.org)**

| Repo | Role |
|------|------|
| [opentide](https://github.com/OpenTideHQ/opentide) | Engine — CLI, MCP, SDK (PyPI) |
| [specifications](https://github.com/OpenTideHQ/specifications) | Normative object specs and vocabularies |
| [library](https://github.com/OpenTideHQ/library) | Public registry of published detection objects |
| [explorer](https://github.com/OpenTideHQ/explorer) | Deployable app to explore objects end to end |
| [skills](https://github.com/OpenTideHQ/skills) | Canonical agent skills for detection engineering |
| [website](https://github.com/OpenTideHQ/website) | Site and docs ([opentide.org](https://opentide.org)) |

`opentide setup` scaffolds a detection repository, CI (GitHub, GitLab, Azure DevOps), MCP, and skills. You do not start from an InitTide template.

If you still have a pinned CoreTide submodule, it keeps resolving. New work goes on the package. Migration: [opentide.org/docs/usage/migration/](https://opentide.org/docs/usage/migration/).

Brand assets (logo, icon, badges): [`assets/`](assets/).

All OpenTide projects are licensed under the [European Union Public Licence (EUPL) 1.2](https://eupl.eu/1.2/en/).
