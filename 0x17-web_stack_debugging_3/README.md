# Project 0x17. Web stack debugging #3 📚

### 📋 Requirements
***
* Files will be interpreted on Ubuntu 14.04 LTS
* Puppet manifests must pass `puppet-lint` version 2.1.1 without any errors
* Puppet manifests must run without error
* Your Puppet manifests first line must be a comment explaining what the Puppet manifest is about
* Your Puppet manifests files must end with the extension .pp
* Files will be checked with Puppet v3.4

### More Info
***
#### Install `puppet-lint`

```shell
apt-get install -y ruby
gem install puppet-lint -v 2.1.1
```

### 🎯 Tasks
***
Mandatory:
| Files | Description |
| --- | --- |
| [0-strace_is_your_friend.pp]() | Fix 500 error when a GET HTTP method is requested to Apache web server. |
