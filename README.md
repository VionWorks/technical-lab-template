# VionWorks Technical Lab Template

Canonical starting point for public projects whose primary purpose is to demonstrate a specific engineering capability through inspectable implementation, controlled evaluation, and documented decisions.

## Use this template for

- RAG / retrieval systems
- agent architectures
- evaluation systems
- infrastructure experiments
- search, ranking, memory, routing, observability, or similar technical capability labs

Do **not** use it for client-style websites or commercial concept demos; those belong in the business demo family.

## Required first steps

1. Replace every `REPLACE-ME` value in `PROJECT.yaml`.
2. Register the project in `VionWorks/portfolio-registry` and allocate its permanent `TECH-###` ID.
3. Define the capability boundary in `docs/SCOPE.md` before expanding implementation.
4. Document the architecture and methodology before treating benchmark results as portfolio evidence.
5. Keep durable architectural decisions in `docs/DECISIONS.md`.

## Documentation structure

```text
docs/
├── SCOPE.md
├── ARCHITECTURE.md
├── METHODOLOGY.md
├── EXPERIMENTS.md
└── DECISIONS.md
```

Implementation folders such as `src/`, `tests/`, `benchmarks/`, and `scripts/` should be added according to the language and project needs rather than forced by the template.

## Portfolio standard

A Technical Lab should make it possible for another engineer to answer:

- What capability is being demonstrated?
- What was implemented by the project versus provided by dependencies?
- How was it evaluated?
- What evidence supports the conclusions?
- What trade-offs and rejected alternatives were identified?
- Can the result be reproduced?

The goal is evidence of engineering judgment, not repository size.

## Registry

Canonical taxonomy and metadata rules live in [VionWorks/portfolio-registry](https://github.com/VionWorks/portfolio-registry).
