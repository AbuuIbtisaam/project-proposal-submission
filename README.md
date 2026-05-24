# Foundation Phase – Session 3
## Git & GitHub Collaboration Lab
### Fork → Clone → Commit → Push → Pull Request

Welcome to the Git and GitHub Collaboration Lab.

This repository is created to help students practice real software engineering collaboration using Git and GitHub.

Your task is to submit your **Project Title** and **Project Description** through a professional Git workflow.

---

# Objective

By completing this activity, students should be able to:

- Fork a GitHub repository
- Clone a repository locally
- Create a branch
- Edit project files
- Commit changes professionally
- Push code to GitHub
- Open a Pull Request

---

# Submission Workflow

```plaintext
Instructor Repository
↓
Fork
↓
Clone
↓
Create Branch
↓
Update Submission File
↓
Commit
↓
Push
↓
Open Pull Request
```

---

# Step 1 — Fork Repository

Open this repository.

Click:

Fork

This creates your own copy.

Example:

```
Instructor Repository
↓
Student Repository
```

---

# Step 2 — Clone Your Fork

Copy your fork URL.

Run:

```bash
git clone <your-fork-url>
```

Example:

```bash
git clone https://github.com/username/project-submission.git
```

Enter project folder:

```bash
cd project-submission
```

---

# Step 3 — Create Your Branch

Branch Naming Format:

```plaintext
submission-yourname
```

Example:

```bash
git switch -c submission-mansoor
```

Verify:

```bash
git branch
```

---

# Step 4 — Submit Your Work

Open:

```plaintext
submissions.md
```

Add your submission using this template.

---

# Submission Template

```md
## Student Submission

Name:
Registration Number:

Project Title:

Project Description:

Problem Statement:

Proposed Solution:

Technology Stack:
- Python
- Git
- GitHub
- Other (Optional)

Expected Outcome:
```

---

# Example Submission

```md
## Student Submission

Name:
John Doe

Registration Number:
BIT001

Project Title:
Smart Attendance System

Project Description:
A system for managing classroom attendance digitally.

Problem Statement:
Manual attendance consumes time and creates errors.

Proposed Solution:
Build a web application to automate attendance.

Technology Stack:
- Python
- Git
- GitHub
- Django

Expected Outcome:
Faster and more reliable attendance management.
```

---

# Step 5 — Save Your Work

After editing:

```bash
git add .
```

Commit professionally:

```bash
git commit -m "feat: submit project proposal"
```

---

# Step 6 — Push to GitHub

First push:

```bash
git push -u origin submission-yourname
```

Later:

```bash
git push
```

---

# Step 7 — Open Pull Request

Go to GitHub.

Click:

Compare & Pull Request

Title:

```plaintext
Submit Project Proposal – Your Name
```

Description:

```plaintext
Added project proposal for review.
```

Submit Pull Request.

---

# Submission Checklist

Before submitting confirm:

- [ ] Repository Forked
- [ ] Repository Cloned
- [ ] Branch Created
- [ ] Project Added
- [ ] Commit Completed
- [ ] Changes Pushed
- [ ] Pull Request Submitted

---

# Professional Commit Examples

Good:

```plaintext
feat: submit attendance project
docs: update project description
fix: correct proposal formatting
```

Avoid:

```plaintext
final
done
update
123
```

---

# Assessment

| Criteria | Marks |
|----------|------|
| Fork Repository | 10 |
| Clone Repository | 10 |
| Branch Creation | 10 |
| Commit Quality | 20 |
| Push to GitHub | 20 |
| Pull Request | 30 |

Total: 100 Marks

---

# Reflection Questions

1. What did you learn from Fork and Pull Request?
2. What challenge did you face?
3. Why are branches important?
4. How can Git improve teamwork?

---

Good luck and practice professional software engineering workflow.

Build → Commit → Push → Collaborate
