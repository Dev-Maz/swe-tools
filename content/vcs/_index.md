+++
title = "Version Control System"
type = "chapter"
+++

Version control (also known as revision control, source control, and source code management) is the software
engineering practice of controlling, organizing, and tracking different versions in history of computer files;
primarily source code text files, but generally any type of file.

Version control is a component of software configuration management.

A version control system is a software tool that automates version control. Alternatively, version control
is embedded as a feature of some systems such as word processors, spreadsheets, collaborative web docs, and
content management systems, e.g., Wikipedia's page history.

Version control includes viewing old versions and enables reverting a file to a previous version.

As teams develop software, it is common for multiple versions of the same software to be deployed in different
sites and for the developers to work simultaneously on updates. Bugs or features of the software are often
only present in certain versions (because of the fixing of some problems and the introduction of others
as the program develops). Therefore, for the purposes of locating and fixing bugs, it is vitally important to be able
to retrieve and run different versions of the software to determine in which version(s) the problem occurs.
It may also be necessary to develop two versions of the software concurrently: for instance, where one version
has bugs fixed, but no new features (branch), while the other version is where new features are worked on (trunk).

At the simplest level, developers could simply retain multiple copies of the different versions of the program,
and label them appropriately. This simple approach has been used in many large software projects. While this method
can work, it is inefficient as many near-identical copies of the program have to be maintained. This requires a lot
of self-discipline on the part of developers and often leads to mistakes. Since the code base is the same,
it also requires granting read-write-execute permission to a set of developers, and this adds the pressure of
someone managing permissions so that the code base is not compromised, which adds more complexity. Consequently,
systems to automate some or all of the revision control process have been developed. This ensures that the majority
of management of version control steps is hidden behind the scenes.

Moreover, in software development, legal and business practice, and other environments, it has become increasingly
common for a single document or snippet of code to be edited by a team, the members of which may be geographically 
dispersed and may pursue different and even contrary interests. Sophisticated revision control that tracks and
accounts for ownership of changes to documents and code may be extremely helpful or even indispensable
in such situations.

Revision control may also track changes to configuration files, such as those typically stored in `/etc` or 
`/usr/local/etc` on Unix systems. This gives system administrators another way to easily track changes made 
and a way to roll back to earlier versions should the need arise.

Many version control systems identify the version of a file as a number or letter, called the version number,
version, revision number, revision, or revision level. For example, the first version of a file might be 
version 1. When the file is changed the next version is 2. Each version is associated with a timestamp and the
person making the change. Revisions can be compared, restored, and, with some types of files, merged.
