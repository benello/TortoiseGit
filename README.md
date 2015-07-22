TortoiseGit - The coolest Interface to Git Version Control
==========================================================

TortoiseGit is a Windows Shell Interface to Git and based on TortoiseSVN. It's open source and can fully be build with freely available software.

TortoiseGit supports you by regular tasks, such as committing, showing logs, diffing two versions, creating branches and tags, creating patches and so on (see our [Screenshots](https://code.google.com/p/tortoisegit/wiki/Screenshots) or [documentation](https://tortoisegit.org/docs/tortoisegit/)).

* Website: [tortoisegit.org](https://tortoisegit.org)
* Download: [tortoisegit.org/download](https://tortoisegit.org/download)
* Manual: [tortoisegit.org/docs/tortoisegit/](https://tortoisegit.org/docs/tortoisegit/)
* Issue tracker: [tortoisegit.org/issues](https://tortoisegit.org/issues)
* Mailing lists: [tortoisegit-announce](https://groups.google.com/group/tortoisegit-announce),
                 [tortoisegit-users](https://groups.google.com/group/tortoisegit-users) and
                 [tortoisegit-dev](https://groups.google.com/group/tortoisegit-dev)
* StackOverflow tag: [tortoisegit](http://stackoverflow.com/questions/tagged/tortoisegit)

Download
--------

The latest release and language packs are available on the [download page](https://tortoisegit.org/download). There you also find the system requirements and latest release notes.

The TortoiseGit team also provides [preview releases](https://download.tortoisegit.org/tgit/previews/) on an irregular basis. These versions are used by the TortoiseGit developers and are built from the latest code that represents 
the cutting edge of the TortoiseGit development.

What to do if things go wrong or a crash happened?
--------------------------------------------------

Before reporting an issue, please search whether a similar issue already exists and check that your problem isn't fixed in our latest [preview release](https://download.tortoisegit.org/tgit/previews/).

An important aspect of reporting issues it to have a reproducible way for the issue and also to mention your exact version of your operating system, the version of Git and the version of TortoiseGit (this information can be found on the TortoiseGit about dialog).

TortoiseGit includes a crash reporter (if not disabled on installation), which automatically uploads crash dumps to drdump.com, where the TortoiseGit team can review them. If you have a reproducible way, please also file an issue and link the crash report.

We have a special page describing [steps for debugging](src/Debug-Hints.txt), where the majority of ways does not require to build TortoiseGit on your own.

How Can I Contribute?
=====================

You're welcome to contribute to this project! There are several aspects you can help on:

* improving our [documentation](https://tortoisegit.org/docs/tortoisegit/) (see [doc/readme.txt](doc/readme.txt) file and [doc](doc) folder),
* [translations](Languages/README.txt),
* testing [preview releases](https://download.tortoisegit.org/tgit/previews/),
* helping other users on the mailing lists,
* improving our UIs, or also
* coding (e.g., fix open issues or implement new features; see below for more information).

Any help is appreciated!

Feel free to report issues and open merge requests.

Please also check the [contribution guidelines](doc/HowToContribute.txt) to understand our
workflow.

How to build
------------

Building TortoiseGit normally is not necessary, however, it is easy. All necessary requirements and steps are described in the [build.txt](build.txt) file. Helpful might also be our short description in the [architecture.txt](architecture.txt) file.

License
=======

TortoiseGit is licensed under the [GPLv2](src/gpl.txt).

