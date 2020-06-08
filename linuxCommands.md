
![Linux logo](./linux_logo.jpg)

### Linux Basic Commands

In this tutorial you will learn basic commands that are very useful when
working in Linux.

1. **cd** -> **Change directory** This command helps you to change directory.
  - $cd <file name> will move you to the <name> directory
  - $cd .. this will bring you backwards one directory at a time
  - $cd ../.. this will bring you backwards two directory at a time
  - $cd ~ this will bring you back to Home.
  <br>
  
2. **mkdir** -> **Make directory** This will allow you to create a new directory.
  - $mkdir <name> will create a directory called "<name>"
  - $mkdir -v <name1> <name2> will create the directories called "name1" and "name2"
  <br>

3. **cp** -> **copy** This will make copies of files and directories
  - $cp file1.txt newFile.txt
  <br>

4. **pwd** -> **print working directory** -> This will let you see the path of the working directory starting from the root.
  - $pwd will display: /home/myName/myCurrentDirectory
  <br>

5. **mv** -> **move** This will move one or more files or directories from one destination to another. Also, it changes the name of a file.
  - $mv source destination
  - $mv file1.txt file2.txt then the file1.txt will be renamed as file2.txt
  <br>

6. **rm** -> **remove** This works as a delete for files or directories
  - $rm file1.txt  will erase file1
  - $rm file1.txt file2.txt  will erase file1.txt and file2.txt
  <br>

7. **history** -> This will display a list of the executed commands in Linux
  - $history  will display the list of all the commands that had been used
  - $history 3  will display the last 3 commands
  <br>

8. **Home directory and \~** -> Home directory is the user's root of all its files and directories
  - the ~ (tilde) will serve as shortcut to get back to home by just typing **cd \~** will bring you to: **user@myHome:~$**
  <br>

9. **File paths** in Linux -> This will be like a map path, to know exactly how to get to a certain directory or file
  - If you type **cd /Desktop/file1/Alpha**
  this will take you directly to user@myHome:~/Desktop/file1/Alpha
  <br>

10. **Tab key** to complete file paths -> This will help you to find the names of the files or directories in the current Directory. For example if you are at: **user@myHome:~/Desktop$ cd f** and you hit the **Tab** key it will display all the files and directories that start with f, making it easier to see what files and directories there are, if there is only one file or directory it will autocomplete it for you.
<br>

11. Using **Up** and **Down** arrow for history -> This will display all the last executed commands in the Linux. It makes it easier because sometimes we want to reuse the
commands and it saves time.
<br>
<br>

![LoveLinux](http://dwaves.de/wp-content/uploads/2016/10/debian_inside.jpeg)
<br>
<br>
A good introduction video is:
- - [YouTube Linux Introduction](https://www.youtube.com/watch?v=IVquJh3DXUA)
