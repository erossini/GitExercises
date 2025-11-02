# Git Exercises

## Why git?


hitygcjctyfckgiktyujvtug

For a thorough discussion on the pros and cons of Git compared to centralized source code control systems, see the web. There are plenty of flame wars going on there. As a developer, I prefer Git above all other tools around tody. Git really changed the way developers think of merging and branching.

From the classic CVS/Subversion world I came from, merging/branching has always been considered a bit scary (“beware of merge conflicts, they bite you!”) and something you only do every once in a while.

But with Git, these actions are extremely cheap and simple, and they are considered one of the core parts of your daily workflow, really.

## Plan

Install [Git](https://git-scm.com/install/).
[Markdown](https://www.markdownguide.org/basic-syntax/)

### GitHub

- Create your account with [GitHub](https://github.com/)
- Clone this repository
- Create a pull request
- Review and peer review
- Fork this repository
- Manage conflicts
- Create a Wiki
- Create your personal page

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
git clone https://github.com/erossini/GitExercises.git
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

Students open a pull request to merge their branch into main.

8. Review & Merge

Peers review the pull request and merge it.

9. Conflict Resolution (Optional Challenge)

If two students edit the same line, Git will show a conflict. Instructor can simulate this and guide students through resolving it:

```bash
git pull origin main
# Resolve conflict in story.txt
git add story.txt
git commit -m "Resolved merge conflict"
```

## Create your personal bio

### Create a new repository

- Go to your GitHub account and click "New repository".
- Name the repository exactly the same as your username.

> Example: If your username is `erossini`, the repo name should be `erossini`.

### Make it public

The repository must be public for the README to show on your profile.

### Check "Add a README file"

GitHub will automatically detect this and display the README on your profile.

### Customize your README

You can use [Markdown](https://www.markdownguide.org/cheat-sheet/) to add:

- Text ✍️
- Images 🖼️
- Links 🔗
- Emojis 😎
- Badges 🚀

Example:

    # Hi, I'm Enrico 👋

    - 🔭 I’m currently working on open-source projects
    - 🌱 Explaining GitHub
    - 📫 Reach me at [My Website](https://puresourcecode.com)

    ![GitHub Stats](https://github-readme-stats.vercel.app/api?username=erossini&show_icons=true)
