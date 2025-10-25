# Git Exercises

## Why git?

For a thorough discussion on the pros and cons of Git compared to centralized source code control systems, see the web. There are plenty of flame wars going on there. As a developer, I prefer Git above all other tools around today. Git really changed the way developers think of merging and branching.

From the classic CVS/Subversion world I came from, merging/branching has always been considered a bit scary (“beware of merge conflicts, they bite you!”) and something you only do every once in a while.

But with Git, these actions are extremely cheap and simple, and they are considered one of the core parts of your daily workflow, really.

## Plan

### GitHub

- Create your account with [GitHub](https://github.com/)
- Clone this repository
- Create a pull request
- Fork this repository
- Manage conflicts

### Azure DevOps

1.  If you don't have one, [create a Microsoft account](https://azure.microsoft.com/services/devops/).
    
2.  Go to [Azure DevOps](https://azure.microsoft.com/services/devops/) and select **Get started with Azure**.
    
3.  Select either **Try Azure for free** or **Pay as you go**.
    
4.  Enter your Microsoft account credentials and go through the sign-up process.
    Azure DevOps creates an organization:
    *   If you signed up with a newly created Microsoft account, Azure DevOps creates a project named after your account.
    *   If you signed up with an existing Microsoft account, [create a project](https://learn.microsoft.com/en-us/azure/devops/organizations/projects/create-project?view=azure-devops) next.
    Sign in to your organization at any time: `https://dev.azure.com/{Your_Organization}`.

## Documentation

- [Git Flow](https://puresourcecode.com/tools/a-successful-git-branching-model/)

## Software

- [GitHub desktop](https://desktop.github.com/download/)
- [Sourcetree](https://www.sourcetreeapp.com/) simplifies how you interact with your Git repositories so you can focus on coding. Visualize and manage your repositories through Sourcetree's simple Git GUI.
- [Visual Studio Code](https://apps.microsoft.com/detail/xp9khm4bk9fz7q?launch=true&mode=full&hl=en-gb&gl=gb&ocid=bingwebsearch)
- [Visual Studio](https://visualstudio.microsoft.com/downloads/)

## Exercices

- [GeeksforGeeks](https://www.geeksforgeeks.org/git/git-exercise/): Offers simple Git exercises, practice questions, and solutions suitable for all skill levels. 
- [WebUtility.io](https://webutility.io/git-simulator-online): Provides a Git Simulator for hands-on practice with Git commands and workflows directly in your browser.
- [Git Exercises](https://gitexercises.fracz.com/): A dedicated platform to learn and practice Git with various exercises. These resources will help you level up your Git knowledge effectively!

---

## Build a Collaborative Story

Students will collaboratively build a short story using Git. Each student contributes a paragraph, practices branching, merging, and resolving conflicts.

### 🧑‍🏫 Setup

- Each student should have Git installed and access to GitHub or another Git hosting service.
- Instructor creates a public repository called collaborative-story.

### 📝 Instructions

1. Clone the Repository

```bash
git clone [https://github.com/erossini/GitExercises.git](https://github.com/erossini/GitExercises.git)
cd GitExercises
```

2. Create a New Branch

Each student creates a personal branch:

```bash
git checkout -b student-name-story
```

3. Add a Paragraph

Edit the file story.txt and add a paragraph at the end.

4. Commit the Change

```bash
git add story.txt
git commit -m "Added my paragraph to the story"
```

5. Push the branch

```bash
git push origin student-name-story
```

6. Create a Pull Request
7. 
Students open a pull request to merge their branch into main.

8. Review & Merge

Instructor or peers review the pull request and merge it.

9. Conflict Resolution (Optional Challenge)

If two students edit the same line, Git will show a conflict. Instructor can simulate this and guide students through resolving it:

```bash
git pull origin main
# Resolve conflict in story.txt
git add story.txt
git commit -m "Resolved merge conflict"
```
