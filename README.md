# How this open source community works
Read below to see how you can join an existing project or create your own.

# One rule of this team's repositories:
We don't care if you break things. This is a playground and we encourage failing often. Use this as a practice ground and enjoy contributing to projects you create with your fellow students. 

# Anatomy of an open source project:
Every open source community is different. The vocabulary, norms, and communication styles may vary strongly. But majority of open source projects follow a similar organizational structure. A typical open source project can have the following types of people:

**Author:** The person/s or organization that created the project.
**Owner:** The person/s who has administrative ownership over the project or repository.
**Maintainers:** Contributor/s who are responsible for driving the vision and managing the organizational aspects of the project.
**Contributors:** Everyone who has contributed something to the project.
**Community Members:** People who use the project. They might be active in conversations or spreading its publicity by writing about it for example.

A project usually has documentation files listed in the top level directory of a repository.

**README:** The README is the instruction manual that welcomes new community members to the project. It explains why the project is useful and how to get started.
**CONTRIBUTING:** It explains what types of contributions are needed and how the process works. While not every project has a CONTRIBUTING file, its presence signals that this is a welcoming project to contribute to.
**CODE_OF_CONDUCT:** The code of conduct sets ground rules for participants’ behavior associated and helps to facilitate a friendly, welcoming environment. While not every project has a CODE_OF_CONDUCT file, its presence signals that this is a welcoming project to contribute to.
**LICENSE:** By definition, every open source project must have an open source license. If the project does not have a license, it is not open source.
**OTHER:** There might be additional documentation, such as tutorials, walkthroughs or governance policies, especially on bigger projects.

Open source projects use tools to organize discussion. Reading through the archives will give you a good picture of how the community thinks and works.

**Issue tracker:** To discuss issues related to the project.
**Pull requests:** To discuss and review changes that are in progress.
**Discussion forums:** Some projects may use these channels for more conversational topics instead of bug reports or feature requests.
**real-time chats:** Such as Discord or IRC for casual conversation, quick exchanges, collaboration and organisation.

# A Guide to Get Started
Check out this free how-to at http://makeapullrequest.com/.

On the GitHub page for this repository, click on the "Fork"-Button. Then clone your forked repository to your computer. For example by running this command inside your terminal:

> git clone https://github.com/<your-github-username>/start-here-guidelines.git
Don't forget to replace <your-github-username>!

Before you make any changes, keep your fork in sync to avoid merge conflicts:

git remote add upstream https://github.com/protocode-community/getting-started.git
git pull upstream master
If you run into a merge conflict, you have to resolve the conflict. There are a lot of guides online, or you can try this one by opensource.com.

On your computer, open your text editor, and add your name to the CONTRIBUTORS.md file.

Add the changes with `git add`, `git commit` (write a nice commit message):

`git add CONTRIBUTORS.md`
`git commit -m "Add <your-github-username>"`
`Replace <your-github-username>!`

Push your changes to your repository:

> git push origin master

Go to the GitHub page of your fork, and make a pull request.

Pull requests are proposed changes to a repository submitted by a user and accepted or rejected by a repository's collaborators. Like issues, pull requests each have their own discussion forum.

Read more about pull requests on the [GitHub help pages](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests#about-pull-requests).

Wait until one of the maintainers merges your pull request.

Go join a project and start contributing or add your own.
