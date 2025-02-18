# Git, WebStorm, and GitHub Tutorial

## Part 1: Directions on Using WebStorm

### Step 1: Download Required Software
1. **Download WebStorm**:  
   Visit the [WebStorm Download Page](https://www.jetbrains.com/webstorm/download/) and install the latest version for your operating system.
2. **Download Git**:  
   If Git is not already installed on your system, download it from the [Git Official Website](https://git-scm.com/downloads) and follow the download instructions.

### Step 2: Configure Git in WebStorm
1. Open WebStorm.
2. Go to **File > Settings** (on Windows/Linux) or **WebStorm > Preferences** (on macOS).
3. In the Settings/Preferences window, expand the **Version Control** section and select **Git**.
4. In the **Path to Git executable** field, make sure the correct path is set. Click the **Test** button to check that Git is correctly configured.

### Step 3: Create a New Project
1. On the WebStorm welcome screen, select **New Project**.
2. Choose project type.
3. Specify your project location and click **Create**.

### Step 4: Initialize a Git Repository in Your Project
1. With your project open, go to **VCS > Enable Version Control Integration**.
2. In the box that appears, select **Git** and click **OK**.

### Step 5: Making Changes and Committing
1. Edit your project files as needed.
2. To commit your changes:
   - Go to **VCS > Commit**.
   - In the commit dialog, review your changes and enter a descriptive commit message.
   - Click **Commit**.

### Step 6: Connecting Your Project to GitHub
1. **Create a GitHub Account**:  
   If you don't have one, sign up at [GitHub](https://github.com/).
2. **Create a Repository on GitHub**:  
   Log in to GitHub, click the **+** icon in the upper-right corner, and select **New repository**. Follow the prompts to create your repository.
3. **Add the Remote Repository in WebStorm**:
   - In WebStorm, go to **VCS > Git > Remotes**.
   - Click the **+** button to add a new remote.
   - Enter the repository URL you obtained from GitHub and click **OK**.

### Step 7: Pushing and Pulling Changes
1. **Push Changes**:
   - Go to **VCS > Git > Push**.
   - Check the commits you are pushing, then confirm to upload them to GitHub.
2. **Pull Changes**:
   - To update your local repository with changes from GitHub, go to **VCS > Git > Pull**.

### Step 8: Fetching and Merging Updates
1. **Fetch**:
   - Use **VCS > Git > Fetch** to download new data from the remote repository without merging changes immediately.
2. **Merge**:
   - To combine the fetched changes into your current branch, go to **VCS > Git > Merge**.
   - If there are conflicts during merging, WebStorm will highlight them and give you tools to resolve the conflicts manually.

## Part 2: Glossary

- **Branch**: A separate copy of your project where you can try new ideas or fix problems without changing the main project. When you're ready, you can combine it back with the main branch.
- **Clone**: Making a copy of a project from the internet onto your computer so you can work on it locally.
- **Commit**: Saving your changes in the project. You also add a short message to explain what you changed.
- **Fetch**: Checking for any new changes in the online project without adding them to your work yet.
- **Git**: A tool that tracks all the changes made to your project, helping you work on it safely and with others.
- **Github**: A website where projects using Git are stored and shared, making it easy to work together with others.
- **Merge**: Combining changes from two different branches into one.
- **Merge Conflict**: A problem that happens when changes from different branches clash, so you need to decide which changes to keep.
- **Push**: Sending your saved changes from your computer to the online project.
- **Pull**: Getting the latest changes from the online project and adding them to your local computer.
- **Remote**: The online version of your project, usually hosted on a service like GitHub.
- **Repository**: A folder or storage space where your project is kept, including its files and history.

## References

- JetBrains. (n.d.). *WebStorm Download*. [https://www.jetbrains.com/webstorm/download/](https://www.jetbrains.com/webstorm/download/)
- Git. (n.d.). *Git Downloads*. [https://git-scm.com/downloads](https://git-scm.com/downloads)
- GitHub. (n.d.). *GitHub*. [https://github.com/](https://github.com/)
- Atlassian. (n.d.). *Git Tutorials*. [https://www.atlassian.com/git/tutorials](https://www.atlassian.com/git/tutorials)
