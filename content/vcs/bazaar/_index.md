+++
title = "GNU Bazaar"
type = "chapter"
+++

GNU Bazaar (formerly Bazaar-NG, command line tool bzr) is a distributed and client–server revision control
system sponsored by Canonical.

Bazaar can be used by a single developer working on multiple branches of local content, or by teams
collaborating across a network.

Bazaar is written in the Python programming language, with packages for major Linux distributions, Mac OS X
and Microsoft Windows. Bazaar is free software and part of the GNU Project.

Bazaar commands are similar to those found in CVS or Subversion. A new project can be started and maintained
without a remote repository server by invoking `bzr init` in a directory which a person wishes to version.

In contrast to purely distributed version control systems which do not use a central server, Bazaar supports
working with or without a central server. It is possible to use both methods at the same time with the same project.
The websites Launchpad and SourceForge provide free hosting service for projects managed with Bazaar.

Bazaar has support for working with some other revision control systems. This allows users to branch from another
system (such as Subversion), make local changes and commit them into a Bazaar branch, and then later merge them
back into the other system. Read-only access is also available for Git and Mercurial. Bazaar also allows for
interoperation with many other systems (including CVS, Darcs, Git, Perforce, Mercurial) by allowing one to
import/export the history.

Bazaar supports files with names from the complete Unicode set. It also allows commit messages,
committer names, etc. to be in Unicode.
