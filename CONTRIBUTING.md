# Contributing to the NGINX Kubernetes Ingress Controller

:+1::tada: Thanks for thinking of contributing! :tada::+1:

The following is a set of guidelines for contributing to the NGINX Kubernetes Ingress Controller.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[I just want to ask a question](#asking-questions)

[What should I know before I get started?](#what-should-i-know-before-i-get-started)

[How Can I Contribute?](#how-can-i-contribute)

[Styleguides](#styleguides)
  * [Git Commit Messages](#git-commit-messages)
  * [Go Styleguide](#go-styleguide)

## Asking questions

> **Note:** Please don't file an issue to ask a question

We will have a public forum soon where you can come and ask questions and have a discussion

## What should I know before I get started?

Follow our [Installation Guide](https://github.com/nginxinc/kubernetes-ingress/blob/master/docs/installation.md) to get the NGINX Kubernetes Ingress Controller up and running.

There are also docs available for
* [CLI arguments](https://github.com/nginxinc/kubernetes-ingress/blob/master/docs/cli-arguments.md)
* [Difference between this and the Kubernetes Community Ingress Controller](https://github.com/nginxinc/kubernetes-ingress/blob/master/docs/nginx-ingress-controllers.md)

### Package Conventions

* This Ingress Controller supports both NGINX Open Source and NGINX Plus (our commercial product).
    * The main code is found under `/nginx-controller/main.go`
* Dependencies
    * Dependencies are found under `/vendor` at the project root
    * Please ensure you add new dependencies here using [glide](https://github.com/Masterminds/glide)

## How Can I Contribute?

### Reporting Bugs

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/) and available on the [issues part of our repository](https://github.com/nginxinc/kubernetes-ingress/issues). After you confirmed the bug has not already been reported, then create an issue following the instructions in [our issue template](https://github.com/nginxinc/kubernetes-ingress/blob/master/.github/ISSUE_TEMPLATE.md).

Remember - the more information the better!

### Suggesting Enhancements

We also accept feature requests and enhancements.

* For smaller change please open a [Pull Request](#pull-requests) and describe the change in detail there.
* For larger feature requests you can should first raise a feature request using [our issue template](https://github.com/nginxinc/kubernetes-ingress/blob/master/.github/ISSUE_TEMPLATE.md) and specify a feature request type. This can open up a discussion with maintainers and ideally lead to a Pull Request after some short discussion.

### Pull Requests

* Fill in [our pull request template](https://github.com/nginxinc/kubernetes-ingress/blob/master/.github/PULL_REQUEST_TEMPLATE.md)
* Do not include issue numbers in the PR title
* Follow the [Git Commit](#git-commit-messages) style-guide.
* Follow the [Go](#go-styleguide) style-guide.

## Styleguides

### Git Commit Messages

* Keep a clean, concise and meaningful git commit history on your branch, rebasing locally and squashing before submitting a PR
* Follow the guidelines of writing a good commit message as described here https://chris.beams.io/posts/git-commit/ and summarised in the next few points
* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line

### Go Styleguide

* Run `gofmt` over your code to automatically clean up a lot of style issues. Most editors support this on-save now.
* Run `go lint` and `go vet` on your code too to catch any other issues.
* Follow this guide on some good practice and idioms for Go https://github.com/golang/go/wiki/CodeReviewComments

## Code of Conduct

This project and everyone participating in it is governed by this code.

### Our Pledge

In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, sex characteristics, gender identity and expression,
level of experience, education, socio-economic status, nationality, personal
appearance, race, religion, or sexual identity and orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or
  advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic
  address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable
behavior and are expected to take appropriate and fair corrective action in
response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or
reject comments, commits, code, wiki edits, issues, and other contributions
that are not aligned to this Code of Conduct, or to ban temporarily or
permanently any contributor for other behaviors that they deem inappropriate,
threatening, offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces
when an individual is representing the project or its community. Examples of
representing a project or community include using an official project e-mail
address, posting via an official social media account, or acting as an appointed
representative at an online or offline event. Representation of a project may be
further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported by contacting the project team at [mailto:nginx@nginx.org]. All
complaints will be reviewed and investigated and will result in a response that
is deemed necessary and appropriate to the circumstances. The project team is
obligated to maintain confidentiality with regard to the reporter of an incident.
Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good
faith may face temporary or permanent repercussions as determined by other
members of the project's leadership.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4,
available at https://www.contributor-covenant.org/version/1/4/code-of-conduct.html

[homepage]: https://www.contributor-covenant.org
