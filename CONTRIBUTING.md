# Contribution Guidelines

Thanks for your interest in contributing!  This page summarizes important guidelines for _how_ to contribute to maximize the value of your work to the community.  If you are developing code, following these guidelines will provide the best chances that your work will be approved and added to the codebase.


## Contribution Standards
Regardless how you contribute, you are expected to at minimum adhere to the following guidelines:
- **Follow the Code of Conduct**: A link to the code of conduct can be found on the home page of the repository.  This document defines basic standards for ethical and inclusive behavior.
- **Prioritize Standards**: Ideally, all contributors should function as a united team and produce a single, coherent result.  Follow all code style guidelines.  Use the conventions of the repository/project, not your own.
- **Prioritize Security and Privacy**: Modifications should **NEVER** compromise users' security or privacy.  Users who intentionally submit insecure code will be reported to GitHub and permanently banned.  If you are concerned about the potential security implications of a change you propose in your fork, make a note of it in the pull request.
- **Document Your Work**: Whenever making changes to code, you must **ALWAYS** thoroughly document your work.  Where applicable, when making code changes you **MUST** update documentation to explain to users how the new features work.  Documentation should clearly and in detail explain the theory behind your work, and reviewers should know what you did, why you did it, and conceptually how it is implemented without having to look at your code.
- **Open an Issue or Discussion First**: Not all repositories accept external contributions, and in some cases, maintainers may not want to implement certain changes for various reasons.  To ensure your efforts have the greatest chance of being approved, **ALWAYS** open a GitHub issue or discussion **BEFORE** forking a repository and writing code.
- **If You Have a Question, Ask**: Take a few minutes to look through the repository's issues and discussions and to do a Google search before posting, but if you have a question, ask it.  No matter how simple, you are always invited to ask.  On the other side of this, it is NEVER acceptable to criticize someone for asking an honest question.

In addition, there are several expectations for use of Git to manage projects:
- **Small Commits**: Every commit should be a single, logical, coherent change to the code.  In most cases, a single commit should not change more than 100 lines.
- **Descriptive Commit Messages**: EVERY commit message should be descriptive and explain exactly what was changed and why.
- **Single Change Per Pull Request**: Pull requests should implement a single, coherent modification.  Do not "bundle" unrelated modifications in a single pull request; separate them into multiple pull requests.

**Failure to adhere to any of the stated expectations may result in automatic rejection of your proposed contributions.**  It is of high priority to maintain high-quality code, as free as possible of "junk" or poorly-documented content.  In other words, it doesn't matter if your code is a brilliant addition; if it doesn't follow the above standards or will otherwise lower the overall quality of the repository, it will be rejected.  However, if this happens, you are encouraged to revise/redo and resubmit your work.


## Ways to Contribute

### :lock: Security Concerns
**If you identify a security-related issue, do NOT open a GitHub issue, pull request, or discussion to report it.**  These are publicly visible and may pose a risk to other users.

Instead, follow the instructions in the repository Security Policy (linked on the "Security" tab) to report the concern.

### :pencil2: Issues
If you notice a non-security bug, think of a cool new feature, or otherwise identify something that could be improved, create an issue!

Guidelines for submitting issues:
- Always follow the issue template
- Fill out all fields.  If you aren't sure about a particular item, provide as much information as you can and post any follow-up questions as a comment on the issue
- Bug reports
  - Include error messages, logs, and any other important debugging details
  - Describe in detail the steps needed to reproduce the issue
  - If possible, include the software version or commit SHA of the code you are using
  - List relevant system properties (operating system, Python version, etc.)
- Feature requests
  - Describe the motivation for adding the feature.  What problems are you facing?  What benefits will the feature bring for other users?
  - Include links to similar features or implementations in other projects

### :speech_balloon: Discussion
GitHub Discussions are a great way to ask questions, brainstorm ideas, and share cool ways you've used the code in a repository, in a less formal format than an issue or pull request.

Anyone is welcome to ask questions or post in repository discussions on GitHub.  Features and instructions can be found in the official [GitHub documentation](https://docs.github.com/en/discussions/collaborating-with-your-community-using-discussions/about-discussions).

### :trident: Fork and Pull Request
If you have a great idea and know how to implement it, a potential way to contribute is to [fork the repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo), implement the feature, and [open a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork).

**ALWAYS open an issue or discussion BEFORE forking a repository and implementing features.**  There are several reasons for doing so:
- Not all repositories accept external contributions
- It is ultimately the decision of the repository maintainers which features they want to include.  Opening an issue or discussion first will allow maintainers to clarify their plans and ensure your work is considered

### :mag: Review Code
You are always welcome to look through open pull requests, issues, and discussions and add comments.  This is a great way to gain familiarity with the code and to get involved with the project's community.
