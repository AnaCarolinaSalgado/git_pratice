Carol@DESKTOP-4RAUA55 MINGW64 ~$mkdir git_practice

Carol@DESKTOP-4RAUA55 MINGW64 ~
$ cd git_practice

Carol@DESKTOP-4RAUA55 MINGW64 ~/git_practice
$ git init
Initialized empty Git repository in C:/Users/Carol/git_practice/.git/

Carol@DESKTOP-4RAUA55 MINGW64 ~/git_practice (master)
$

Carol@DESKTOP-4RAUA55 MINGW64 ~/git_practice (master)
$ echo "Hello Git and GitHub" >> README,txt

Carol@DESKTOP-4RAUA55 MINGW64 ~/git_practice (master)
$ echo "Hello Git and GitHub" >> README.txt

Carol@DESKTOP-4RAUA55 MINGW64 ~/git_practice (master)
$ git add README.txt
warning: LF will be replaced by CRLF in README.txt.
The file will have its original line endings in your working directory

Carol@DESKTOP-4RAUA55 MINGW64 ~/git_practice (master)
$ git commit -m "First commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Carol@DESKTOP-4RAUA55.(none)')

Carol@DESKTOP-4RAUA55 MINGW64 ~/git_practice (master)
$ git config --global user.email "carol-salgado@hotmail.com"

Carol@DESKTOP-4RAUA55 MINGW64 ~/git_practice (master)
$ git config --global user.name "anacarolinasalgado"

Carol@DESKTOP-4RAUA55 MINGW64 ~/git_practice (master)
$ git commit -m "First commit"
[master (root-commit) 38dcc1f] First commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.txt

Carol@DESKTOP-4RAUA55 MINGW64 ~/git_practice (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README,txt

nothing added to commit but untracked files present (use "git add" to track)

Carol@DESKTOP-4RAUA55 MINGW64 ~/git_practice (master)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

Carol@DESKTOP-4RAUA55 MINGW64 ~/git_practice (master)
$ git add .
warning: LF will be replaced by CRLF in README,txt.
The file will have its original line endings in your working directory

Carol@DESKTOP-4RAUA55 MINGW64 ~/git_practice (master)
$
