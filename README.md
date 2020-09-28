$ git clone git@github.com:Miku3250/Hello-World.git
Cloning into 'Hello-World'...
remote:Counting objects: 3,done.
remote:Total 3 (delta 0),reused 0 (delta 0)
Receiving objects:100% (3/3), done.

$ cd Hello-World
# Hello-World
<?php
   echo "Hello World";
?>
$ git status
# On branch master
# Untracked files:
# (use "git add<file>..."to include in what will be committed)
#   
#    hello_world.php
  nothing added to commit but untracked files present(use "git add"to track)
$ git add hello_world.php
$ git commit -m "Add hello world script by php"
[master d23b909] Add hello qorld script by php
 1 file changed, 3 insertions(+)
   creat mode 100644 hello_world.php
$git log
   commit d23b909caad5d4
   Author: hirocastest <hohtsuka@gmail.com>
   Date: 2020
   Add hello world script by php
   
