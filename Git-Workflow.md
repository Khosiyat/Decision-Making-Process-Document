# GitHub Workflow Guidelines for Lund University's `biodiversitydata-se` Project
To minimize conflicts among us (developers) in terms of maintaining a clean and organized codebase and to ensure a smooth and efficient code review process we've established the following guidelines.

## Basic Principles
1. **Branching Strategy**: Use branches for all **new changes, features, fixes, and refactoring**. Avoid direct commits to the main or `develop` branch (We agreed not to commit directly to the main or develop branch).
2. **Code Reviews**: All changes must undergo code review before merging into the main branches to ensure quality and consistency.
3. **Continuous Integration**: Ensure that the `develop` branch always contains a working version of the application.

## General Workflow Steps:

- **Pull Before Push:**
- **Create New Branches for Changes:**
- **Review and Merge then Push:**

## Workflow Rules:
### 1. Creating Branches
- We (every developer) should create a new branch for each change we want to make.
- Branch names should be descriptive and reflect the purpose of the change.
- Avoid creating branches without any actual changes or features.

### 2. Making Changes
- We (developers) work on our respective branches, making changes and improvements.
- Follow the project's coding standards and guidelines while making modifications (evolving standards are occuring during the development process, so if we're uncertain about how to proceed or if the modification might impact existing standards, we should consult with our team members via Slack).

### 3. Code Reviews
- Once changes are ready, initiate a pull request (PR) for review (to facilitate code reviews, do not push directly to the develop branch. Instead, push changes to feature branches.)
- Select team members (2 of the 3 developers for now: Khosiyat, Yuliia, Zuzanna) for the PR.
- Reviewers should provide constructive feedback and approve the PR before merging.

### 4. Merging Changes
- After approval, merge the changes into the develop branch.
- Ensure that the develop branch remains stable and functional at all times.
- Avoid pushing directly to the develop branch.
- Before pushing any changes to a shared (`develop`) branch, ensure that your changes have been merged successfully with the latest version of the target branch (to avoid the conflicts we are encountering frequently)

### 5. Pulling Changes
- Before making any new changes, pull the latest changes from the develop branch to stay up-to-date.
- Resolve any merge conflicts locally before proceeding.

### 6. **Documentation:**
  - Document any significant changes (at least leave comments), including reasons for modifications, to ensure transparency and clarity for all team members.

