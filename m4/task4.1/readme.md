## TASK 4.1


## Part 1

### 1. Logged in to the system as root
![img](images/lx01.jpg)


### 2. Using the *passwd* command to change the password
![img](images/lx02.jpg)

-examining *passwd* command basic parameters by using *man* command
![img](images/lx03.jpg)
![img](images/lx04.jpg)
![img](images/lx05.jpg)

-command *passwd* make changes to such system files - */ets/passwd, /etc/shadow and /etc/pam.d/passwd*
![img](images/lx06.jpg)


### 3. Determining what users are registered in the system (*w*, *who*, *finger* and etc.)
![img](images/lx07.jpg)

-determining what commands users executes (*who -aH*)
![img](images/lx08.jpg)

-additional options can be found in manual by typing *man <command>* or *info <command>*. I have used *man finger* for example
![img](images/lx09.jpg)


### 4. Changing my personal information, using chfn command
![img](images/lx10.jpg)


### 5. Exploring Linux help system and the *man* and *info* commands
![img](images/lx11.jpg)
![img](images/lx12.jpg)
![img](images/lx13.jpg)
 
-geting help on the *chfn* commands
![img](images/lx14.jpg)

-describing two keys for *chfn* commands and giving examples
![img](images/lx15.jpg)


### 6. Exploring the *more* and *less* commands using the help system
-more
![img](images/lx16.jpg)

-less
![img](images/lx17.jpg)

Viewing the contents of file .bashrc using commands:
-using *more .bashrc*
![img](images/lx18.jpg)

-using *less .bashrc*
![img](images/lx19.jpg)


### 7. Determining the last logon time for all users. Using *finger -l* and *last -a* commands
![img](images/lx20.jpg)


### 8. Listing the contents of the home directory using the *ls* command
![img](images/lx21.jpg)

-defining its files and directories (*ls -al*)
![img](images/lx22.jpg)


## Part 2

### 1. Exploring the *tree* command using *man tree* command
![img](images/lx23.jpg)

-Command *tree -aP 'le*'* displaying all files that contain specific sequence of characters *le*
![img](images/lx24.jpg)

-Command *tree -aL 2* lists subdirectories of the root directory up to and including the second nesting level
![img](images/lx25.jpg)

### 2. Using command *file* to determine the type of file
![img](images/lx26.jpg)

### 3. Navigating the file system using *cd* command. Using *cd ~* command to quick navigate user home directory
![img](images/lx27.jpg)

### 4. Exploring *ls* command and its various options. Using *man ls* to get info about command
![img](images/lx28.jpg)

Switch *-a* - displays hidden entries(staring with .)
![img](images/lx29.jpg)

Switch *-l* - displays entries in long listig format
![img](images/lx30.jpg)

### 5. Performing the following sequence of operations:
-сreating a subdirectory *az* in the home directory;
-сreating a file *root.tree* containing information about directories located in the root directory
-viewing the created file
![img](images/lx31.jpg)

-coping created file to your home directory using absolute addressing
![img](images/lx32.jpg)
-coping created file to your home directory using relative addressing
![img](images/lx33.jpg)

-deleting the previously created subdirectory with the file requesting removal
-deleting the file copied to the home directory
![img](images/lx34.jpg)

### 6. Performing the following sequence of operations:
-creating a subdirectory test in the home directory
-coping the .bash_history file to this directory while changing its name to labwork2
-creating a hard and soft link to the labwork2 file in the test subdirectory
-defining soft and hard link, with *ls -al* command
![img](images/lx35.jpg)

-changing data by opening a symbolic link by command *nano softlink*. This will change the content of original labwork2 file (second screenshot, cat labwork2)
![img](images/lx36.jpg)
![img](images/lx37.jpg)

-renaming the hardlink file to hard_lnk_labwork2
-renaming the softlink file to symb_lnk_labwork2 file
-After deleting the labwork2 file, softlink is no more accessible (link displayed in red colour) and hardlink is still existing and storing the copy of labwork2 data
![img](images/lx38.jpg)

### 7. Finding all files that contain the squid and traceroute sequence(using *find /etc -name "example"* command)
![img](images/lx39.jpg)

### 8. Determining which partitions are mounted in the system (df -h), as well as the types of these partitions
![img](images/lx40.jpg)

### 9. Counting the number of lines containing a characters in file proc/mounts using *wc* command
![img](images/lx41.jpg)

### 10. Searching all files in the /etc directory containing the host character sequence
![img](images/lx42.jpg)

### 11. Listing all objects in /etc that contain the ss character sequence, using *grep -r 'ss' /etc* command
![img](images/lx43.jpg)

### 12. Organizing a screen-by-screen print of the contents of the /etc directory with *ls -l /etc | less* command
![img](images/lx44.jpg)

### 13. Listing devices with its type and inf mount point, *df -ahT* command used
![img](images/lx45.jpg)

### 14. Using *file <filename>* determines type of file
![img](images/lx46.jpg)

### 15.* Listing first 5 directory files that were recently accessed in the /etc directory by *ls -lut /etc/ | head -n6* command
![img](images/lx47.jpg)