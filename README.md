# test
test
Microsoft Windows [Versión 10.0.26200.7922]
(c) Microsoft Corporation. Todos los derechos reservados.

C:\Users\Joan>git
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   restore    Restore working tree files
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   diff       Show changes between commits, commit and working tree, etc
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   backfill   Download missing objects in a partial clone
   branch     List, create, or delete branches
   commit     Record changes to the repository
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   reset      Set `HEAD` or the index to a known state
   switch     Switch branches
   tag        Create, list, delete or verify tags

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

C:\Users\Joan>git clone
fatal: You must specify a repository to clone.

usage: git clone [<options>] [--] <repo> [<dir>]

    -v, --[no-]verbose    be more verbose
    -q, --[no-]quiet      be more quiet
    --[no-]progress       force progress reporting
    --[no-]reject-shallow don't clone shallow repository
    -n, --no-checkout     don't create a checkout
    --checkout            opposite of --no-checkout
    --[no-]bare           create a bare repository
    --[no-]mirror         create a mirror repository (implies --bare)
    -l, --[no-]local      to clone from a local repository
    --no-hardlinks        don't use local hardlinks, always copy
    --hardlinks           opposite of --no-hardlinks
    -s, --[no-]shared     setup as shared repository
    --[no-]recurse-submodules[=<pathspec>]
                          initialize submodules in the clone
    --[no-]recursive ...  alias of --recurse-submodules
    -j, --[no-]jobs <n>   number of submodules cloned in parallel
    --[no-]template <template-directory>
                          directory from which templates will be used
    --[no-]reference <repo>
                          reference repository
    --[no-]reference-if-able <repo>
                          reference repository
    --[no-]dissociate     use --reference only while cloning
    -o, --[no-]origin <name>
                          use <name> instead of 'origin' to track upstream
    -b, --[no-]branch <branch>
                          checkout <branch> instead of the remote's HEAD
    --[no-]revision <rev> clone single revision <rev> and check out
    -u, --[no-]upload-pack <path>
                          path to git-upload-pack on the remote
    --[no-]depth <depth>  create a shallow clone of that depth
    --[no-]shallow-since <time>
                          create a shallow clone since a specific time
    --[no-]shallow-exclude <ref>
                          deepen history of shallow clone, excluding ref
    --[no-]single-branch  clone only one branch, HEAD or --branch
    --[no-]tags           clone tags, and make later fetches not to follow them
    --[no-]shallow-submodules
                          any cloned submodules will be shallow
    --[no-]separate-git-dir <gitdir>
                          separate git dir from working tree
    --[no-]ref-format <format>
                          specify the reference format to use
    -c, --[no-]config <key=value>
                          set config inside the new repository
    --[no-]server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --[no-]filter <args>  object filtering
    --[no-]also-filter-submodules
                          apply partial clone filters to submodules
    --[no-]remote-submodules
                          any cloned submodules will use their remote-tracking branch
    --[no-]sparse         initialize sparse-checkout file to include only files at root
    --[no-]bundle-uri <uri>
                          a URI for downloading bundles before fetching from origin remote


C:\Users\Joan>git clone https://github.com/joan48011/test.git
Cloning into 'test'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.

C:\Users\Joan>dir
 El volumen de la unidad C no tiene etiqueta.
 El número de serie del volumen es: 509B-A159

 Directorio de C:\Users\Joan

02/03/2026  16:26    <DIR>          .
11/12/2024  13:29    <DIR>          ..
05/07/2024  11:03    <DIR>          .afirma
27/09/2023  15:43    <DIR>          3D Objects
27/09/2023  15:43    <DIR>          AppMods
16/10/2023  19:20            94.532 battery-report.html
11/12/2024  14:25    <DIR>          Contacts
01/03/2026  21:45    <DIR>          Desktop
20/11/2025  23:09    <DIR>          Documents
01/03/2026  21:45    <DIR>          Downloads
11/12/2024  14:25    <DIR>          Favorites
11/12/2024  14:25    <DIR>          Links
11/12/2024  14:25    <DIR>          Music
02/03/2026  15:51    <DIR>          OneDrive
31/12/2025  13:23    <DIR>          Pictures
27/09/2023  15:43    <DIR>          Recorded Calls
11/12/2024  14:25    <DIR>          Saved Games
25/02/2025  09:28    <DIR>          Searches
02/03/2026  16:26    <DIR>          test
01/12/2025  19:40    <DIR>          Videos
               1 archivos         94.532 bytes
              19 dirs  276.638.912.512 bytes libres

C:\Users\Joan>cd test

C:\Users\Joan\test>dir
 El volumen de la unidad C no tiene etiqueta.
 El número de serie del volumen es: 509B-A159

 Directorio de C:\Users\Joan\test

02/03/2026  16:26    <DIR>          .
02/03/2026  16:26    <DIR>          ..
02/03/2026  16:26                14 README.md
               1 archivos             14 bytes
               2 dirs  276.638.846.976 bytes libres

C:\Users\Joan\test>echo README.md
README.md

C:\Users\Joan\test>type README.md
# test
test

C:\Users\Joan\test>KICAD
"KICAD" no se reconoce como un comando interno o externo,
programa o archivo por lotes ejecutable.

C:\Users\Joan\test>git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Prueba.kicad_pcb
        Prueba.kicad_prl
        Prueba.kicad_pro
        Prueba.kicad_sch

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\Joan\test>git add .
warning: in the working copy of 'Prueba.kicad_pcb', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Prueba.kicad_prl', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'Prueba.kicad_pro', LF will be replaced by CRLF the next time Git touches it

C:\Users\Joan\test>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Prueba.kicad_pcb
        new file:   Prueba.kicad_prl
        new file:   Prueba.kicad_pro
        new file:   Prueba.kicad_sch


C:\Users\Joan\test>git commid
git: 'commid' is not a git command. See 'git --help'.

The most similar command is
        commit

C:\Users\Joan\test>git commit -m "Este es mi primer commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Joan@JoanPc.(none)')

C:\Users\Joan\test> git config --global user.email "you@example.com"

C:\Users\Joan\test> git config --global user.email "jcorraltarraga@gmail.com"

C:\Users\Joan\test> git config --global user.name "joan48011"

C:\Users\Joan\test>git commit -m "Este es mi primer commit"
[main c22f4a4] Este es mi primer commit
 4 files changed, 532 insertions(+)
 create mode 100644 Prueba.kicad_pcb
 create mode 100644 Prueba.kicad_prl
 create mode 100644 Prueba.kicad_pro
 create mode 100644 Prueba.kicad_sch

C:\Users\Joan\test>git push
info: please complete authentication in your browser...
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 3.15 KiB | 1.58 MiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/joan48011/test.git
   c20c0f9..c22f4a4  main -> main

C:\Users\Joan\test>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Prueba.kicad_pro
        modified:   Prueba.kicad_sch

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Prueba-backups/

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\Joan\test>git add .
warning: in the working copy of 'Prueba.kicad_pro', LF will be replaced by CRLF the next time Git touches it

C:\Users\Joan\test>git commit -m "Prueba de gusrdado"
[main ed311ee] Prueba de gusrdado
 3 files changed, 272 insertions(+), 2 deletions(-)
 create mode 100644 Prueba-backups/Prueba-2026-03-02_163913.zip

C:\Users\Joan\test>git puch
git: 'puch' is not a git command. See 'git --help'.

The most similar command is
        push

C:\Users\Joan\test>git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 12 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 5.36 KiB | 2.68 MiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/joan48011/test.git
   c22f4a4..ed311ee  main -> main
