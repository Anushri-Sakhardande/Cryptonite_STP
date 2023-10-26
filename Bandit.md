# Index
* [Level 0](#lvl0)
* [Level 0 → Level 1](#lvl1)
* [Level 1 → Level 2](#lvl2)
* [Level 2 → Level 3](#lvl3)
* [Level 3 → Level 4](#lvl4)
* [Level 4 → Level 5](#lvl5)
* [Level 5 → Level 6](#lvl6)
* [Level 6 → Level 7](#lvl7)
* [Level 7 → Level 8](#lvl8)
* [Level 8 → Level 9](#lvl9)
* [Level 9 → Level 10](#lvl10)
* [Level 10 → Level 11](#lvl11)
* [Level 11 → Level 12](#lvl12)
* [Level 12 → Level 13](#lvl13)
* [Level 13 → Level 14](#lvl14)
* [Level 14 → Level 15](#lvl15)
* [Level 15 → Level 16](#lvl16)
* [Level 16 → Level 17](#lvl17)
* [Level 17 → Level 18](#lvl18)
* [Level 18 → Level 19](#lvl19)
* [Level 19 → Level 20](#lvl20)
* [Level 20 → Level 21](#lvl21)
* [Level 21 → Level 22](#lvl22)
* [Level 22 → Level 23](#lvl23)
* [Level 23 → Level 24](#lvl24)



# <a id="lvl0"></a>Level 0
### Level Goal
The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/923af17c-b3fc-4758-87a5-2de0de2365b6)

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/9771ec97-487b-4957-9805-614a32f276dd)

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/f144bb91-a431-4854-88ce-a1f731d89028)

SSH is a network protocol for using services securely over an unsecured network. Uses public key cryptography.
Used SSH to connect to the server at port 2220 and proceeded to put bandit0 as the password

# <a id="lvl1"></a>Level 0→ Level 1
### Level Goal
The password for the next level is stored in a file called readme, located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/72bcc74c-47fb-4e3e-a865-bf62d10c7cbe)

Ls and cat the readme file.

**NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL**

# <a id="lvl2"></a>Level 1→ Level 2
### Level Goal
The password for the next level is stored in a file called "-" located in the home directory.

We have a file named - which we can't simply cat.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/2a5a87ee-4509-47fb-be37-a411ca2e238e)

I found this on the stack overflow.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/12c6295b-6b73-4169-ae5f-81327723a99e)

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/6ddfa0db-d23d-4957-9daf-d3f6b0694a74)

**rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi**

# <a id="lvl3"></a>Level 2→ Level 3
### Level Goal
The password for the next level is stored in a file called spaces in this filename located in the home directory.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/b1222b9f-6d14-4539-b29d-9a2e00340b10)

**aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG**

# <a id="lvl4"></a>Level 3→ Level 4
### Level Goal
The password for the next level is stored in a hidden file in the inhere directory.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/52564a15-ec23-4a12-8d51-33433c9239ff)

So we know it is in a hidden file in inhere. We use ls with -a, which shows all files in the directory

**2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe**

# <a id="lvl5"></a>Level 4→ Level 5
### Level Goal
The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/a9817c62-e9de-4001-885e-db49ceb626f9)
We have ten files

 ![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/fcf553b5-9a74-4a3b-b98a-7489ecfa6083)

I went through their file type using the file command.

File 7 is an ASCII file containing our coveted flag
**lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR**


# <a id="lvl6"></a>Level 5→ Level 6
### Level Goal
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:
human-readable
1033 bytes in size
not executable

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/1c58fdff-9ba6-4729-b50c-d58aef740b5b)

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/00ab55c1-bafa-43fd-bb80-d4a4909b70eb)

Combined these with find. I needed some help with typing it correctly.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/1c5d7547-43bf-4057-8728-b230cacf891d)

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/c411efcc-b35d-49a7-8db1-dcbd7153677b)


**P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU**


# <a id="lvl7"></a>Level 6→ Level 7
### Level Goal
The password for the next level is stored somewhere on the server and has all of the following properties:
owned by user bandit7
owned by group bandit6
33 bytes in size

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/002ed9b3-cd21-4ad2-b3d3-64e080c2ae4f)

Trying to find it yields a ton of permission-denied messages.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/b122f917-d04f-4e10-81b7-96becf551424)

**z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S**

# <a id="lvl8"></a>Level 7→ Level 8
### Level Goal
The password for the next level is stored in the file data.txt next to the word millionth.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/599eb8b7-2cc6-4267-a0f5-11f1166800f7)

Used grep, which helps find the particular pattern in the file
**TESKZC0XvTetK0S9xNwm25STk5iWrBvP**

# <a id="lvl9"></a>Level 8→ Level 9
## Level Goal
The password for the next level is stored in the file data.txt and is the only line of text that occurs only once
Used uniq command along with sort to find lines that are not repeated

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/973e80d6-2bc0-4fef-b866-28b6b54515cd)

**EN632PlfYiZbn3PhVK3XOGSlNInNE00t**

# <a id="lvl10"></a>Level 9→ Level 10
### Level Goal
The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.
String command helps find the human-readable strings and grep to find the === pattern.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/a28f7a8a-7f2e-44d2-b685-dc7ee50c11d2)

**G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s**

# <a id="lvl11"></a>Level 10→ Level 11
Level Goal
The password for the next level is stored in the file data.txt, which contains base64 encoded data.
Used the base64 command to decode the text

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/dacce091-67c4-4cd1-a2ed-f6f2313e669b)

**6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM**

# <a id="lvl12"></a>Level 11→ Level 12
### Level Goal
The password for the next level is stored in the file data.txt, where 13 positions have rotated all lowercase (a-z) and uppercase (A-Z) letters
tr - translate shifted each character by 13 using the translate command

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/5a30c75d-c49b-479e-98b3-28b40550daba)

JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv


# <a id="lvl13"></a>Level 12→ Level 13
### Level Goal
The password for the next level is stored in the file data.txt, which is a hex dump of a file that has been repeatedly compressed. For this level, creating a directory under /tmp may be helpful in which you can work using mkdir. For example: mkdir /tmp/myname123. Then copy the datafile using cp, and rename it using mv (read the manpages!)


I had to look up a writeup for this one. 
We have to revert a hex dump, meaning convert it back to text form and decompress it multiple times.
So we first make a temporary folder using mkdir, move the file in using cp, and rename with mv.

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/268c1b73-335d-4e9c-90c1-b0026fe73f3d)

We then revert it to text form using xxd -r to get a look at the actual data.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/fb6cda69-4d3b-43c6-9bdb-69515eda8e17)

Every compressed file contains a file signature as its first byte, which clues us as to which compression method to use. From [this list](https://en.wikipedia.org/wiki/List_of_file_signatures),
I got help with the first byte.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/cd96a8c6-db53-4842-b145-772950d17d23)
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/1cec1ee5-7872-4d43-ad93-3b3ce60a8386)

This one had the gzip compression. 
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/fb87f79e-e756-4cd1-a167-60d7b3d6eb88)

So decompressed with gzip -d
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/986cc1ef-0881-4e5f-8874-387ad79136e9)

Now we have a Bzip2 file decompressed with bzip2 -d.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/8dd66afe-7cba-421c-83df-69733742b90a)

Now we again have a gzip.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/4dd5cd53-9b93-4f7e-8427-98f8dacfbf59)

This shows data5.bin and the file header. The writeup says it is a tar file. I did some reading to find out that tar files do not have a magic number header and only show the metadata as ASCII.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/98f254f9-914d-4d78-b1a2-a279e9afdfee)

Data5.bin is also compressed as tar.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/1f461278-ccb1-48cf-9372-40b0042cef17)

This time it is compressed again as bzip2.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/309fbcc2-87d4-4e20-98ce-20a2c4b9b1e4)

Again, it looks like a tar file
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/6b595e2c-3869-413b-ae38-d41270151d2e)

Now a gzip 
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/4c1506e2-f2cf-4148-bea3-fe8de382ab1b)

Finally, we get the password **wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw**

# <a id="lvl14"></a>Level 13→ Level 14
### Level Goal
The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Note: localhost is a hostname that refers to the machine you are working on

![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/49690ef8-716e-424b-8be0-31a57a34b766)

The private key is on the remote server.
Scp is used to transfer files over an SSH connection
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/ae1c4731-b3c1-4efd-9ea6-5c91655c9ac0)

So I got the private key fom the remote server and tried logging using it
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/44a8b658-8a2f-46c2-aec7-d40d217cb085)

But the file is unprotected 
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/12ba6603-c5ba-4b35-9a3a-7af4bca5fb3e)


These are the permissions. We reduce permissions with chmod 700.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/0092aa4c-467a-476a-9889-a40684fe9729)

and we are in.
And we get the password according to the instructions.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/5634b599-8b4a-434c-9bb2-0e6821cd85d1)

**fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq**

# <a id="lvl15"></a>Level 14→ Level 15
### Level Goal
The password for the next level can be retrieved by submitting the password of the current level to port 30000 on localhost.


Netcat nc is used to send and receive data over a network connection. So we connect to localhost on port 3000 and submit the password from the previous level.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/85e280f8-361e-4f0d-9020-5ffc8c36a3bc)

**jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt**

# <a id="lvl16"></a>Level 15→ Level 16
### Level Goal
The password for the next level can be retrieved by submitting the password of the current level to port 30001 on localhost using SSL encryption.
Helpful note: Getting “HEARTBEATING” and “Read R BLOCK”? Use -ign_eof and read the “CONNECTED COMMANDS” section in the manpage. Next to ‘R’ and ‘Q’, the ‘B’ command also works in this version of that command…

SSL is a cryptographic protocol that prevents eavesdropping of others in the client-server connection by establishing a handshaking procedure.
OpenSSL is a software library to provide applications for secure communication.
OpenSSL s_client uses SSL to set up a simple client that connects to a server.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/85a8e5a8-b8f8-4ff7-9828-5ff875443fb0)

I then put in the password.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/01bd9d80-0ac2-497b-bdb5-6c23670ca652)

**JQttfApK4SeyHwDlI9SXGR50qclOAil1**

# <a id="lvl17"></a>Level 16→ Level 17
## Level Goal
The credentials for the next level can be retrieved by submitting the password of the current level to a port on localhost in the range 31000 to 32000. First find out which of these ports have a server listening on them. Then find out which of those speak SSL and which don’t. There is only 1 server that will give the next credentials, the others will simply send back to you whatever you send to it.
A service is said to be “listening” on a port when it is binding to a port/protocol/IP address combination to wait for requests from clients of the service.

Nmap is used for finding information about all the ports and hosts.-sV gives the port version, and -p filters the port numbers.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/413a357f-9305-4d02-b5e8-46d76853594f)
31518 echoes the answer, so we connect to 31790.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/1491191f-710e-46aa-858d-8478fbfb8c61)

Putting in the password yields a private key
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/e71c377b-6b84-4e28-9204-f32e6cb873a2)

I put the private key into sshkey2.private and made sure the permissions were correct this time.
And proceed to use that to log in to the next level.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/8589bc18-e938-4374-a154-2c812acfda2b)

# <a id="lvl18"></a>Level 17→ Level 18
### Level Goal
There are 2 files in the homedirectory: passwords.old and passwords.new. The password for the next level is in passwords.new and is the only line that has been changed between passwords.old and passwords.new
NOTE: if you have solved this level and see ‘Byebye!’ when trying to log into bandit18, this is related to the next level, bandit19
Diff command is used to find the difference between two files.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/69aefa62-1c10-44e7-bec9-189466fe6dfa)

**hga5tuuCLF6fFzUpnagiMN8ssu9LFrdg**

# <a id="lvl9"></a>Level 18→ Level 19

## Level Goal
The password for the next level is stored in a file readme in the homedirectory. Unfortunately, someone has modified .bashrc to log you out when you log in with SSH.

.bashrc holds the configuration of the shell.
The connection is closed
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/668e0c9b-a296-4208-a665-0df424db267f)

We can access the readme by appending commands after the ssh connection details to remotely access the server.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/5f94d488-98a1-4bb2-bba8-f108b9d2740e)

**awhqfNnAbc1naukrpqDYcF95h7HoMTrC**

# <a id="lvl20"></a>Level 19→ Level 20
### Level Goal
To gain access to the next level, you should use the setuid binary in the homedirectory. Execute it without arguments to find out how to use it. The password for this level can be found in the usual place (/etc/bandit_pass), after you have used the setuid binary

access rights flags setuid and setgid (short for set user identity and set group identity)[1] allow users to run an executable with the file system permissions of the executable's owner or group respectively and to change behaviour in directories. They are often used to allow users on a computer system to run programs with temporarily elevated privileges to perform a specific task. While the assumed user ID or group ID privileges provided are not always elevated, at a minimum, they are specific.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/c8cb3b1a-e108-4154-9855-8cb4b02e9b33)

Read permission is there for user bandit20.
So we use the uid of bandit20 access.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/a3241f77-17ae-4d5c-ad8b-48378597956a)

**VxCazJaVykI6W36BkBU0mJTCM8rR95XT**

# <a id="lvl21"></a>Level 20→ Level 21
### Level Goal
There is a setuid binary in the homedirectory that does the following: it makes a connection to localhost on the port you specify as a commandline argument. It then reads a line of text from the connection and compares it to the password in the previous level (bandit20). If the password is correct, it will transmit the password for the next level (bandit21).
NOTE: Try connecting to your own network daemon to see if it works as you think
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/446865dc-6339-426d-bcc8-71d6c20590f8)

Nc -l listens to the connection and we connect to a random port 1234 The & is used run the process in the background.
We now run the setuid according to the information given and enter the password we have found.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/81af7b17-d43d-40e6-a0bb-420055991e81)

**NvEJF7oVjkddltPSrdKEFOllh9V1IBcq**

# <a id="lvl22"></a>Level 21→ Level 22
### Level Goal
A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed.
According to the instructions, I looked up the directory.
The cronjob creates a file which I simply cat.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/4ea76bc5-3c69-419f-8e2b-7a8b7800bcf0)
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/564efed1-76f5-4aea-8978-d7ea678ec8b7)

**WdDozAdTM2z9DiFEQ2mGlwngMfj4EZff**

# <a id="lvl23"></a>Level 22→ Level 23
### Level Goal
A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed.
NOTE: Looking at shell scripts written by other people is a very useful skill. The script for this level is intentionally made easy to read. If you are having problems understanding what it does, try executing it to see the debug information it prints.
So according to the information, I practically did the same thing as the last level.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/abd20254-bef1-412c-b35b-1e468bf48ce4)

This time I received the set of instructions which I simply followed along with to reveal the password.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/96d3f486-424b-4647-bf12-dc895c83d4db)

**QYw0Y2aiA672PsMmh9puTQuhoz8SyR2G**


# <a id="lvl24"></a>Level 23→ Level 24
### Level Goal
A program is running automatically at regular intervals from cron, the time-based job scheduler. Look in /etc/cron.d/ for the configuration and see what command is being executed.
NOTE: This level requires you to create your own first shell-script. This is a very big step and you should be proud of yourself when you beat this level!
NOTE 2: Keep in mind that your shell script is removed once executed, so you may want to keep a copy around…
We have a shell script that deletes all files unless the user is bandit23, in which case it executes the file.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/a538bb3e-089b-45f6-82b7-2474ba4e6f71)

So, we make a temporary folder and follow templates of the previous levels to write a shell script.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/c55de052-1dc3-46a9-a689-992e3a43e798)

/tmp/tmp.sUJz8PsA16

We will put the password into the password file.
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/f7091271-2f69-4123-9b0b-3046f39c4195)

We give full permissions to the file and directory
![image](https://github.com/Anushri-Sakhardande/Cryptonite_STP/assets/118385974/77ff17a3-79c6-43a0-92bd-fad4bc4019b3)


