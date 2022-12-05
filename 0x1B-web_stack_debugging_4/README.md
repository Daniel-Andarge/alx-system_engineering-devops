
# Project 0x1B. Web stack debugging #4 📚

### 📋 Requirements
***
* Allowed editors: `vi`, `vim`, `emacs`
* Files will be interpreted on Ubuntu 14.04 LTS
* Your Puppet manifests must pass puppet-lint version 2.1.1 without any errors
* Your Puppet manifests must run without error
* Your Puppet manifests first line must be a comment explaining what the Puppet manifest is about
* Your Puppet manifests files must end with the extension .pp

### 🎨 Style
***
* Files will be checked with Puppet v3.4

### Install `puppet-lint
***
```bash
$ apt-get install -y ruby
$ gem install puppet-lint -v 2.1.1
```

### 🎯 Tasks
***
Mandatory:
| Files | Description |
| --- | --- |
| [0-the_sky_is_the_limit_not.pp]() | I will make 2000 requests to my server with 100 requests at a time. We can see that 943 requests failed, let’s fix our stack so that we get to 0, and remember that when something is going wrong, logs are your best friends! |
