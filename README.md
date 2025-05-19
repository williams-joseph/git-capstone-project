# Git Capstone Project
---
## Enhancing A Community Library Website
---
This Project simulates the roles of two contributors with respective objectives of updating the features of the **Greenwood Community Website**, to include **Book Reviews** page and update an upcoming event on the **Events Page**. The contributors are **Morgan** and **Jamie**. Below is a detailed walkthrough of the tasks performed.

### Repository Setup (Admin)
---
 A new Github Repository `greenwood-library-website` initialized with `README` file was created. 

![Web Repo Created](Images/new-repo-created.png)
---
Since this project is a simulation of two collaborators on a single machine(Ubuntu), there will be only one `git clone` command.

![Clone Greenwood Site](Images/clone-greenwood-repo.png)
---
Also to properly simulate PR reviews of the two contributors, another Github User was invited as a collaborator.

![Invite Collaboration](Images/new-github-accn-collab-invite.png)
---
Added `home.html`, `about_us.html`,  `events.html`, `contact_us.html` files in text editor(VSCode) simulating the teams's existing codebase.

![Added Files](Images/created-html-css-js-files-vscode.png)
---
Added, Commits and Push the files to Remote Repo.

![Initial Commit](Images/stage-commit-push-files.png)
---
Created a New Branch `add-book-reviews` for Morgan's work.

![New Branch for Book Review](Images/morgan-create-branch-add-book-review.png)
---
 ### Feature Addition: Book Reviews Page by Morgan
 ---
 Morgan creates and edited a new `book_reviews.html` file in VSCode.

 ![Added book review file](Images/morgan-creates-book-reviews-html-vscode.png)
---
Morgan stages the modifications. Then pushes it to the branch.

![Morgan Adds, Commits and Push changes](Images/morgan-add-commit-push-branch-book-review.png)

### Content Update: Events Page by Jamie
---
New Branch Created for Jamie's Work.

![Created branch for jamie](Images/Jamie-creates-update-events-branch.png)
---
Jamie modifies the content in the `events.html` page to add an upcoming event. 

![Jamie Modifies Events Page](Images/Jamie-modifies-events-html.png)
---
Jamie adds, commits and push changes to repo on `update-events` branch.

![Staged Update Events](Images/Jamie-add-commit-events.png)

![Pushed Updates to branch on repo](Images/Jamie-event-push-branch.png)
---

### Pull Requests Summary
---
**Morgan PR tasks detailed below:**

- Morgan switches to `book-reviews` branch.

    ![Morgan switch branch on github](Images/Morgan-switch-branch.png)

- Morgan creates PR.

    ![Morgan creates PR](Images/morgan-creates-PR.png)

    ---

**Jamie PR tasks detailed below:**

- Jamie switches to `update-events` branch.

    ![Jamie switch branch on github](Images/Jamie-switch-branch.png)

- Jamie creates PR.

    ![Jamie creates PR](Images/Jamie-creates-PR.png)
---
- Morgan reviews and accepts Jamie's PR.
    ![Morgan accepts Jamie's PR](Images/Morgan-Review-Jamie-PR.png)

- Jamie reviews and accepts Morgan's PR.
    ![Jamie accepts Morgan's PR](Images/Jamie-Review-Morgan-PR.png)

---
### Post-PR Tasks: Merging Contributions
---

- Merging Morgan's work to `main` branch on local Repo.

![Merging morgan's work to main](Images/merge-morgan-work-to-main.png)

- Pushing Morgan's work to `main` on Remote Repo.

![Pushing morgan's work to main](Images/push-after-merge-to-main-morgan.png)

---

- Merging Jamie's work to `main` branch on local Repo.

![Merging jamie's work to main](Images/merge-Jamie-work-to-main.png)

- Pushing Jamie's work to `main` on Remote Repo.

![Pushing jamie's work to main](Images/push-after-merge-to-main-jamie.png)
---

### Commit Log Summary
---

Below is a summary of the commit history reflecting individual and collaborative contributions throughout the project:

![Git Log](Images/git-log-greenwood-site.png)

