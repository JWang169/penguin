## Set up Ubuntu 
Create new user:
```
$ sudo adducer newUser
```              
Add to sudo group:
```
$ sudo usermod -aG sudo newUser
```
Check user group:
```
$ groups newUser
```
Check current user:
```
$whoami 
```
Switch to another user:
```
$sudo su - newUser
```
