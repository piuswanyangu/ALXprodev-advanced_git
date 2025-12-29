# ALXprodev-advanced_git

## 📌 Project Overview
This repository demonstrates the use of **Git-Flow**, a structured Git branching model used to manage features, releases, and hotfixes in a collaborative development environment.

The project follows Git-Flow best practices to simulate real-world software development workflows.

---

## 🚀 Git-Flow Setup (Task 0)

### Repository Initialization
The following commands were used to set up the repository and Git-Flow workflow:

```bash
git clone <repository-url>
cd ALXprodev-advanced_git
Create and Push Develop Branch
bash
Copy code
git checkout -b develop
git push origin develop
Initialize Git-Flow (default settings)
bash
Copy code
git flow init -d
Create Initial README
bash
Copy code
touch README.md
git add README.md
git commit -m "chore: initial project setup"
git push origin develop
This setup ensures a clean separation between production-ready code (main) and ongoing development (develop).

🌱 Feature Development (Task 1)
Feature: Implement Login Page
A feature branch was created from the develop branch using Git-Flow.

Create Feature Branch
bash
Copy code
git checkout develop
git flow feature start implement-login
This command created and switched to:

bash
Copy code
feature/implement-login
Add Feature Files
bash
Copy code
mkdir login-page
touch login-page/README.md
Content added to login-page/README.md:

nginx
Copy code
Login Feature Coming soon
Commit Changes
bash
Copy code
git add login-page/README.md
git commit -m "feat: scaffolding login page"
Push Feature Branch
bash
Copy code
git push origin feature/implement-login
This isolates the login feature development from the main codebase.

🧠 Key Concepts Practiced
Git-Flow initialization and configuration

Feature-based branching (feature/*)

Safe development using the develop branch

Meaningful commit messages using conventional commits

Pushing and managing remote branches

✅ Project Status
Git-Flow successfully initialized

Feature branch created and pushed

Login feature scaffolded

Ready for release and hotfix workflows