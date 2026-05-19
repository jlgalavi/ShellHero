# Contributing to ShellHero 👾

First off, thank you for considering contributing to ShellHero! Whether you are a core team member or an Open Source enthusiast, we want to make contributing to this project as easy and transparent as possible.

## 🚀 How to Contribute

Depending on your permissions in the repository, the workflow differs slightly.

### 1. For External Contributors (The Fork Workflow)
If you are not an official collaborator, you won't be able to create branches directly in this repository. Please follow these steps:

1. **Fork** the repository by clicking the "Fork" button in the top right corner of this page.
2. Clone your forked repository to your local machine.
3. Create a new branch for your feature or bugfix: `git checkout -b feature/amazing-new-feature`
4. Make your changes and commit them with descriptive messages.
5. Push your branch to your fork: `git push origin feature/amazing-new-feature`
6. Open a **Pull Request (PR)** from your fork to our `main` branch.

### 2. For Official Collaborators
If you are part of the core team and have write access, you can work directly within the repository:

1. **Never commit directly to `main`.** The `main` branch is protected and should always contain stable, working code.
2. Update your local `main` branch: `git pull origin main`
3. Create a new branch for your task: `git checkout -b feature/your-feature-name`
4. Commit your changes and push the branch: `git push origin feature/your-feature-name`
5. Open a **Pull Request (PR)** against the `main` branch.

## 🔍 Pull Request Guidelines

- Ensure your PR has a clear, descriptive title.
- Explain what changes you made and why in the PR description.
- **Review process:** Every PR must be reviewed and approved by at least one other team member before it can be merged into `main`.

## 🛠️ Tech Stack

ShellHero is built using a combination of two powerful tools:
- **Rust:** Acting as the "brain", handling core logic, local database updates, and rendering the companion.
- **Bash:** Acting as the "sensor", hooking into the terminal to capture events and commands.

We look forward to building this adventure with you. Happy coding!
