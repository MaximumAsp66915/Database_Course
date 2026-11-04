# Database_Course

Work for the **Database Design** course (course no. 40384) at the
**Sharif University of Technology**, Department of Computer Engineering,
first semester of 1405–06 (Fall 2026).

This repository serves two purposes, each on its own branch:

| Branch | Purpose |
| --- | --- |
| [`project`](../../tree/project) | The **group project**: specifications, design documents and implementation. |
| [`homeworks`](../../tree/homeworks) | A personal archive of the **homework submissions** (final PDFs and screenshots only). |

## The project

The course project is carried out in **4 phases** and is implemented on
**PostgreSQL** and **MongoDB**. The assignment comes from the Intelligent
Systems and Equipment R&D Center and starts with data requirements analysis
and semantic model design.

| Phase | Topic | Status |
| --- | --- | --- |
| I | Data requirements analysis and semantic model design | In progress |
| II – IV | See the project roadmap | Not started |

### Repository layout

```
project/
└── Phase 1/                     Phase I deliverables
    ├── preprovided/
    │   └── DB-Project-Phase-I.pdf   Phase I specification (handed out)
    ├── ER-EER-diagrams.pdf      ER/EER diagrams (readable output)
    ├── Phase1-Report.pdf        Short report: components, rules, decisions, sample situations
    └── drawio/                  Editable diagrams (draw.io): one file per diagram plus a combined file
```

New deliverables for each phase should be added under `project/`, for
example `project/Phase 1/`.

## Working with the repository

```bash
git clone https://github.com/MaximumAsp66915/Database_Course.git
cd Database_Course

# project work happens on the project branch
git switch project

# homework archive
git switch homeworks
```

## Conventions

- Only **final deliverables** are committed: PDFs and screenshots/images.
  LaTeX sources and build files (`*.tex`, `*.aux`, `*.log`, …) are ignored.
- The `homeworks` branch is independent of `project` and shares no history with it.
- Releases are disabled for this repository.

## License

Copyright © 2026 Mohammad Sabzalian and project contributors.
**All rights reserved.** See [LICENSE](LICENSE) for details.
