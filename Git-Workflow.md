# GitHub Workflow Guidelines for Lund biodiversitydata-se Project

## Basic Principles
1. **Branching Strategy**: Use branches for all **new changes, features, fixes, and refactoring**. Avoid direct commits to the main or develop branch.
2. **Code Reviews**: All changes must undergo code review before merging into the main branches to ensure quality and consistency.
3. **Continuous Integration**: Ensure that the `develop` branch always contains a working version of the application.

## Workflow Steps
### 1. Creating Branches
- We (every developer) should create a new branch for each change we want to make.
- Branch names should be descriptive and reflect the purpose of the change.
- Avoid creating branches without any actual changes or features.

### 2. Making Changes
- We (developers) work on our respective branches, making changes and improvements.
- Follow the project's coding standards and guidelines while making modifications (evolving standards are occuring during the development process, so if we're uncertain about how to proceed or if the modification might impact existing standards, we should consult with our team members via Slack).

### 3. Code Reviews
- Once changes are ready, initiate a pull request (PR) for review.
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

----- 1. **Avoid Direct Commits to Main/Develop Branch:**
   - We agreed not to commit directly to the main or develop branch.








# GitHub Code Review and Workflow Guidelines

To ensure a smooth and efficient code review process, as well as a streamlined workflow for our development team, we've established the following guidelines:


## Workflow:



2. **Code Reviews:**
   - All changes must go through a code review process.
   - To facilitate code reviews, do not push directly to the develop branch. Instead, push changes to feature branches.

3. **Maintain a Working Version in Develop Branch:**
   - The develop branch should always have a working version of the application.
   - Developers should be able to see and interact with the application in this branch.

## Workflow Steps:

1. **Pull Before Push:**
   - Every time you want to make a change, pull the latest changes from the target branch.
   - This ensures that you're working on the most up-to-date version of the codebase.

2. **Create New Branches for Changes:**
   - When starting work on a new change or feature, create a new branch from the target branch.
   - Work on this branch separately and avoid directly modifying the develop branch.

3. **Merge and Push:**
   - Once your changes are complete and have been reviewed, merge them into the target branch.
   - After merging, push the changes to the remote repository.

## Additional Notes:

- **Code Review Comments:**
  - Ensure that comments and feedback from code reviews are addressed before merging changes.
  - Reviewers should provide clear and constructive feedback to help improve code quality.

- **Documentation:**
  - Document any significant changes, including reasons for modifications, to ensure transparency and clarity for all team members.

By adhering to these guidelines, we aim to maintain a clean and organized codebase, minimize conflicts, and facilitate effective collaboration within our development team. 
