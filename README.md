# One rule
We don't care if you break things. This is a playground and we encourage failing, because that means you at least try. Use this as a practice ground and enjoy contributing to projects you create and maintain with your fellow students. 

# Setup and workflow
Check out this free how-to at http://makeapullrequest.com/.

On the GitHub page for this repository, click on the "Fork"-Button. Then clone your forked repository to your computer. For example by running this command inside your terminal:

```
git clone https://github.com/<your-github-username>/getting-started.git
```
Don't forget to replace \<your-github-username\>!

> Here you can learn more about [forking](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) and [cloning](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) a repo.

Before you make any changes, keep your fork in sync to avoid merge conflicts:

```
git remote add upstream https://github.com/protocode-community/getting-started.git
git pull upstream main
```

If you run into a merge conflict, you have to resolve the conflict. There are a lot of guides about this topic.

On your computer, open your text editor, and add your name to the `CONTRIBUTORS.md` file.

Add the changes with `git add`, `git commit` (write a nice commit message):

```
git add CONTRIBUTORS.md
git commit -m "Add <your-github-username>"
```
**Replace \<your-github-username\>!**

Push your changes to your repository:

```
git push origin main
```

Go to the GitHub page of your fork, and make a pull request.

Pull requests are proposed changes to a repository submitted by a user and accepted or rejected by a repository's collaborators. Like issues, pull requests each have their own discussion forum.

Read more about [pull requests](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests#about-pull-requests) on the GitHub help pages.

Wait until one of the maintainers merges your pull request.

**Go join a project and start contributing or add your own!**
