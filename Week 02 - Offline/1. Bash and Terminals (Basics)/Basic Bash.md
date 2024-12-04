# 1.Basic Bash Command

## Commands

### 1. `Pwd: ` It will print current working Directory.
```sh
$ pwd 
```
### 2. `cd: ` Change Directory.
```sh
$ cd week-2-offline --it will change Direcotry to week-2-offline
$ cd .. -- it will go back one directory back 
$ cd ../.. --it will go back two directory back 
```  
### 3. `ls: `  it will list all the files and folder of your current working Direcotry. 
```sh
$ ls 
```
### 4. `mkdir: ` to create a new foder in current directory.
```sh
$ mkdir folder-name
```
### 5. `touch: ` to create a new file in current directory.
```sh
$ touch file-name
```
### 6. `rmdir: ` to delete folder from current directory.
```sh
$ rmdir folder-name
```
### 7. `rm: ` to delete file from current directory.
```sh
$ rm file-name
```
### 8. `cat: ` it will print contents of file. 
```sh
$ cat file-name
```

### 9. `vi: ` working with vim editor.
```sh
$ vi file-name -- it will open vim editor 

Press `i` to work in insert mode.
Now we can write anything.

After writing we have to exit from insert mode and vim editor mode

Press `ESC`

then `:q!` to exit from vim editor without saving the content of file

    `:wq!` to exit from vim editor with saving the content of file

```

### 10. `mv: ` to move file and folder
```sh
$ mv file-name(file which you want to move) folder-name(folder where you want to move that file)

`Exmaple: mv hello.js HelloWorldApp`

$ mv folder-name(foder which you want to move) folder-name(folder where you want to move that file)

`Exmaple: mv models dbFiles`
```

### 11. `cp: ` to copy the files and folders.
```sh
$ cp file-name(file which you want to copy) folder-name(folder where you want to copy that file)

`Exmaple: cp hello.js HelloWorldApp`

$ cp folder-name(foder which you want to copy) folder-name(folder where you want to copy that file)

`Exmaple: cp models dbFiles`
```

### 12. `nvm: ` to install node in your system
