# Tumelo Phale

**Software Engineer**  
Cloud · Security · Reliability

I have professional experience across **C#/.NET backends and Angular/TypeScript frontends**. My work has included application features, validation and business rules, automated testing, defect investigation and delivery workflows. I am now building deeper capability in cloud systems, application security and service reliability.

[Portfolio](https://tumelodev-arch.github.io/) · [Projects](https://tumelodev-arch.github.io/work.html) · [LinkedIn](https://www.linkedin.com/in/tumelo-junior-phale-a6579527b/)

---

## What I work with

| Application engineering | Testing and delivery | Current learning |
| --- | --- | --- |
| C# / .NET / ASP.NET Core | Unit and negative-path testing | AWS service fundamentals |
| Angular / TypeScript / JavaScript | Regression and Cypress E2E | Service health and failure diagnosis |
| REST APIs / SQL / CQRS patterns | Git, pull requests and CI investigation | Application security and reliability |

## Selected projects

### 01 / [RuleTrace](https://github.com/tumelodev-arch/tumelodev-arch.github.io/tree/main/projects/RuleTrace)

A .NET validation API with deterministic rules and an independent browser example using invented records.

[Browser example](https://tumelodev-arch.github.io/projects/RuleTrace/demo.html) · [Architecture notes](https://github.com/tumelodev-arch/tumelodev-arch.github.io/blob/main/projects/RuleTrace/ARCHITECTURE.md)

The API runs locally. It is not hosted and has no authentication or persistence.

### 02 / [ReleaseLens](https://github.com/tumelodev-arch/tumelodev-arch.github.io/tree/main/projects/ReleaseLens)

A TypeScript dashboard for exploring synthetic build history, filtering runs, viewing derived metrics and exporting CSV.

[Open dashboard](https://tumelodev-arch.github.io/projects/ReleaseLens/index.html) · [Source files](https://github.com/tumelodev-arch/tumelodev-arch.github.io/tree/main/projects/ReleaseLens)

It does not connect to a live CI provider.

### 03 / [Randwise](https://github.com/tumelodev-arch/Randwise)

A local-first cash-flow planner with transaction editing, monthly summaries, category breakdowns and CSV export.

[Live demo](https://tumelodev-arch.github.io/Randwise/) · [Source and setup](https://github.com/tumelodev-arch/Randwise)

### 04 / [Incident Atlas](https://github.com/tumelodev-arch/IncidentAtlas)

A local incident review log with severity/state filters, response notes, resolution summaries and JSON export.

[Live demo](https://tumelodev-arch.github.io/IncidentAtlas/) · [Source and setup](https://github.com/tumelodev-arch/IncidentAtlas)

This is not a monitoring, alerting or paging platform.

### 05 / [Decision Archive](https://github.com/tumelodev-arch/DecisionArchive)

An Architecture Decision Record workspace with status, search, Markdown export and JSON backup/restore.

[Live demo](https://tumelodev-arch.github.io/DecisionArchive/) · [Source and setup](https://github.com/tumelodev-arch/DecisionArchive)

The three standalone browser applications store records in the current browser. They have no accounts, backend service or cloud sync. Use synthetic or non-sensitive data.

---

## Next investigation

**Cloud Service Router** is planned, not implemented. The goal is a small .NET service where request contracts, validation, health reporting, automated tests and failure behaviour can be inspected. I will publish it when the implementation provides evidence worth reviewing.

## Engineering rules

1. Reproduce the behaviour before changing code.
2. Separate observations from assumptions.
3. Make validation and error paths explicit.
4. Test invalid input as well as expected flows.
5. Document limitations and verify claims independently.

## Notes from the work

- [A failing build is evidence, not a diagnosis](https://tumelodev-arch.github.io/notes.html#note-001)
- [Validation is part of the domain](https://tumelodev-arch.github.io/notes.html#note-002)
- [Write down what would disprove the hypothesis](https://tumelodev-arch.github.io/notes.html#note-003)

The aim is simple: show what I can demonstrate, explain how I reason about it, and be precise about what remains to be built.
