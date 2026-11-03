# Student Profile Team Repository

> **Repository:** `student-profile-team--07-->`
> A shared student profile project built as a team using **Git** and **GitHub**.

## About the Project

This repository is a team activity for the Web Development lab. Each team member works on their own feature branch and HTML file, raises a Pull Request (PR), and the Team Lead reviews and merges the approved changes into `main`.

The goal is to practise real-world collaboration: cloning, branching, committing, pushing, raising Pull Requests, and reviewing and merging code.

## Team Details

**Team Number:** `--07--`

| Student   | Name             | Role                   | Branch            | File           |
|-----------|------------------|------------------------|-------------------|----------------|
| Student 1 | `Praneet Basu'       | Team Lead and Reviewer | `main`            | `README.md`    |
| Student 2 | `Hridyanshu Patnayak`| Profile Developer      | `feature/profile` | `profile.html` |
| Student 3 | `RITHVIK GOPINATH`   | Skills Developer       | `feature/skills`  | `skills.html`  |
| Student 4 | `RISHI VISPUTE`      | Contact Developer      | `feature/contact` | `contact.html` |

> For a team of three, the Team Lead also takes one of the developer roles.

## Repository Structure

```
student-profile-team--07--/
├── README.md        # Project overview (Praneet)
├── profile.html     # Profile page (Hridyanshu)
├── skills.html      # Skills page (Rithvik)
└── contact.html     # Contact page (Rishi)
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Praneet007-47/student-profile-team--07--
cd student-profile-team--07--
```

### 2. Create your feature branch

Use the branch assigned to your role:

```bash
git checkout -b feature/profile    # Student 2
git checkout -b feature/skills     # Student 3
git checkout -b feature/contact    # Student 4
```

### 3. Create your HTML file and add content

Create the file assigned to you (`profile.html`, `skills.html`, or `contact.html`) and write your page.

### 4. Stage, commit, and push

```bash
git add <your-file>.html
git commit -m "Add <your-file>.html page"
git push -u origin feature/<your-branch>
```

### 5. Raise a Pull Request

1. Open the repository on GitHub.
2. Click **Compare & pull request** for your branch.
3. Set the base branch to `main` and the compare branch to your feature branch.
4. Add a clear title and description, then click **Create pull request**.

### 6. Review and merge (Team Lead)

1. Open each Pull Request and review the changes.
2. Approve the PR and click **Merge pull request**.
3. Confirm that all HTML files are now available in the `main` branch.

## Workflow

```
clone  →  create branch  →  add file  →  commit  →  push  →  Pull Request  →  review  →  merge to main
```

## Rules

- Every member runs their own Git commands and shows their own contribution.
- The Team Lead must not complete the work on behalf of other members.
- Each feature branch must contain only the correct HTML file for that role.
- All approved changes must be merged into `main` before the demonstration.

## Submission Checklist

- [ ] GitHub repository URL
- [ ] Pull Request URLs (one per developer)
- [ ] All Pull Requests merged into `main`
- [ ] `profile.html`, `skills.html`, and `contact.html` visible in `main`
- [ ] Individual contributions demonstrated by every member
- [ ] Activity Completion Tracker updated

## Links

- **Repository:** `https://github.com/Praneet007-47/student-profile-team--07--'
- **Pull Requests:**
  - Profile: `https://github.com/Praneet007-47/student-profile-team--07--/tree/feature/profile`
  - Skills: `https://github.com/Praneet007-47/student-profile-team--07--/tree/feature/skills`
  - Contact: `https://github.com/Praneet007-47/student-profile-team--07--/tree/feature/contact`

## Contributors

- `Praneet Basu` (Team Lead)
- `Hridyanshu Patnayak`
- `Rithvik Gopinath`
- `Rishi Vispute`
