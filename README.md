# 💻 COMP3104 (DevOps) - Group 65 Assignment 1

---

## 👥 Group Members

| Name           | Student ID | GitHub Username                               | Role |
| -------------- | ---------- | --------------------------------------------- | ---- |
| Zach Keatings  | 101422808  | [@ZacharyKeatings](https://github.com/ZacharyKeatings) | Leader |
| Jonathan Weir  | 101181715  | [@Stuckc](https://github.com/Stuckc) | Collaborator |
| Mustafa Bandukda | 101203879 | [@MustafaBan](https://github.com/Mustafaban) | Collaborator |
| Daniel Demesa | 101440281 | [@danieldemesa](https://github.com/danieldemesa) | Collaborator |
---

## 📝 Project Description

This project is part of the COMP3104 DevOps course. Each team member contributes by creating individual branches, adding text files that cover different topics, and practicing Git-based collaboration techniques. The project includes creating at least 10 meaningful commits per member to ensure continuous and incremental contributions.
The primary goal of this project is to teach students the importance of version control, continuous integration, and collaborative workflows in software development. By using GitHub and Git commands, students gain hands-on experience in managing codebases in a team environment and showcase our understanding of work until now.


---

## 📜 Instructions

Clone the Repository:
To get started, clone the repository to your local machine by running:

```
git clone https://github.com/ZacharyKeatings/COMP3104_Group65_Assignment.git
```

Navigate to the Project Directory:
Change directory into the cloned repository:

```
cd COMP3104_Group65_Assignment
```
Create Your Branch:
Each member should create a branch named in the format STUDENTID-Name (e.g., 101422808-Zach):

```
git checkout -b STUDENTID-Name
```
Make Changes:
Add your required files (e.g., Studentid_gb.txt, Studentid_devops.txt, Studentid_sdlc.txt) and make commits. Ensure each commit is meaningful:

```
git add .
git commit -m "Descriptive commit message"
```
Push Your Branch:
Once changes are made, push your branch to the remote repository:

```
git push -u origin STUDENTID-Name
```
Open a Pull Request:
After pushing your changes, go to GitHub, create a Pull Request (PR) from your branch to the main branch, and wait for review and approval.

---

## 🚀 CI/CD Details

Our repository uses GitHub Actions for continuous integration. The CI pipeline is triggered on every push to ensure that all necessary files are included and that the repository meets the project requirements.

 - CI Tool: GitHub Actions
 - Workflow File Location: The CI workflow is defined in ```.github/workflows/ci.yml.```
 - Trigger: The workflow runs on every push to any branch, validating file presence and ensuring the repository is correctly structured.
 - Job Details: The CI job checks out the repository, lists the files, and verifies the presence of required files such as ```Studentid_gb.txt```, ```Studentid_devops.txt```, and ```Studentid_sdlc.txt```.

---

## 🌲 Branching Strategy

For this project, we use a simple branching strategy to ensure organized and conflict-free collaboration:

 - Branch Naming: Each team member works on a separate branch named in the format ```STUDENTID-Name``` (e.g., ```101422808-Zach```).

 - Individual Contributions: Each branch contains the individual member’s contributions, including the three required text files and at least 10 commits. This helps keep each person’s work isolated and easier to review.

 - Pull Requests: Once a member has completed their work, they must open a Pull Request (PR) to merge their branch into the ```main``` branch. This allows for code reviews, conflict resolution, and ensures that the ```main``` branch remains stable.

 - Merging: After all reviews are complete and conflicts (if any) are resolved, the branch is merged into the ```main``` branch, ensuring that the project progresses incrementally without breaking the codebase.