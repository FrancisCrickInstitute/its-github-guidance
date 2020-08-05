# its-github-guidance
A place for best practice, hints and tips. Please feel free to contribute your own 

# Conventions
* For [Repo Naming](https://github.com/bcgov/BC-Policy-Framework-For-GitHub/blob/master/BC-Gov-Org-HowTo/Naming-Repos.md) use the `lowercase-and-dashes.git` pattern in most cases.
* R packages have their [own conventions](http://r-pkgs.had.co.nz/package.html) and do not permit dashes. Convention is to use one repo per package and use the same name. `CamelCase` is popular.

# Suggested practises 
* Use github.com as the master repo in most cases
* Maintain a separate `devel` branch
* Use additional branches for packages of work. Groups of changes may then be trivially rolled back. 
* If you have multiple people collaborating on a repo, maintaining separate branches for different workflows is even more important 
* Clone repos to your local machine for development
* Clone the master branch of repos to production servers to ensure only production-ready code runs there
* Changes to the master branch happen only by Pull Request

# Useful Links
* [Introduction to GitHub](https://learngitbranching.js.org/)
* Power-up your README's with the [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Online interactice branch tutorial](https://learngitbranching.js.org/)
* [Git For Ops People Podcast](https://packetpushers.net/podcast/day-two-cloud-043-git-for-ops-people/)
* [Learning Git Branching](https://learngitbranching.js.org/)
