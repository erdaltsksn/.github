# Contributing

This document contains a set of guidelines to help you during the contribution
process. We are happy to welcome all contributions from anyone willing to
improve this project. Thank you for helping out and remember, no contribution is
too small.

## Step By Step Contribution Guide

01. **Open** an issue before working on your changes
02. **Install** the prerequisites
03. **Create** a git branch and **start working** on your fix, feature, etc on
    **its branch**
04. **Add** and **run** the **tests**
05. **Add** or **update** the **documentation**
06. **Commit** your changes according to [Commit Message Guidelines](#commit-message-guidelines)
07. **Push** your changes and **create** a **Pull Request** for review
08. **Communicate** with the maintainer about the revisions
09. **Be responsive** if someone request changes for your contributions
10. Your contribution gets accepted. 🎉🎉🎉

**NOTE:** Be sure to get the latest from "**upstream**" before making a pull
request!

## Commit Message Guidelines

We have strict rules over how our **git commit messages** can be formatted. This
leads to **more readable messages** that are easy to follow when looking through
the **project history**. Fortunately, there are well-established conventions as
to what makes an idiomatic Git commit message. Indeed, many of them are assumed
in the way certain Git commands function. There’s nothing you need to re-invent.
Just follow the seven rules below.

01. Separate subject from body with a blank line
02. Limit the subject line to 50 characters
03. Capitalize the subject line
04. Do not end the subject line with a period
05. Use the imperative mood in the subject line
06. Wrap the body at 72 characters
07. Use the body to explain what and why vs. how

### Template

Each commit message consists of a **header**, a **body**, and a **footer**.
Do not forget to separate each area with a blank line.

```html
<type>: <subject>

<body>

<footer>
```

`<type>` must be one of the following.

```html
fix:  Fix an issue e.g. bug, code typo, accident, misstatement
feat: < Add | Delete | Update > a feature
redo: Changes neither fix a bug nor add a feature (refactor)
test: < Add | Delete | Update > a test
docs: < Add | Delete | Update > documentation
chor: < Bump | Downgrade > {pkg} to , Run {task}
tidy: Style e.g. indent, space, layout, etc.
```

`<subject>` should always be able to complete the following sentence:
*If applied, this commit will ...*

```html
- If applied, this commit will refactor subsystem X for readability
- If applied, this commit will update getting started documentation
- If applied, this commit will remove deprecated methods
- If applied, this commit will release version 1.0.0
- If applied, this commit will merge pull request #123 from user/branch
````

`<body>`

```html
More detailed explanatory text, if necessary. Wrap it to about 72 characters. In
some contexts, the first line is treated as the subject of an email and the rest
of the text as the body. The blank line separating the summary from the body is
critical (unless you omit the body entirely); tools like rebase can get confused
if you run the two together.

In most cases, you can leave out details about how a change has been made. Code
is generally self-explanatory in this regard (and if the code is so complex that
it needs to be explained in prose, that’s what source comments are for).

Just focus on making clear the reasons why you made the change in the first
place—the way things worked before the change (and what was wrong with that),
the way they work now, and why you decided to solve it the way you did.
```

`<footer>` can contain information about breaking changes and deprecations and
is also the place to reference GitHub issues, Trello tickets, and other PRs that
this commit closes or is related to.

```html
iss: < close | reopen > #124
PRs: #123 (Pull Request)
ref: a5c3785 (Commit)
     repo-name@a5c3785 (Commit from another repository)
see: Links to external resources, articles, or Trello tickets

BREAKING CHANGE: followed by a summary of the breaking change, a blank line,
                 and a detailed description of the breaking change that also 
                 includes migration instructions.
DEPRECATED:      followed by a short description of what is deprecated, a blank
                 line, and a detailed description of the deprecation that also 
                 mentions the recommended update path.
```

### Revert and Merge

Use default GIT templates for `revert` and `merge`.

## Issues

Before creating a new issue, please search for similar issues, open or closed,
to see if someone else has already noticed the same problem and possible
solutions.

Do not comment on open issues unless you can provide more information to resolve
them. Use the subscribe function to keep up-to-date with the issue or the voting
system to support it.

### Bug reports

When you can't find a previous bug, open an issue keeping in mind the following
considerations:

- Try to reproduce the bug using the code found on the `main` branch
- Copy and paste the full error message, including the `backtrace`
- Be as detailed as possible and include any additional information

### Feature requests

If you want to request or implement a new feature please submit an issue
describing the details and possible use cases.

## Thanks

Thank you to all who have contributed to this great project.
