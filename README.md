# b153.co
This is the placeholder file for b153.co blog.

### Some instructions for using this repository.

This is a static web site using hugo.

The source is in src

Building source fills up the root with the real site.

To build...  

```

#Assuming your in the root of this repository...

cd ./src

#This will build the site at the root of the directory (because the config file builds to ../
hugo

```

#Andrea's special git reminder pane

```console
#See any git changes
git status

#Add files to a pending commit
git add . #(Or use individual file names instead of .)

#Commit the pending files
git commit -m "Your commit message here"

#Push that commit to the main repo (and thus make it live if you've built the site)
git push origin master

#You'll see errors if other people have pushed stuff.  Pull and merge first
git pull origin master

```
