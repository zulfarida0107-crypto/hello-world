# Hello World GitHub Actions Workflow

A lightweight and simple GitHub Actions workflow template configured to run on a self-hosted runner (`my-laptop`). This project demonstrates automated job execution triggered by repository push events.

---

## 🚀 Workflow Overview

The workflow file (`runner.yml`) executes a series of automated steps whenever code is pushed to the `main` branch:

1. **Say Hello**: Prints a friendly greeting message to the runner console.
2. **Show Date and Time**: Displays the current system timestamp of the execution.
3. **Show GitHub Info**: Outputs dynamic GitHub context variables, including:
   - Repository name (`github.repository`)
   - Current Git branch/ref (`github.ref`)
   - Commit SHA hash (`github.sha`)

---

## 📂 Configuration Details

- **Trigger Event (`on`)**: `push` to the `main` branch.
- **Execution Environment (`runs-on`)**: `my-laptop` (configured for a self-hosted runner setup).
- **File Location**: `.github/workflows/runner.yml`

---

## 🛠 Usage & Setup

1. Clone or upload this repository to your GitHub account.
2. Set up a self-hosted runner on your local machine and assign it the label `my-laptop`.
3. Push any commit to the `main` branch to trigger and observe the automated workflow execution!
