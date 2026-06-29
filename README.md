# Hackathon-Sprint

## Team: CodeCrafters
* **Aryaman**
* **Alex Smith**

## Project: CommitSpark
**Domain:** Developer Tools & Productivity Engineering

### Problem Statement
Users who are software developers working in remote teams struggle to write clear and consistent pull request descriptions because they have to manually review and summarize all their commits and changed files before submitting their code for review. Our product helps them automatically generate well-structured and descriptive PR summaries directly from their branch commit history and diffs.

### Proposed Solution
Upon launching CommitSpark, developers are greeted with a dashboard displaying their active local git repositories and current branches. The core workflow allows them to select a branch, view a list of untracked or unmerged commits, and click a button to compile these changes into an organized markdown draft. For this sprint, we will build the local repository scanner, the markdown template generator, and the export function to copy or save the generated description directly.

### Tech Stack
* **Frontend:** React (Vite & Tailwind CSS)
* **Backend:** Node.js with Express
* **Database:** SQLite
* **Deployment:** Vercel & Render
