1. User Accounts in Linux
Types of users:
Root user – Superuser with full privileges
System users – Used by services (apache, nginx, mysql)
Normal users – Human users for login

2. Important Files
File Purpose
/etc/passwd	Stores user account information
/etc/shadow	Stores encrypted passwords
/etc/group	Stores group information

3. Create a User
sudo useradd username

4. Set or Change User Password
sudo passwd username

5. User Information
Check user details
id username
List logged-in users
who

6. Delete a User
   sudo userdel username

7. Groups in Linux
Groups are used to assign permissions to multiple users at once.
Types of groups
Primary group – Assigned at user creation
Secondary group – Additional groups

8. Create a Group
sudo groupadd groupname

9. Add User to a Group
sudo usermod -aG groupname username

10. Change Primary Group
sudo usermod -g groupname username

11. Check Group Information
groups username

12. Delete a Group
sudo groupdel groupname

13. Lock and Unlock a User Account
Lock user
sudo usermod -L username