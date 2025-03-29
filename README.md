# Ex-01-Linux-Commands
# Name: SURIYA RAJ K
# Reg No: 212223040216
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
![image](https://github.com/user-attachments/assets/6f98b604-caaf-40d7-b684-b31beba592d3)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/user-attachments/assets/0d574161-ceb3-46d0-98b9-a13d957e638e)
 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/user-attachments/assets/eca27f67-3a93-4122-9a3e-ad921a0f7d09)

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
![image](https://github.com/user-attachments/assets/95092d16-d23d-4bf7-811a-c74c97d1041f)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![image](https://github.com/user-attachments/assets/20a08b36-115b-4667-ac49-68e0de404d35)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![image](https://github.com/user-attachments/assets/a68cced8-bdb3-4b96-96d0-ae138067aef1)
 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/user-attachments/assets/437fcf90-67d2-4b53-9e0b-34c59126ac1a)

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![376898504-3d4f580e-f711-47e1-9f86-d348a03b1374](https://github.com/user-attachments/assets/110a6c22-fd96-4721-9ab9-75c10c8308ab)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
![376898539-a701d9b5-8755-4860-b595-c90cf63ed58c](https://github.com/user-attachments/assets/4c3fab01-a65e-4862-baea-92885c72bf5a)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![376898570-3d82da66-f19d-45e7-a7c6-ba051f8ea232](https://github.com/user-attachments/assets/9656a5cd-397d-4fb0-b10f-a73253ab9492)

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![376898586-352862aa-cfc0-4119-b699-2710619741af](https://github.com/user-attachments/assets/ac4ca7a1-cd32-447f-a1c1-108cc3e390e4)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![376898595-5f504f33-5591-4193-bdde-2bdffbce16dd](https://github.com/user-attachments/assets/233b86bc-071b-44ac-afe5-0abd0eb20b24)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![376898608-8c7c902c-261d-471e-91d8-398d29b68421](https://github.com/user-attachments/assets/d174e3d7-af67-4e7a-90de-a2c52492d4ae)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![376898622-2b5505b0-414f-4634-9b24-76cbe180a2f3](https://github.com/user-attachments/assets/5f1aaabc-6ea3-49ec-a9a4-241c3519551b)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![376898637-7ac56c1a-1fca-44ce-9a97-ee2f1316bd11](https://github.com/user-attachments/assets/fb534f4e-cdb0-4aec-bd57-6cb984d07b16)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![376898660-d1b279a2-0289-459a-aa9e-5a1d454593fa](https://github.com/user-attachments/assets/3f883f74-5019-4745-acb3-62f46557c038)

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

![376898688-1918c386-2b27-47a2-93e4-a4da4516d36f](https://github.com/user-attachments/assets/3efd3e26-ff95-40dd-a39a-a90c05a4d78a)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![376898709-781d6009-7070-43a6-bd4e-e16f141219b3](https://github.com/user-attachments/assets/379ae429-0af2-410c-801e-f1f4634d7e75)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![376898727-c947fdcf-d906-4052-bf91-943598478282](https://github.com/user-attachments/assets/b738893c-2e2f-45f5-b274-30173dbe27e1)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![376898751-06913a7c-cd27-4107-a73f-7f1bbfaec252](https://github.com/user-attachments/assets/401a0ac8-2249-4503-a912-b263f8d7ba80)

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![376898771-80e66b4c-9dca-4d04-a4dc-209114526baa](https://github.com/user-attachments/assets/19c7a975-60ba-4498-adc2-dcb2487f7cb6)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![376898796-5d14e282-3d91-4930-a0b4-49665be282f4](https://github.com/user-attachments/assets/9f261719-88cc-41bd-8ee4-2b3632eaf687)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.
Syntax: cal

![376898816-17358982-cead-4f94-8cce-3be4605eda32](https://github.com/user-attachments/assets/dbdfa346-2e72-4b13-b19a-f99ede7f2541)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![376898835-e265b0c7-92f8-429c-b66f-ccaaf5396da8](https://github.com/user-attachments/assets/c2578c49-d66d-474f-9f1a-293e8b6310c7)


### 28)	mail Command

The mail command is used to send emails from the command line.
"Subject" <recipient address>
Syntax: mail -s

![376898860-6799494a-8c39-4956-b781-4a95ec6f1e12](https://github.com/user-attachments/assets/74861741-d7f3-4f4b-b7ad-6f811985f0f3)

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![376898891-526f8f4f-0b4d-4017-8c29-94a1cfa230e0](https://github.com/user-attachments/assets/c3832e4d-f02f-4745-a3b3-7c1651adf697)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
