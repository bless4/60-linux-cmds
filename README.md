# 60-linux-cmds

## Here's a list of 60 Linux commands along with examples of how they are used:

1. ls (List)

List files and directories in the current directory.
ls

2. pwd (Print Working Directory)

Print the current working directory.
pwd

3. cd (Change Directory)
 Change directory.

cd /path/to/directory

4. cp (Copy)

Copy files or directories.
cp file.txt /path/to/destination

5. mv (Move/Rename)

Move or rename files or directories.
mv file.txt newfile.txt

6. rm (Remove/Delete)

Remove files or directories.

rm file.txt

7. mkdir (Make Directory)

Create a new directory.

mkdir new_directory

8. rmdir (Remove Directory)
Remove an empty directory.

 rmdir empty_directory
9. touch

Create an empty file or update the access/modification time.

touch new_file.txt

10. cat (Concatenate)

Display the content of files.

cat file.txt

11. more

Display the content of a file one screen at a time.

more file.txt

12. less

Display the content of a file interactively.
less file.txt

13. head
Display the first few lines of a file.
head file.txt

14. tail

Display the last few lines of a file.

tail file.txt

15. nano/vi

Text editors for creating or modifying files.

nano file.txt

16. grep (Global Regular Expression Print)

Search for a pattern in files.
grep "pattern" file.txt

17. find

Search for files and directories in a directory hierarchy.

find /path/to/search -name "filename"

18. tar (Tape Archive)

Create or extract tar archives.

tar -cvf archive.tar file1 file2

19. gzip

Compress or decompress files using gzip compression.
gzip file.txt

20. gunzip

Decompress files compressed with gzip.

gunzip file.txt.gz

21. zip/unzip
Create or extract zip archives.
zip archive.zip file1 file2

22. df (Disk Free)

Display disk space usage.
df -h

23. du (Disk Usage)

Display file and directory space usage.
du -h

24. ps (Process Status)

Display information about running processes.
ps aux

25. top

Display a dynamic view of system processes.
top

26. kill

Terminate a process.
kill -9 PID

27. chmod (Change Mode)

Change file permissions.
chmod 755 file.txt

28. chown (Change Owner)

Change file owner and group.
chown user:group file.txt

29. ps aux

Display detailed information about all running processes.
ps aux

30. bg (Background)

Run a command in the background.
command &

31. fg (Foreground)

Bring a background process to the foreground.
fg

32. jobs

Display the status of background jobs.

jobs

33. ping

Test network connectivity.
ping google.com

34. ifconfig

Display or configure network interfaces.
ifconfig

35. netstat

Display network connections and routing tables.
netstat -an

36. wget
Download files from the internet.

wget http://example.com/file.zip

37. curl

Transfer data with URLs.
curl -O http://example.com/file.txt

38. scp (Secure Copy)

Copy files securely over SSH.

39. scp file.txt user@remote:/path/to/destination
ssh

Connect to a remote server securely.

ssh user@remote

40. uname
Display system information.
uname -a

41. date
Display or set the system date and time.
date

42. cal (Calendar)
Display a calendar.
cal

43. uptime

Display how long the system has been running.
uptime

44. passwd

Change user password.
passwd

45. useradd
Copy code
useradd newuser

46. userdel
Delete a user.
userdel olduser

47. passwd

Change user password.

passwd username

48. sudo

Execute a command with administrative privileges.
sudo command

49. chroot

Run a command or interactive shell with a different root directory.
chroot /new/root /bin/bash

50. free

Display amount of free and used memory.
free -h

51. df -h

Display disk space usage in a human-readable format.
df -h

52. lsblk

List block devices.
lsblk

53. fdisk

Manipulate disk partition table.
fdisk /dev/sdX

54. mount/umount

Mount or unmount filesystems.
mount /dev/sdX1 /mnt

55. ps aux | grep [process]

Find information about a specific process.

ps aux | grep process_name

56. killall
Kill processes by name.
killall process_name

57. hostname

Display or set the system's hostname.
hostname

58. echo

Display a message or redirect output.
echo "Hello, World!"

59. history

Display command history.
history

60. shutdown

Shut down or restart the system.
shutdown -h now
