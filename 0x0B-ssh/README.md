0x0B. SSH
Project done during Full Stack Software Engineering studies at Alx-Holberton School. It aims to learn about what is a SSH, how to create an SSH RSA key pair and how to connect to a remote host using SSH.

Technologies
Scripts written in Bash 4.3.11(1)
Tested on Ubuntu 14.04 LTS
Puppet 3.8
Resources📚
Read or watch:

What is a (physical) server - text
What is a (physical) server - video
SSH essentials
SSH Config File
Public Key Authentication for SSH
How Secure Shell Works
SSH Crash Course
Learning Objectives💡
What you should learn from this project:

What is a server
Where servers usually live
What is SSH
How to create an SSH RSA key pair
How to connect to a remote host using an SSH RSA key pair
The advantage of using #!/usr/bin/env bash instead of /bin/bash
Files
Filename	Description
0-use_a_private_key	Uses ssh to connect to a server using a private key previously generated
1-create_ssh_key_pair	Creates an RSA key pair
2-ssh_config	SSH client configuration using a private key and refusing to authenticate using a password
100-puppet_ssh_config.pp	Sets up the client SSH configuration file to connect to a server without typing a password
