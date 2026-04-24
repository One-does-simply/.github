# One Does Simply (ODS)

**A family of spec-driven app frameworks.** A *builder* writes a JSON
spec describing their app; a *framework* renders it as a fully
functional application with persistence, auth, and a polished UI.

The philosophy: *complexity is the framework's job, simplicity is the
builder's experience.*

## Families

Each family is a self-contained monorepo: the specification, its
renderers, the AI build helpers that author it, and the conformance
scenarios that pin behavior across implementations.

| Status      | Family                                                           | What it describes                                                                                      |
| ----------- | ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| ✅ Active    | [**ODS Pages**](https://github.com/One-does-simply/ods-pages)    | Data-driven apps — forms, lists, charts, dashboards. Two production renderers: Flutter + React.       |
| 🔜 Planned  | **ODS Chat**                                                     | Chat and voice-driven apps built as conversational agents; shares data with ODS Pages apps.           |
| 🔜 Planned  | **ODS Workflow**                                                 | Orchestration between spec-driven apps, plus simple automations.                                       |
| 🔜 Planned  | **ODS Game**                                                     | Vibe-code games in minutes — education-focused, teaches software development + vibe-coding practices. |

## Start here

The first family to ship is **ODS Pages**. It has a React renderer
(PocketBase backend) and a Flutter renderer (local SQLite) that
render the same spec. Head to
[github.com/One-does-simply/ods-pages](https://github.com/One-does-simply/ods-pages)
— or read the marketing pitch at
[one-does-simply.github.io/ods-pages/Specification/](https://one-does-simply.github.io/ods-pages/Specification/).

## Philosophy

- **Specs over code.** If behavior can be described declaratively in
  JSON, it should be.
- **Multiple renderers per family.** One spec, many targets (web,
  mobile, desktop).
- **Atomic cross-framework commits.** When the spec changes, all
  renderers update together.
- **No silent breaking changes.** Conformance scenarios pin
  cross-framework behavior; renderers that disagree fail loudly.

## Status

Pre-1.0. Spec and framework APIs are still evolving across all
families. Interested? Star a repo; the ODS Pages README has a
roadmap and contribution pointers.

## License

MIT across all ODS families. Each repo includes its own `LICENSE` for
clarity.
