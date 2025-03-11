# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
 
![276810106-3231afbf-31db-4eae-9a4e-4857a5334d96](https://github.com/user-attachments/assets/0f7ffbc6-e403-4008-84d9-63cef8a21cbb)



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![276810403-631389db-7c2d-4c6e-a34a-7c0c94fb90cd](https://github.com/user-attachments/assets/256f5942-bda3-4fca-ba7c-90f4b19c0a39)


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![276810658-5e7a2a7b-328c-4039-99d6-9e44206e2745](https://github.com/user-attachments/assets/7976ab4c-bc80-46df-a074-e0449057f535)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![276810944-177a203a-ecbb-4878-add2-f42f2c29b123](https://github.com/user-attachments/assets/8e5513c6-ba03-4a14-a325-8cfa965a33ef)



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![276811143-58beef2c-2e0d-4d14-b5a6-d806c8b1d81b](https://github.com/user-attachments/assets/b4fe9243-5c2a-4ea3-b7c1-e4d77c49be7a)



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

 ![276811338-5e2417aa-589d-4e21-88f5-ce1094000915](https://github.com/user-attachments/assets/4f731082-5490-47fc-838d-3c9003af1c51)

### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![276811529-3ff740d0-e6ae-45c8-8a2f-adfa976c137e](https://github.com/user-attachments/assets/c4c29105-7c5b-424d-b789-a2abaa65342e)


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![276811683-5069c51f-844c-4014-bc32-d3578300be05](https://github.com/user-attachments/assets/ba00f072-6046-4c97-a025-34f8c2b5de78)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
![276814083-51685b5e-4919-49b5-88c5-dab75ce47a48](https://github.com/user-attachments/assets/a8e861c1-e9db-4e92-8192-c683f7814806)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![276814112-34193d41-b475-4e7b-9898-89efb5e396b3](https://github.com/user-attachments/assets/c3e85156-b039-42c8-b73e-73f1243cb15b)

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 ![276814135-77af1242-e096-482c-8993-3fd2023fb5fe](https://github.com/user-attachments/assets/bc264758-66ac-4263-bd95-f9d1bcbdcc53)

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![276814164-26ad8350-1d47-475e-8ac1-1153165138d2](https://github.com/user-attachments/assets/44ec8a2c-61e5-45ce-96eb-2bc7f7b9b33b)

### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![276814234-73da0d46-242a-41f9-bb8f-ebc4cf38c809](https://github.com/user-attachments/assets/6b292fd7-91f0-47b2-8dca-d3461107fe1e)

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 ![276814285-ae81e9ab-c8e6-4b74-8d27-f9124c790cfa](https://github.com/user-attachments/assets/20b3c588-f52a-4019-8a4c-f11e2635c7cb)

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![276814350-8282ffef-252d-4665-a5a2-52c1a15ad6ca](https://github.com/user-attachments/assets/f60adaf7-02c4-49bc-bf14-8b2a780b2e8a)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
