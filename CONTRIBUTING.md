# Contributing

Welcome! This repo is a hub for IT project ideas. There are two things you'll want to do: **submit a new idea** or **join an existing project**. Both are easy.

---

## 🆕 Submit a new project idea

You have two options — pick whichever is comfortable.

### Option A — Open an issue (easiest)

1. [Open a **New project** issue](../../issues/new?template=new-project.yml).
2. Fill in the short form (name, problem, proposed solution).
3. A maintainer (or you!) will scaffold the project folder from the issue.

### Option B — Open a pull request (full control)

1. Copy the template folder into `projects/` with a kebab-case name:
   ```bash
   cp -r templates/project-template projects/your-idea-name
   ```
2. Edit `projects/your-idea-name/README.md` — fill in the idea, problem, and plan.
3. Add yourself as the initiator in `projects/your-idea-name/CONTRIBUTORS.md`.
4. Add a row for your project in [`projects/README.md`](./projects/README.md).
5. Open a PR. The [PR template](./.github/PULL_REQUEST_TEMPLATE.md) will guide you.

**Naming:** use lowercase `kebab-case`, e.g. `ai-helpdesk-assistant`, `campus-wifi-map`.

---

## 🤝 Join an existing project

1. Browse the [project index](./projects/README.md) and open any project's `README.md`.
2. Check its **Status** and **Looking for** section to see if they need your skills.
3. Say hello — either:
   - [Open a **Join project** issue](../../issues/new?template=join-project.yml), or
   - Open a PR adding your name to that project's `CONTRIBUTORS.md`.
4. Start contributing in the project's `src/` folder.

---

## 🌱 Project lifecycle & status

Each project's `README.md` carries a status badge near the top:

| Status | Meaning |
|---|---|
| `💡 Idea` | Proposed, looking for a team. |
| `🚧 In progress` | Active development. |
| `✅ Shipped` | Delivered / live. |
| `🧊 Paused` | On hold, open to being revived. |

Keep it up to date so others know where things stand.

---

## ✅ Ground rules

- Keep all work for a project **inside its own folder** under `projects/`.
- Don't edit another team's folder without coordinating (issues/PRs are great for this).
- Be kind and inclusive — see the [Code of Conduct](./CODE_OF_CONDUCT.md).
- Small, focused PRs are easier to review and merge.

Questions? Open an issue. Thanks for building with us! 🎉
