# Git commit template

Git commit template to improve your project's commit messages.

This commit template has a bunch of information inside,
and it's set up so you can freely edit it as you like.

If you want to learn why we use this kind of template,
see our repo [How to write a great git commit message](https://github.com/joelparkerhenderson/git_commit_message)

If you want to improve your git speed and capabilities,
see our repo  [Git alias configuration for shortcuts and enhancements](https://github.com/gitalias/gitalias)


## Help ##

Subject line imperative uppercase verbs:

  * Add = Create a capability e.g. feature, test, dependency.
  * Drop = Delete a capability e.g. feature, test, dependency.
  * Fix = Fix an issue e.g. bug, typo, accident, misstatement.
  * Bump = Increase the version of something e.g. a dependency.
  * Make = Change the build process, or tools, or infrastructure.
  * Start = Begin doing something; e.g. enable a toggle, feature flag, etc.
  * Stop = End doing something; e.g. disable a toggle, feature flag, etc.
  * Refactor = A change that MUST be just refactoring.
  * Reformat = A change that MUST be just format, e.g. indent line, trim space, etc.
  * Rephrase = A change that MUST be just textual, e.g. edit a comment, doc, etc.
  * Optimize = A change that MUST be just about performance, e.g. speed up code.
  * Document = A change that MUST be only in the documentation, e.g. help files.

For the subject line:
  * Use 50 characters maximum.
  * Do not use a sentence-ending period.

For the body text:
  * Use as many lines as you like.
  * Use 72 characters maximum per line for typical word wrap text.


## Usage ##

Put the template file here:

     ~/.git_commit_template.txt

Configure git to use the template file by running:

     git config --global commit.template ~/.git_commit_template

Add the template file to our ~/.gitconfig file:

    [commit]
      template = ~/.git_commit_template

If you prefer other file locations or ways of working,
you can freely adjust the usage as you like.


## Tracking ##

* Package: git_commit_message
* Version: 6.0.1
* Updated: 2018-08-27T21:33:51Z
* Licence: GNU General Public License (GPL-3.0)
* Contact: Joel Parker Henderson (http://joelparkerhenderson.com)
