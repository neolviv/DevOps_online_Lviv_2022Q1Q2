## TASK 4.1


## Part 1


### 1. Logged in to the system as root
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx01.jpg)
</details>


### 2. Using the *passwd* command to change the password
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx02.jpg)
</details>

-examining *passwd* command basic parameters by using *man* command
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx03.jpg)
  ![img](images/lx04.jpg)
  ![img](images/lx05.jpg)
</details>

-command *passwd* make changes to such system files - */ets/passwd, /etc/shadow and /etc/pam.d/passwd*
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx06.jpg)
</details>


### 3. Determining what users are registered in the system (*w*, *who*, *finger* and etc.)
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx07.jpg)
</details>

-determining what commands users executes (*who -aH*)
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx08.jpg)
</details>

-additional options can be found in manual by typing *man <command>* or *info <command>*. I have used *man finger* for example
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx09.jpg)
</details>


### 4. Changing my personal information, using chfn command
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx10.jpg)
</details>


### 5. Exploring Linux help system and the *man* and *info* commands
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx11.jpg)
  ![img](images/lx12.jpg)
  ![img](images/lx13.jpg)
</details>
 
-geting help on the *chfn* commands
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx14.jpg)
</details>

-describing two keys for *chfn* commands and giving examples
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx15.jpg)
</details>


### 6. Exploring the *more* and *less* commands using the help system
-more
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx16.jpg)
</details>

-less
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx17.jpg)
</details>

Viewing the contents of file .bashrc using commands:
-using *more .bashrc*
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx18.jpg)
</details>

-using *less .bashrc*
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx19.jpg)
</details>


### 7. Determining the last logon time for all users. Using *finger -l* and *last -a* commands
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx20.jpg)
</details>


### 8. Listing the contents of the home directory using the *ls* command
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx21.jpg)
</details>

-defining its files and directories (*ls -al*)
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx22.jpg)
</details>


## Part 2


### 1. Exploring the *tree* command using *man tree* command
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx23.jpg)
</details>

-Command *tree -aP 'le*'* displaying all files that contain specific sequence of characters *le*
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx24.jpg)
</details>

-Command *tree -aL 2* lists subdirectories of the root directory up to and including the second nesting level
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx25.jpg)
</details>


### 2. Using command *file* to determine the type of file
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx26.jpg)
</details>


### 3. Navigating the file system using *cd* command. Using *cd ~* command to quick navigate user home directory
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx27.jpg)
</details>


### 4. Exploring *ls* command and its various options. Using *man ls* to get info about command
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx28.jpg)
</details>

Switch *-a* - displays hidden entries(staring with .)
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx29.jpg)
</details>

Switch *-l* - displays entries in long listig format
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx30.jpg)
</details>


### 5. Performing the following sequence of operations:

-сreating a subdirectory *az* in the home directory;
-сreating a file *root.tree* containing information about directories located in the root directory
-viewing the created file
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx31.jpg)
</details>

-coping created file to your home directory using absolute addressing
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx32.jpg)
</details>

-coping created file to your home directory using relative addressing
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx33.jpg)
</details>

-deleting the previously created subdirectory with the file requesting removal
-deleting the file copied to the home directory
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx34.jpg)
</details>


### 6. Performing the following sequence of operations:
-creating a subdirectory test in the home directory
-coping the .bash_history file to this directory while changing its name to labwork2
-creating a hard and soft link to the labwork2 file in the test subdirectory
-defining soft and hard link, with *ls -al* command
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx35.jpg)
</details>

-changing data by opening a symbolic link by command *nano softlink*. This will change the content of original labwork2 file (second screenshot, cat labwork2)
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx36.jpg)
  ![img](images/lx37.jpg)
</details>


-renaming the hardlink file to hard_lnk_labwork2
-renaming the softlink file to symb_lnk_labwork2 file
-After deleting the labwork2 file, softlink is no more accessible (link displayed in red colour) and hardlink is still existing and storing the copy of labwork2 data
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx38.jpg)
</details>


### 7. Finding all files that contain the squid and traceroute sequence(using *find /etc -name "example"* command)
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx39.jpg)
</details>

### 8. Determining which partitions are mounted in the system (df -h), as well as the types of these partitions
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx40.jpg)
</details>


### 9. Counting the number of lines containing a characters in file proc/mounts using *wc* command
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx41.jpg)
</details>


### 10. Searching all files in the /etc directory containing the host character sequence
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx42.jpg)
</details>


### 11. Listing all objects in /etc that contain the ss character sequence, using *grep -r 'ss' /etc* command
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx43.jpg)
</details>


### 12. Organizing a screen-by-screen print of the contents of the /etc directory with *ls -l /etc | less* command
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx44.jpg)
</details>


### 13. Listing devices with its type and inf mount point, *df -ahT* command used
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx45.jpg)
</details>


### 14. Using *file <filename>* determines type of file
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx46.jpg)
</details>


### 15.* Listing first 5 directory files that were recently accessed in the /etc directory by *ls -lut /etc/ | head -n6* command
<details>
  <summary>Click to expand!</summary>

  ![img](images/lx47.jpg)
</details>