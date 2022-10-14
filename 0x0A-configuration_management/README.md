# Project 0x0A. Configuration management 📚
 Configuration management can drastically improve the integrity of servers over time by providing a framework for automating processes and keeping track of changes made to the system environment.

 When a server goes offline due to unknown circumstances, it might take several hours to properly audit the system and find out what really happened. In scenarios like this, deploying a replacement server is usually the safest way to get your services back online while a detailed inspection is done on the affected server. With configuration management and automation, this can be done in a quick and reliable way.

 In this work, we will see how to implement a configuration management strategy in practice using Puppet as tool.


### 📋 Requirements
***
* Allowed editors: `vi`, `vim`, `emacs`.
* Files will be interpreted/compiled on Ubuntu 20.04 LTS.
* Puppet manifests must pass `puppet-lint` version 2.1.1 without any errors.
* Puppet manifests must run without error.
* Puppet manifests first line must be a comment explaining what the Puppet manifest is about.
* Puppet manifests files must end with the extension .pp.

### 🎯 Tasks
***
#### Mandatory:
| Files | Description |
| --- | --- |
| [0-create_a_file.pp]() | Using Puppet, create a file in `/tmp`. |
| [1-install_a_package.pp]() | Using Puppet, install `puppet-lint`. |
| [2-execute_a_command.pp]() | Using Puppet, create a manifest that kills a process named `killmenow`. |
