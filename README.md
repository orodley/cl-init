Initialize a new CL project.

Includes:

* A new directory for the project
* A package.lisp file containing a package definition
* A src/ subdirectory
* ASDF system
  * Including the package.lisp file
  * A "src" module depending on package.lisp
  * A description, which the user enters
* A new git repository
  * A .gitignore ignoring "*.fasl" files
  * Lines in .git/info/exclude to ignore editor files
  * An initial commit containing all the aforementioned files
Initialize a new CL project.
