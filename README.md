git init
git touch README.md
git add . 
git commit -M "aristant"
git remote add origin
git credeltial.name "qwesosiski"
git push




#git
$ mkdir sashahaji2107

is@MK-201-007 MINGW64 ~
$ cd sashahaji2107

is@MK-201-007 MINGW64 ~/sashahaji2107
$ git init
Initialized empty Git repository in C:/Users/IS/sashahaji2107/.git/

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ gti status
bash: gti: command not found

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git remote add origin https://github.com/qwesosiski/2804.git

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git remote -v
origin  https://github.com/qwesosiski/2804.git (fetch)
origin  https://github.com/qwesosiski/2804.git (push)

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ touch README.md

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ explorer .

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ explorer .

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git add .

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git commit -m "aristant"
[master (root-commit) 53c938d] aristant
 Committer: Студент группы IS <is@sielom.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
 create mode 100644 README.md

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git push origin
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$  git config --global user.name "balamut"

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$  git config --global user.email "loxantox@mail.ru"

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git push origin
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git push -u origin master
remote: Permission to qwesosiski/2804.git denied to vadim0732.
fatal: unable to access 'https://github.com/qwesosiski/2804.git/': The requested URL returned error: 403

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git remote add origin https://github.com/qwesosiski/2804.git
error: remote origin already exists.

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git rm remote
fatal: pathspec 'remote' did not match any files

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git rem origin
git: 'rem' is not a git command. See 'git --help'.

The most similar commands are
        grep
        refs
        remote
        rm

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git rm origin
fatal: pathspec 'origin' did not match any files

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ ggit config credential.helper
bash: $'\302\203git': command not found

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git config credential.helper
manager

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git credential
usage: git credential (fill|approve|reject)

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git credential fill




is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ printf "protocol=https\nhost=github.com\nusername=<me>" | \
  git credential-manager-core get
git: 'credential-manager-core' is not a git command. See 'git --help'.

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git config user.name "sashamasha
> ^C

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ ^C


is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git config user.name "sashamasha"

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ ^[[200~git config ^Cedential.username "new name"~

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ ^C

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ ^C

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git config credential.username "qwesosiski"

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git credential^C

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ ^C


is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 239 bytes | 239.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/qwesosiski/2804.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

is@MK-201-007 MINGW64 ~/sashahaji2107 (master)
$
