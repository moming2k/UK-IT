# UK-IT Projects

A community monorepo where anyone can **submit an IT project idea** and others can **easily join and build it together**.

Every project lives in its own folder under [`projects/`](./projects) — holding both the idea proposal *and* the actual code. Browse the projects, find one you like, and jump in.

---

## 🚀 Quick start

| I want to... | Do this |
|---|---|
| **Submit a new idea** | [Open a "New project" issue](../../issues/new?template=new-project.yml), or copy [`templates/project-template/`](./templates/project-template) into `projects/your-idea/` and open a PR. See [CONTRIBUTING](./CONTRIBUTING.md). |
| **Join an existing project** | Find it in [`projects/`](./projects), read its `README.md`, then [open a "Join project" issue](../../issues/new?template=join-project.yml) or add yourself to its `CONTRIBUTORS.md` via PR. |
| **Browse all projects** | See the [project index](./projects/README.md). |

---

## 📂 Repository structure

```
UK-IT/
├── README.md                      # You are here — the hub
├── CONTRIBUTING.md                # How to submit and join projects
├── CODE_OF_CONDUCT.md             # Community ground rules
├── projects/                      # Every project lives here
│   ├── README.md                  # Index of all projects
│   └── <project-name>/            # One folder per project
│       ├── README.md              # Idea, status, how to join
│       ├── CONTRIBUTORS.md        # Who's on the team
│       └── src/                   # The actual code/work
├── templates/
│   └── project-template/          # Copy this to start a new project
└── .github/
    ├── ISSUE_TEMPLATE/            # "New project" & "Join project" forms
    └── PULL_REQUEST_TEMPLATE.md
```

## 💡 How it works

1. **Submit** — Propose an idea (issue or PR). Each idea becomes a folder in `projects/`.
2. **Recruit** — Others discover your project in the index and ask to join.
3. **Build** — Teams collaborate inside their project folder. Code, docs, everything in one place.
4. **Ship** — Track progress in the project's `README.md` status.

New here? Start with **[CONTRIBUTING.md](./CONTRIBUTING.md)**.
