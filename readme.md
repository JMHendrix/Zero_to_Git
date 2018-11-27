## Common Commands
```Shell

ls <path>     ## Command

ls -a     ## Show Invisible files of current directory

ls ./ 	## Show Current Directory 
```

```
cd <path> ## Command

cd ./Desktop. ## Relative Path changing directory
```
### Paths

##### Current User's Home Folder
```/Users/cchapman/ ``` is the same as ```~```

##### Absolute Paths
The entire path from the root ```/``` of your hard drive to the folder you are targeting. 
Example:```/users/cchapman/Desktop/Zero_to_Git```

##### Relative Paths
```./``` or ```.``` prefix for Relative path. Means "My current working directory."
```shell
cd ./Desktop
```
## Be Careful
```shell
rm /
```
## Git Commands 
Use once when starting a git repo

```shell
git init
```

One time commands

```shell
git config --global core.editor "nano"
git config --global user.name "Hendrix"
git config --global user.email JMHendrix@student.fullsail.edu
```

Use often, Common Commands

```shell
git init
git status 
git add <path>
git commit -m "Some message here (Start with a verb)"
```




