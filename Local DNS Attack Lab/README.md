### Local DNS Attack Lab
[Task and Lab Description Provided by seed labs](https://drive.google.com/file/d/1JomZMVknqb_V4KyPywtDp-ISMeKqkaGF/view?usp=sharing)

[Lab Setup Zip File](https://drive.google.com/file/d/1iO9tvj1FsWJpxlGB6MMRMcksEdmDkMm3/view?usp=sharing)


## Installation
Install the [Lab Setup](https://drive.google.com/file/d/1iO9tvj1FsWJpxlGB6MMRMcksEdmDkMm3/view?usp=sharing)
in Seed Ubuntu and then unzip in some file directory.

## Setting Up a Local DNS Server

- Open the Lab Setup Folder in terminal
- For docker build  (Run this command on terminal in lab setup file directory) 

 Building Docker images or configuring components within a data center environment
``` 
dcbuild
```
For Docker on

```
dcup
```
- Open new Terminal in labsetup file directory and check all file/images of docker

```
dockps
```
## Terminal Setup for Five Machines with DNS Server, User, Attacker's Name Server, Seed Attacker, and Seed Router
- Open five terminals, each assigned to one of the following machines: local DNS server (IP: 10.9.0.53), user (IP: 10.9.0.5), attacker's name server (IP: 10.9.0.153), seed attacker, and seed router, representing the three original machines, as well as the two spoofed entities (attacker and router) for the user.

- For DNS server
```
docksh local-dns-server-10.9.0.53
```

```
export PS1="local-dns-server-10.9.0.53:\w\n\$>"
```

- For User
```
docksh user-10.9.0.5
```

```
export PS1="user-10.9.0.5:\w\n\$>"
```

- For attackers
```
docksh attacker-ns-10.9.0.153
```

```
export PS1="attacker-ns-10.9.0.153:\w\n\$>"
```

- For Seed attacker
```
docksh seed-attacker
```

```
export PS1="attacker-ns-10.9.0.153:\w\n\$>"
```

- For Seed Router
```
docksh seed-router
```

```
export PS1="user-10.9.0.5:\w\n\$>"
```








