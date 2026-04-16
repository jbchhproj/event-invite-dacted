# Architecture Overview

## Approach

Modular Monolith

## Structure (Planned)

```text
/apps
  /web
  /api

/packages
  /domain
  /types
```

---

## Modules

- Event Module
- Party Module
- Guest Module
- RSVP Module
- Invitation Module

---

## Key Decisions

- Strong domain modeling
- Clear module boundaries
- Single deployable backend
- Relational database (Postgres)

---

## Rationale

- Faster development for MVP
- Easier to maintain consistency
- Can evolve into services later if needed

---

## Repository Strategy

Monorepo structure to manage frontend, backend, and shared packages in a single codebase.
