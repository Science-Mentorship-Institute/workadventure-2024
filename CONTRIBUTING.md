# Contributing guide

Please first refer to the official [WorkAdventure guide](https://docs.workadventu.re/map-building/tiled-editor/) to map building, and install the Tiled map editor and NodeJS.

Note that the current version of the main branch map can be viewed by anyone anytime by going [here](https://science-mentorship-institute.github.io/workadventure-2024/) to this GitHub Pages site.

## Using Git

To contribute to this project, you will need to use Git. Git should be available via the command line for MacOS/Linux systems. For Windows, you will need to download [Git for Windows](https://gitforwindows.org/) or the [GitHub CLI](https://cli.github.com/).

## Setup

1. Open your command line and navigate to the directory where you want to work on this project.
2. Clone this repository using the command `git clone https://github.com/Science-Mentorship-Institute/workadventure-2024.git` and navigate to the "workadventure-2024" directory in the command line.
3. Install all of the necessary Node packages with `npm i`.
4. By running `npm run dev`, window should open in your browser at the URL http://localhost:5173/ allowing you to test your map. More information can be found in the [README](README.md).
5. To stop the server, press Ctrl + C or Cmd + . (the latter is for Apple devices). 

## Contributing workflow
1. Always make sure your main branch is up to date by doing:
```
git checkout main
git pull origin main
```
2. To start working on new changes, switch to a new branch with `git checkout -b <branch_name>`. If this branch has already been created and you simply want to resume making changes exclude the "-b" flag. To avoid merge conflicts, please also run `git merge main` if the main branch has been updated.
3. Modify, add, or delete files in the repo directory as necessary to implement your desired changes.
4. Add, commmit, and push the changes to a new remote branch corresponding to your local feature branch:
```
git add .
git commit -m "<Describe what you changed, without the angle brackets>"
git push --set-upstream origin <branch_name>
```
5. You may repeat steps 3 and 4 as many times as necessary; note that if you have already pushed at least once you can simply do `git push` after committing.
6. Open a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) on GitHub so that your changes can be reviewed and merged into the main branch.

For more information about Git, please refer to [here](https://www.baeldung.com/ops/git-guide).

## Miscellaneous WorkAdventure guides
* https://docs.workadventu.re/admin/
* https://docs.workadventu.re/admin/integrations/google-calendar
* https://docs.workadventu.re/admin/custom-wokas/
* https://docs.workadventu.re/blog/gpt-bot
* https://docs.workadventu.re/admin/quests

