[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18340479&assignment_repo_type=AssignmentRepo)
# se-day-2-git-and-github
Version Control & GitHub
1. What is Version Control & Why GitHub?

Version control tracks changes in files, enabling collaboration and rollback. GitHub is popular for its distributed workflow, allowing multiple contributors to work simultaneously. It supports branching and merging for parallel development and provides collaboration tools like pull requests, issues, and discussions.
2. Setting Up a GitHub Repository

Steps:

    Log in to GitHub and click New Repository.
    Name it, add a description, and choose public or private.
    (Optional) Add a README, .gitignore, or a license.
    Click Create Repository.

Key Decisions:

    Public vs. Private: Public repositories are open-source, while private ones restrict access.
    README & License: Helps clarify project purpose and usage rights.

3. Importance of a README File

A well-written README provides an overview of the project, installation and usage instructions, and contribution guidelines. It enhances collaboration by offering clear documentation for new contributors.
4. Public vs. Private Repositories

Public repositories are accessible to everyone and encourage open-source contributions. Private repositories restrict access, making them ideal for proprietary or confidential projects. Public repositories promote community involvement, while private ones offer greater security and control.
5. Making Your First Commit

    Clone the repository using git clone <repo-url>.
    Navigate into the project directory with cd repo-name.
    Stage changes using git add ..
    Commit changes with git commit -m "Initial commit".
    Push to GitHub using git push origin main.

6. Branching in Git

Branching allows developers to work on new features without affecting the main codebase.

    Create a new branch: git checkout -b feature-branch.
    Switch between branches: git checkout feature-branch.
    Merge the branch into main:
        Switch to main using git checkout main.
        Merge with git merge feature-branch.
        Push changes using git push origin main.

7. Pull Requests (PRs)

Pull requests facilitate code review and team collaboration.
Process:

    Push changes to GitHub and open a Pull Request.
    Request a review from teammates and make necessary changes.
    Once approved, merge the branch into main.

8. Forking vs. Cloning

Forking creates an independent copy of a repository, allowing users to contribute without affecting the original project. Cloning downloads a repository locally for direct modifications. Forking is useful for open-source contributions, while cloning is ideal for team projects.
9. Issues & Project Boards

GitHub Issues help track bugs, feature requests, and tasks. Project Boards organize work into categories like To-Do, In Progress, and Done, improving task management and collaboration.
10. Common Challenges & Best Practices

Challenges & Solutions:

    Merge Conflicts: Regularly pull updates to stay in sync.
    Forgetting to Push Changes: Use git push origin branch-name.
    Accidental Commits to Main: Work in branches and submit PRs.
