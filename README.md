# Assalamualaikum and Welcome to the Quran Verse Workshop

This GitHub project is designed to help you practice creating branches, making changes, handling merge conflicts, and reviewing code collaboratively. Follow the instructions below to complete your task.

---

## Instructions

### Step 1: Access Your Assigned Issue
1. **Go to the Project Board**: Navigate to the project board in this repository.
2. **Find Your Issue**: Locate the issue assigned to you.

### Step 2: Create a Branch
3. **Create a Branch from Your Issue**: Use the "Create a branch for this issue" feature in GitHub. Name your branch following the convention `add-verse-<yourname>`.

### Step 3: Clone the Repository
4. **Clone the Repo**: Open GitHub Desktop and clone this repository to your local machine.

### Step 4: Change to Your Branch
5. **Switch Branches in GitHub Desktop**: Make sure to change from the `main` branch to the branch you just created.

---

## Understanding the Code in This Repo
The code in this repository is simple yet functional. Here’s a breakdown:

- **`data/quran_verses.txt`**: This file will contain all participants' favorite Quran verses. Each line should follow this format:
  First Name, Last Name, Quran verse number

- **`src/verse_display.py`**: This Python script reads `quran_verses.txt` and prints each line. It’s a basic script that demonstrates how to read and display content from a file.

---

### Step 5: Make Your Changes
6. **Navigate to Your Project Directory**: In your terminal, run: cd quran-verse-workshop

7. **Edit `data/quran_verses.txt`**: Add your entry on the **first line** of the file, following the format:
   First Name, Last Name, Quran verse number

### Step 6: Test Your Changes
8. **Run the Script**: Execute the Python script to ensure your changes display correctly: python src/verse_display.py

---

### Step 7: Commit Your Changes
9. **Make a Commit**: Use a conventional commit message as per [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).
   - Example: feat: added Quran verse for Ali Khan

---

### Step 8: Create a Pull Request
10. **Open a PR**: Create a Pull Request (PR) and fill out the provided PR template.

### Step 9: Notify for Review
11. **Notify for Review**: Once your PR is ready, let the reviewers know. The reviewer will:
    - **Review Your PR**: Check for any issues and run the code locally.
    - **Resolve Merge Conflicts**: If there are conflicts, they will work with you to resolve them.
    - **Add a Screenshot**: Run the code and add a screenshot to the PR, using the "Approve with a comment" feature.

---

### Step 10: Merge Your PR
12. **Merge Into Main**: Once your PR is approved, you can merge it into the main branch.

---

## Note
Since there are 5-6 participants working on the same file, merge conflicts are **expected** and are a key part of this workshop. This exercise will give you practical experience in handling conflicts and collaborating in a team setting.

Happy coding and good luck! Let us know if you need any help.
