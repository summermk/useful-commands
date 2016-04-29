# CentOS 

## List Users
```
$ cat /etc/passwd
```

## Add User

```
$ useradd <username>
$ passwd <username> 
Changing password for user noname.
New password: 
Retype new password: 
passwd: all authentication tokens updated successfully.
```

## Reset password 
### Reset password for current user
```
$ passwd
```

### Reset password for user
```
# passwd user_name
Enter new UNIX password:
Retype new UNIX password:
passwd: password updated successfully
```
