# Moderating Development Contributions

**Reminder:** Please read the current [Utopian Rules](https://utopian.io/rules) first, to bring yourself up to date.

The [Development](https://utopian.io/development/review) category is very formal and the quality and added value of the actual programming work is the important factor. New projects must have a unique character. Textbook examples and generic scripts, that already exist in big numbers, can't be approved. Contributions to existing projects must be merged, and thereby veryfied by the project maintainer, before submitting them on Utopian. Submitted code should always meet modern quality standards if applicable. As a moderator you need a decent understanding of such standards and techniques, that are commonly used in modern software projects.

There are two ways of contributing in the development category. One is to contribute to other projects, in the form of bug fixes and new features. The other is to share your own (actively maintained!) projects with the open source community and to invite others to participate (See [Development Task Requests](https://github.com/utopian-io/moderation-guidelines/tree/master/task-requests/development.md)). Therefore we will split this guide into **Projects** and **Contributions**.

## Projects

It's important at this point, to give a clear definition of what Utopian accepts as a valid open source project and what not. 

Open source is about collaboration on public domain projects. Therefore such projects must include sufficient details about how the software works and how to participate in the project. The repository on GitHub must contain a *README.md* with all this information or links to it.

> **About READMEs (and other good practices to present a project):**
> **https://help.github.com/articles/about-readmes/**

> **Example README.md (busy.org)**
> **https://github.com/busyorg/busy/blob/master/README.md**

This also excludes projects that are not really meant to be used by a wider audience or are to trivial and redundant. Simple scripts and alike, that don't have a any realistic chance to be of some value to others, can't be accepted. There are no specific metrics to make this decision based upon but some cases are very obvious (e.g. tools like image resizers or currency converters), others might need to be discussed.

### Proof Of Work

Evaluating the amount of work that went into a contribution can be tricky, because projects can contain numerous files of different types and formats and of course it's recommended to reuse code and outsource large parts of the work to existing third party libraries. Of course those parts can't be taken into account when evaluating the contribution. In fact there are some common rules and best practices to follow, when working with third party software.

If possible, it shouldn't be directly included in the project. ...

...

## Contributions

## Checklist

- [ ] What did the user contribute before?
- [ ] Is it a new project, started by the user?
  - [ ] Does it provide some unique features/added value?
  - [ ] Is there a valid (open source) [LICENSE file](https://help.github.com/articles/adding-a-license-to-a-repository/)?
  - [ ] Is there a descriptive README file with instructions?
- [ ] Is it a contribution to someone else's project?
  - [ ] Is the repository correct?
  - [ ] Was there any activity withing the past year?
  - [ ] Is the Pull Request already merged?
  - [ ] Was it merged within the past 30 days?
- [ ] Are code samples correctly [formatted](https://help.github.com/articles/creating-and-highlighting-code-blocks/) or [linked](https://help.github.com/articles/creating-a-permanent-link-to-a-code-snippet/)?
- [ ] Is the contributed code well formatted and contains descriptive comments?
- [ ] Does the code contain any obviously deprecated or dangerous parts?
- [ ] ...
- [ ] ...
- [ ] ...

## Good Examples

- https://utopian.io/utopian-io/@netuoso/condenser-fix-body-length-check-on-post-and-comment
- https://utopian.io/utopian-io/@stoodkev/fixed-3-issues-caused-by-changes-on-steemit-layout-feed-fixed
- https://utopian.io/utopian-io/@samrg472/refactoring-and-cleaning-the-utopian-api-part-2
- ...
- ...
- ...


## Comment Examples

**Use only as inspiration!**

### Old project uploaded to GitHub

Your contribution cannot be approved. We cannot evaluate a development contribution, if there's no public history, such as that on GitHub, for open source projects, that were meant to be open source right from the beginning. Many users simply upload their old projects to GitHub, just to have the "Open Source" label, to get a reward. On Utopian we want actively maintained and promising Open Source projects and no outdated private projects. Simply uploading files to GitHub is not the way to go. You need to carefully prepare your project and provide information for others, both users and developers, to participate. The project should be up-to-date and documented and the development should happen in an organized and transparent manner, using Git/GitHub, to qualify as an open source project on Utopian.

For questions and feedback you can contact us on \[Discord](https://discord.gg/uTyJkNm).

\**\[[utopian-moderator]](https://utopian.io/moderators)**

<hr>

### Textbook example with common quality issues

Your contribution cannot be approved because it does not follow the \[Utopian Rules](https://utopian.io/rules).

\> Simple and common code snippets can't be submitted in the development category.

Your project is too simple and has more the character of a textbook example. This kind of projects can't be accepted on Utopian. Also there are some issues with the quality of your GitHub repository.

\- Your \[README.md](https://github.com/...) is not very well formatted.<br>
\- The directory \`node_modules\` doesn't belong into the repository. These are third-party dependencies, that should be installed via a package manager, most likely \[npm](https://www.npmjs.com/).<br>
\- You uploaded the whole project to GitHub in one single commit. This makes it hard to evaluate the history of the project and the actual work that has been done. It's also not the way Git/GitHub are intended to be used.<br>
 
Please only submit projects of decent quality, that you want to actively maintain and develop. Instead you can also try to contribute to other, more established projects.
 
For questions and feedback you can contact us on \[Discord](https://discord.gg/uTyJkNm).
 
\**\[[utopian-moderator]](https://utopian.io/moderators)**

<hr>

## Notes

- plagiarism, search asset files for foreign authors
- check the commits, "Added files via upload" makes it hard to evaluate the development.
- posts should contain more description then code snippets...
