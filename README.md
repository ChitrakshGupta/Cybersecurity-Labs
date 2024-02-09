# Seed Labs Cybersecurity Lab activities

## Introduction
This repository contains materials and instructions for completing a cybersecurity lab activity using Seed Labs. Seed Labs provides a range of hands-on activities for learning cybersecurity concepts in a practical environment.

## Lab Objective
The objective of this lab activity is to gain practical experience in network traffic analysis using Wireshark. Participants will learn how to capture, analyze, and interpret network packets to understand network behavior and identify potential security threats.

## Requirements
To complete this lab activity, you will need:
- A computer with virtualization software installed (e.g., VirtualBox, VMware)
- Seed Labs Ubuntu VM image



## Ethical Considerations
While conducting this lab activity, it's essential to adhere to ethical guidelines and respect the privacy and security of network communications. Avoid capturing sensitive information (e.g., passwords, personal data) belonging to others and refrain from engaging in any unauthorized or malicious activities.

## Resources
- Seed Labs website: [https://seedsecuritylabs.org/](https://seedsecuritylabs.org/)
- Wireshark documentation: [https://www.wireshark.org/docs/](https://www.wireshark.org/docs/)


## DNS Attach (Commands)

### Docker Build
```
dcbuild
dcup
```

### Checking all the files
```
dockps
```

### New Terminal
```
[new terminal]
```

### DNS Server (New Terminal)
```
docksh Local-dns-servеr - 10.9.0.53
```

```
export PS1="Local-dns-servеr - 10.9.0.53:\w\n\$>"
```


### For User
```
docksh user-10.9.0.5
```

```
export PS1="user-10.9.0.5:\w\n\$>"
```


### For Attacker
```
docksh attacker-ns-10.9.0.153
```

```
export PS1="attacker-ns-10.9.0.153:\w\n\$>"
```

### For Seed Attacker
```
docksh seed-attacker
```

```
export PS1="seed-attacker:\w\n\$>"
```


### For Seed Router
```
docksh seed-router
```

```
export PS1="seed-router:\w\n\$>"
```

