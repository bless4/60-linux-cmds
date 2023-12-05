# 60-linux-cmds <br>

## Here's a list of 60 Linux commands along with examples of how they are used: <br>

1. ls (List)  <br>

List files and directories in the current directory. <br>
ls <br>

2. pwd (Print Working Directory) <br>

Print the current working directory. <br>
pwd <br>

3. cd (Change Directory) <br>
 Change directory. <br>

cd /path/to/directory <br>

4. cp (Copy) <br>

Copy files or directories. <br>
cp file.txt /path/to/destination <br>

5. mv (Move/Rename) <br>

Move or rename files or directories. <br>
mv file.txt newfile.txt <br>

6. rm (Remove/Delete) <br>

Remove files or directories. <br>

rm file.txt <br>

7. mkdir (Make Directory) <br>

Create a new directory. <br>

mkdir new_directory <br>

8. rmdir (Remove Directory) <br>
Remove an empty directory. <br>

 rmdir empty_directory <br>
9. touch

Create an empty file or update the access/modification time. <br>

touch new_file.txt <br>

10. cat (Concatenate) <br>

Display the content of files. <br>

cat file.txt <br>

11. more <br>

Display the content of a file one screen at a time. <br>

more file.txt <br>

12. less <br>

Display the content of a file interactively. <br>
less file.txt  <br>

13. head
Display the first few lines of a file. <br>
head file.txt <br>

14. tail <br>

Display the last few lines of a file. <br>

tail file.txt <br>

15. nano/vi <br>

Text editors for creating or modifying files. <br>

nano file.txt <br>

16. grep (Global Regular Expression Print) <br>

Search for a pattern in files. <br>
grep "pattern" file.txt  <br>

17. find <br>

Search for files and directories in a directory hierarchy. <br>

find /path/to/search -name "filename"  <br>

18. tar (Tape Archive)  <br>

Create or extract tar archives. <br>

tar -cvf archive.tar file1 file2  <br>

19. gzip  <br>

Compress or decompress files using gzip compression. <br>
gzip file.txt  <br>

20. gunzip  <br>

Decompress files compressed with gzip. <br>

gunzip file.txt.gz <br>

21. zip/unzip  <br>
Create or extract zip archives. <br>
zip archive.zip file1 file2  <br>

22. df (Disk Free)  <br>

Display disk space usage. <br>
df -h <br>

23. du (Disk Usage) <br>

Display file and directory space usage. <br>
du -h   <br>

24. ps (Process Status)  <br>

Display information about running processes. <br>
ps aux

25. top <br>

Display a dynamic view of system processes. <br>
top

26. kill  <br>

Terminate a process.  <br>
kill -9 PID

27. chmod (Change Mode)  <br>

Change file permissions. <br>
chmod 755 file.txt  <br>

28. chown (Change Owner)  <br>

Change file owner and group. <br>
chown user:group file.txt <br>

29. ps aux  <br>

Display detailed information about all running processes. <br>
ps aux   

30. bg (Background) <br>

Run a command in the background. <br>
command &

31. fg (Foreground) <br>

Bring a background process to the foreground.  <br>
fg

32. jobs  <br>

Display the status of background jobs. <br>

jobs

33. ping  <br>

Test network connectivity. <br>
ping google.com

34. ifconfig  <br>

Display or configure network interfaces. <br>
ifconfig

35. netstat <br>

Display network connections and routing tables.  <br>
netstat -an  <br>

36. wget
Download files from the internet.  <br>

wget http://example.com/file.zip  <br>

37. curl   <br>

Transfer data with URLs. <br>
curl -O http://example.com/file.txt <br>

38. scp (Secure Copy) <br>

Copy files securely over SSH.  <br>

 scp file.txt user@remote:/path/to/destination <br>

39. ssh

Connect to a remote server securely. <br>

ssh user@remote  <br>

40. uname  <br>
Display system information. <br>
uname -a

41. date
Display or set the system date and time. <br>
date

42. cal (Calendar) <br>
Display a calendar. <br>
cal

43. uptime <br>

Display how long the system has been running. <br>
uptime

44. passwd <br>

Change user password. <br>
passwd

45. useradd <br>

useradd newuser <br>

46. userdel   <br>
Delete a user. <br>
userdel olduser

47. passwd  <br>

Change user password. <br>

passwd username

48. sudo <br>

Execute a command with administrative privileges. <br>
sudo command

49. chroot  <br>

Run a command or interactive shell with a different root directory. <br>
chroot /new/root /bin/bash

50. free  <br>

Display amount of free and used memory. <br>
free -h

51. df -h  <br>

Display disk space usage in a human-readable format.  <br>
df -h

52. lsblk  <br>

List block devices.  <br>
lsblk

53. fdisk <br>

Manipulate disk partition table. <br>
fdisk /dev/sdX

54. mount/umount  <br>

Mount or unmount filesystems.   <br>
mount /dev/sdX1 /mnt

55. ps aux | grep [process] <br>

Find information about a specific process. <br>

ps aux | grep process_name

56. killall  <br>
Kill processes by name.  <br>
killall process_name

57. hostname  <br>

Display or set the system's hostname. <br>
hostname

58. echo  <br>

Display a message or redirect output.  <br>
echo "Hello, World!"

59. history <br>

Display command history. <br>
history

60. shutdown  <br>

Shut down or restart the system. <br>
shutdown -h now
