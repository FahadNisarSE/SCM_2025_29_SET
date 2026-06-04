# Lab Task Submission Instructions

Please follow the steps below to submit your lab tasks through GitHub.

## 1. Fork the Repository

Click the **Fork** button on the GitHub repository provided by the instructor. This will create a copy of the repository under your own GitHub account.

---

## 2. Clone Your Fork

Clone your forked repository to your local machine:

```bash
git clone <YOUR_FORK_URL>
```

Example:

```bash
git clone https://github.com/your-username/lab-tasks.git
```

Move into the project directory:

```bash
cd lab-tasks
```

---

## 3. Place Your Tasks in the Correct Folder

Each student has a dedicated folder in the repository.

Locate the folder corresponding to your roll number and place all task files inside it.

Example:

```
2025-SET-01/
├── Lab-01.pdf
├── Lab-02.pdf
├── Lab-03.pdf
```

### Important

* Upload your lab report as a PDF or document file.
* Include all required SQL files, source code files, screenshots, and supporting documents.
* Make sure files are placed in the correct folder for your roll number.

---

## 4. Commit and Push Your Changes

Stage your files:

```bash
git add .
```

Create a commit:

```bash
git commit -m "Submitted Lab Tasks"
```

Push your changes:

```bash
git push origin main
```

---

## 5. Create a Pull Request

After pushing your changes:

1. Open your fork on GitHub.
2. Click **Compare & Pull Request**.
3. Create a Pull Request to the original repository.

### Pull Request Title Example

```
2025-SET-01 - Lab Task Submission
```

### Pull Request Description Example

```
Roll Number: 2025-SET-01

Submitted:
- Lab Task 01
- Lab Task 02
- Lab Task 03

All required documents and files have been uploaded.
```

---

## Uploading Large Files

If your files are large, you do not need to upload everything in a single commit.

You may:

1. Add one lab task folder.
2. Commit and push it.
3. Add another lab task folder.
4. Commit and push again.
5. Continue until all tasks are uploaded.

Example:

```bash
git add 2025-SET-01/Lab-01.pdf
git commit -m "Added Lab Task 01"
git push origin main
```

Then:

```bash
git add 2025-SET-01/Lab-02.pdf
git commit -m "Added Lab Task 02"
git push origin main
```

You can keep updating the same Pull Request by pushing additional commits.

---

## Before Creating Your Pull Request

Please verify that:

* All required tasks have been uploaded.
* PDF/documents are included.
* SQL files are included where required.
* Files are placed in the correct roll number folder.
* The repository structure has not been modified.
* Your Pull Request contains only your own files.

Failure to follow the folder structure may result in delays during evaluation.