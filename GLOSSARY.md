# Commits
A commit simply is a collection of information around your changes, a message about how you got there, and the commits info that came before it. The changes don't even have to be code, it is just anything you want to add to the repository.

Think of a commit message as a note to your future self: it should give a hint on the intention for changing those files.

# There's no place like 'origin/main'
Knowing where we are in a Git project starts with thinking of a tree. All Git projects have a root, similar to the idea of a filesystem's root directory. By convention, main is the default name for the default branch in your root directory.

The term "repository" is used as a way of talking about all copies of the same project. There is the local repository, where you edit your code, and the remote repository, the place where you want to send it. Remotes can be anywhere, but they are often hosted on repository services like GitLab or GitHub.

# Where do we come from where do we go?
Being lost is part of the fun of a Git repository. We can find our way by running through this set of commands:

```
git branch - to find which branch you're on

git log - to see what commit you're on

git status - to see what edits you've made since the last commit

git remote - to see what remote repository you're tracking
```
These commands will give you a sense of direction when you're stuck.

# Glossary
* **Commit** - stores the current contents of the index in a new commit along with a log message from the user describing the changes
* **Branch** - a pointer to a commit
* **Main** - the default name for the first branch
* **HEAD** - a pointer to the most recent commit on the current branch
* **Merge** - joining two or more commit histories
* **Workspace** - the colloquial name for your local copy of a Git repository
* **Working tree** - the current branch in your workspace; you see this in git status output all the time
* **Cache** - a space intended to temporarily store uncommitted changes
* **Index** - the cache where changes are stored before they are committed
* **Tracked and untracked files** - files either in the index cache or not yet added to it
* **Stash** - another cache, that acts as a stack, where changes can be stored without committing them
* **Origin** - the default name for a remote repository
* **Local repository** - another term for where you keep your copy of a Git repository on your workstation
* **Remote repository** - a secondary copy of a Git repository where you push changes for collaboration or backup
* **Upstream repository** - the colloquial term for a remote repository that you track
* **Pull request** - a GitHub-specific term to let others know about changes you've pushed to a branch in a repository
* **Merge request** - a GitLab-specific term to let others know about changes you've pushed to a branch in a repository
* **'origin/master'** - the default setting for a remote repository and its primary branch

# About working with open source projects:
Every open source community is different. The vocabulary, norms, and communication styles may vary strongly. But majority of open source projects follow a similar organizational structure. A typical open source project can have the following types of people:

* **Author:** The person/s or organization that created the project.
* **Owner:** The person/s who has administrative ownership over the project or repository.
* **Maintainers:** Contributor/s who are responsible for driving the vision and managing the organizational aspects of the project.
* **Contributors:** Everyone who has contributed something to the project.
* **Community Members:** People who use the project. They might be active in conversations or spreading its publicity by writing about it for example.

A project usually has documentation files listed in the top level directory of a repository.

* **README:** The README is the instruction manual that welcomes new community members to the project. It explains why the project is useful and how to get started.
* **CONTRIBUTING:** It explains what types of contributions are needed and how the process works. While not every project has a CONTRIBUTING file, its presence signals that this is a welcoming project to contribute to.
* **CODE_OF_CONDUCT:** The code of conduct sets ground rules for participants’ behavior associated and helps to facilitate a friendly, welcoming environment. While not every project has a CODE_OF_CONDUCT file, its presence signals that this is a welcoming project to contribute to.
* **LICENSE:** By definition, every open source project must have an open source license. If the project does not have a license, it is not open source.
* **OTHER:** There might be additional documentation, such as tutorials, walkthroughs or governance policies, especially on bigger projects.

Open source projects use tools to organize discussion. Reading through the archives will give you a good picture of how the community thinks and works.
* **Issue tracker:** To discuss issues related to the project.
* **Pull requests:** To discuss and review changes that are in progress.
* **Discussion forums:** Some projects may use these channels for more conversational topics instead of bug reports or feature requests.
* **real-time chats:** Such as Discord or IRC for casual conversation, quick exchanges, collaboration and organisation.
