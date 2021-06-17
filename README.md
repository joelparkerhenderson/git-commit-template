# Git commit template

<img src="README.png" alt="DataGrip + PostgresSQL" style="width: 100%;"/>

Git commit template to improve your project's commit messages.

If you want to learn why we use this kind of template,
see our repo [How to write a great git commit message](https://github.com/joelparkerhenderson/git-commit-message).

If you want to improve your git speed and capabilities,
see our project [GitAlias](https://github.com/gitalias/gitalias).

The template is below and is also at this link: [git-commit-template.txt](git-commit-template.txt)

## Template

```sh
Add your title here

# First step, see the "Trailers" section at the end of this template.

# Why is this change happening, e.g. goals, use cases, stories, etc.?
Why:

# How is this change happening, e.g. implementations, algorithms, etc.?
How:

# Tags suitable for searching, such as hashtags, keywords, etc.
Tags:

# ## Help ##
#
# Subject line imperative uppercase verbs:
#
#   Add = Create a capability e.g. feature, test, dependency.
#   Drop = Delete a capability e.g. feature, test, dependency.
#   Fix = Fix an issue e.g. bug, typo, accident, misstatement.
#   Bump = Increase the version of something e.g. a dependency.
#   Make = Change the build process, or tools, or infrastructure.
#   Start = Begin doing something; e.g. enable a toggle, feature flag, etc.
#   Stop = End doing something; e.g. disable a toggle, feature flag, etc.
#   Optimize = A change that MUST be just about performance, e.g. speed up code.
#   Document = A change that MUST be only in the documentation, e.g. help files.
#   Refactor = A change that MUST be just refactoring.
#   Reformat = A change that MUST be just format, e.g. indent line, trim space, etc.
#   Rephrase = A change that MUST be just textual, e.g. edit a comment, doc, etc.
#
# For the subject line:
#   * Use 50 characters maximum.
#   * Do not use a sentence-ending period.
#
# For the body text:
#   * Use as many lines as you like.
#   * Use 72 characters maximum per line for typical word wrap text.
#
#
# ## Trailers ##
#
# Trailers suitable for tracking and also for `git interpret-trailers`.
#
# Example of "See:" trailers that mean "see this additional information"
# and links to relevant web pages, issue trackers, blog posts, etc.:
#
#     See: https://example.com/
#     See: Issue #123 <https://example.com/issue/123>
#
# Example of "Co-authored-by:" trailers that list each author's name
# and their preferred commit message email address or contact URL:
#
#     Co-authored-by: Alice Adams <alice@example.com>
#     Co-authored-by: Bob Brown <https://bob.example.com>
#
# Example of "Sponsored-by:" trailers that list each sponsor's name,
# which could be a person's or organization's, and contact email or URL:
#
#     Sponsored-by: Adam Anderson <adam@example.com>
#     Sponsored-by: Bravo Organization <https://bravo.example.com>
#
# The git tools require trailers to be last in a commit message,
# and must be one trailer per line, and with no extra lines between.
#
#
# ## About ##
#
# This is our team's starting point for our git commit messages.
# You can edit this template as you like, to customize it.
#
# For more information about git commit ideas and help:
# https://github.com/joelparkerhenderson/git-commit-message
#
#
# ## Usage ##
#
# Put the template file here:
#
#     ~/.git-commit-template.txt
#
# Configure git to use the template file by running:
#
#     git config --global commit.template ~/.git-commit-template.txt
#
# Add the template file to the ~/.gitconfig file:
#
#     [commit]
#       template = ~/.git-commit-template.txt
#
# If you prefer other file locations or ways of working,
# you can freely adjust the usage as you like.
#
#
# ## Tracking ##
#
# * Package: git-commit-template
# * Version: 7.0.0
# * Updated: 2021-06-16T20:32:18Z
# * Licence: GNU General Public License (GPL-2.0-only)
# * Contact: Joel Parker Henderson (http://joelparkerhenderson.com)

### GIT TRAILERS -- THESE MUST BE LAST IN THE COMMIT MESSAGE ###

See: Description <https://example.com/...>
See: Description <https://example.com/...>
Co-authored-by: Name <name@example.com>
Co-authored-by: Name <name@example.com>
Sponsored-by: Name <name@example.com>
Sponsored-by: Name <name@example.com>
```
