
# GDSC GHRCEM 

This is a repository for you to pratice and make pull request by adding
your image to our website. 



![Logo](https://i.ibb.co/3zBx38L/webSnap.png)


## Instructions:
- Fork the project:
  Click the gray `Fork` button in the top right of this page. This creates _your_ copy of the project and saves it as a new repository in your github account

![Logo](https://i.ibb.co/pZhSb9Q/fork.png)
- Click on the green `Code` button, then either the HTTPS or SSH option and, click the icon to copy the URL. Now you have a copy of the project. Thus, you can play around with it locally on your computer.

![Logo](https://i.ibb.co/x7b2x2t/code-clone.png) 

- Run the following commands into a terminal window (Command Prompt, Powershell, Terminal, Bash, ZSH). Do this to download the forked copy of this repository to your computer.

```bash
  git clone LinkCopied
```

- Switch to the cloned folder. You can paste this command into the same terminal window.

```bash
  cd gdscghrcem.github.io
```
- Open the colned files in vs-code

```bash
  code .
```
- Make a new branch. Your username would make a good branch because it's unique.

```bash
  git checkout -b <name-of-new-branch>
```

- Open the `assets` folder and paste you 1:1 ratio image there.
- Then open the `index.html` file and paste the path of the image alloted to you. 
```bash
  <img src="./assets/name.png" id="img" />
```

- Stage your changes.

```bash
  git add .
```

- Commit the changes.

```bash
  git commit -m "Add image" 
```

- Check the status of your repository.

```bash
  git status
```

- The response should be like this:

```bash
On branch <name-of-your-branch>
nothing to commit, working tree clean
```

- Pushing your repository to GitHub.

```bash
  git push origin <name-of-your-branch>
```

or

```bash
  git branch -M main
  git push -u origin main
```
