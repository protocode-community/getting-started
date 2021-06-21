# Commits
A commit simply is a collection of information around your changes, a message about how you got there, and the commits info that came before it. The changes don't even have to be code, it is just anything you want to add to the repository.

Think of a commit message as a note to your future self: it should give a hint on the intention for changing those files.

# There's no place like 'origin/main'
Knowing where we are in a Git project starts with thinking of a tree. All Git projects have a root, similar to the idea of a filesystem's root directory. All commits branch off from that root. In this way, a branch is only a pointer to a commit. By convention, master is the default name for the default branch in your root directory.

The term "repository" is used as a way of talking about all copies of the same project. There is the local repository, where you edit your code, and the remote repository, the place where you want to send it. Remotes can be anywhere, but they are often hosted on repository services like GitLab or GitHub.

# Where do we come from where do we go?
Being lost is part of the fun of a Git repository. We can find our way by running through this set of commands:

```
git branch—to find which branch you're on

git log—to see what commit you're on

git status—to see what edits you've made since the last commit

git remote—to see what remote repository you're tracking
```

These commands will give you a sense of direction when you're stuck.
