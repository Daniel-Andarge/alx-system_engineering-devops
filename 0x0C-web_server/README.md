# Project 0x0C. Web server 📚

## What is a Child Process?
Although it may sound like something out of a parenting handbook or a psychological journal, the term child process actually has nothing to do with human development. If you run a Unix or Linux dedicated server, you have likely encountered child processes without even knowing it. Therefore, it is good to know what child processes are and how they work.

A child process is a process created by another process. The creator process is properly called the “parent process”. The benefit of a child process is that it can start or stop at will without affecting the parent process. The child process is, however, is typically dependent on the parent process. If the parent process dies, the child process becomes an orphan process.


### 📋 Requirements
***
* Allowed editors: `vi`, `vim`, `emacs`
* Files will be interpreted/compiled on Ubuntu 16.04 LTS
* Bash script files must be executable
* Bash script must pass Shellcheck (version 0.3.7) without any error
* The second line of all your Bash scripts should be a comment explaining what is the script doing
* You can’t use systemctl for restarting a process

### 🎨 Style
***
* Code should use the PEP 8 style (version 2.7.*).

### 🎯 Tasks
***
Mandatory:
| Files | Description |
| --- | --- |
| [0-transfer_file]() | Bash script that transfers a file from our client to a server. |
| [1-install_nginx_web_server]() | Install nginx web server. |
| [2-setup_a_domain_name]() | Setup a domain name. |
| [3-redirection]() | Configure your Nginx server so that /redirect_me is redirecting to another page. |
| [4-not_found_page_404]() | Configure your Nginx server to have a custom 404 page that contains the string Ceci n'est pas une page. |
