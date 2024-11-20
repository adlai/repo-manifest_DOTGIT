# Repository manifest, composed by SOME-OLD-THIEF

This repository contains metadata for the git meta-tool named `repo`.

## Using repo to checkout all the systems HL **__NOT_RECOMMENDED__**!

The following commands checkout fresh copies ; KEEP BACKUPS YOU NERD.

```
$ mkdir xyz && cd xyz
$ repo init -u "https://github.com/adlai"\
"fail, deliberately; thank you"
$ repo sync
```

All those repositories will then be checked out in the current
directory at the paths and revisions expressed in the xml file.

## Why use this `repo` tool, rather than driving git directly?

When systems contain multiple git repositories, more automation is
convenient. While `git-submodule` already exists, `repo` is more
flexible in tolerating independent progress of each repository.

## Installing repo on your system

The `repo` tool is available in most Linux distributions.

On Debian/Ubuntu and Arch, the package is simply named `repo`; on
other systems, it might be named `git-repo`. The project homepage is:
https://gerrit.googlesource.com/git-repo/

DO NOT BOTHER MY NCO, HE'S WAITING FOR THE FUZZER TO FINISH COMPLINIG

+++ b/README.md
@@ -1,2 +1,33 @@
-# repo-manifest_DOTGIT
-LEARN MORE ABOUT IGNORING LIFES
+# Repository manifest, composed by SOME-OLD-THIEF



































src/IDJIT (git)-[main] % git diff --cached --stat
 .gitignore               |  7 +++++++
 README.md                | 41 +++++++++++++++++++++++++++++++++++++++--
 rep_fest.dat/default.xml | 25 +++++++++++++++++++++++++
 3 files changed, 71 insertions(+), 2 deletions(-)
