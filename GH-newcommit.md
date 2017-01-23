# GitHub Tutorial `2`

### Make a new Git Commit and push it to remote master.

- _Please refer to GitHub Tutorial 1 before making a new repository._
- _Please download [Atom](https://atom.io/) if you don't have it yet._
- _Make sure you are in the directory in your local Environment that you have cloned from GitHub from tutorial 1._
- _Make a change on the README.md file in your newly cloned directory by using Atom._

--------------------------------------------

1. In your terminal Type `atom README.md`
This opens README.md in Atom.
2. In your terminal Type `git status`
Lists all new or modified files to be commited.
3. You should see this in your terminal `modified:   README.md` This means that Git has noticed your change on the file README.md.
4. In your terminal Type `git add .`
This means you have added all the files in preparation for versioning. You can also enter `$ git add [file]`which means add this file in preparation for versioning. You can choose to type in your terminal `git status` to see if your changes has been added to staging.
5. In your terminal Type: `git commit -m"Added description to README.md to indicate the purpose of this repository" `
Think about this as setting a milestone for your project.
6. In your terminal Type `git push origin master`.
Find a ref that matches master in the source repository, and update the same ref in origin repository with it. If master did not exist remotely, it would be created.
7. Now go to your GitHub repository and refresh. You should see your new commit.


--------------------------------------------


After Class Read:
- [Understanding the GitHub Work Flow](https://guides.github.com/introduction/flow/)

Additional Resources:

- Terminal command [cheatsheet](https://github.com/0nn0/terminal-mac-cheatsheet).
- Git command [cheatsheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf).
- [GitHub Guide](https://guides.github.com/)
- More in depth [Extended Resource](https://services.github.com/classnotes/)
- Atom [Essential Classes](https://atom.io/docs/api/v1.13.0/AtomEnvironment)
- Atom [cheatsheet](https://gist.github.com/chrissimpkins/5bf5686bae86b8129bee)
