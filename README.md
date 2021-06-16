# Git commit template

Git commit template to improve your project's commit messages.

If you want to learn why we use this kind of template,
see our repo [How to write a great git commit message](https://github.com/joelparkerhenderson/git-commit-message).

If you want to improve your git speed and capabilities,
see our project [GitAlias](https://github.com/gitalias/gitalias).


## Template

```sh
Add your title here

# See links to relevant web pages, issue trackers, blog articles, etc.
See: https://example.com/
See: [Example Page](https://example.com/)

# List any authors, so version control systems can connect teams.
Co-authored-by: Name <name@example.com>
Co-authored-by: Name <name@example.com>

# List any sponsors, so contact relation systems can connect groups.
Sponsored-by: Name <name@example.com>
Sponsored-by: Name <name@example.com>

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
# ## About ##
#
# This is our team's starting point for our git commit messages.
# You can edit this template as you like, to customize it.
#
# For more information about git commit ideas and help:
# https://github.com/joelparkerhenderson/git_commit_message
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
```

## Usage

Put the template file here:

     ~/.git-commit-template.txt

Configure git to use the template file by running:

     git config --global commit.template ~/.git-commit-template.txt

Add the template file to our ~/.gitconfig file:

    [commit]
      template = ~/.git-commit-template.txt

If you prefer other file locations or ways of working,
you can freely adjust the usage as you like.
