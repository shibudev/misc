# Basic terminal command for all, web designer and developer 

### to change the directory
~~~
cd <folderName>
~~~

### to back to parent directory. `..` indicate parent working directory
~~~
cd ..
~~~

### to select present working directory `.` is used. In following example sublime text open with current folder
~~~
subl .
~~~

### to know the current working directory  
~~~
pwd
~~~

### to make a folder
~~~
mkdir <foldername>
~~~

### to make a file
~~~
touch <filename>
~~~

### what file inside present working directory. In order to search any file use grep arguments
~~~
ls
ls | grep style
~~~

### to copy file
~~~
cp <file to be copied> <Where should be copied>
~~~

### to copy folder I have to use flag `-r`. which means recursive.
~~~
cp -r <folder to be copied> <Where should be copied>
~~~

### to move file or folder
~~~
mv <file/folder to be moved> <Where should be moved>
~~~

### to rename file or folder
~~~
mv <filename> <newFilename>
~~~

### to write something inside file
~~~
echo <the things you want to write> >> <filename>
~~~

### to remove file
~~~
rm <filename>
~~~

### to remove folder
~~~
rm -rf <foldername>
~~~
