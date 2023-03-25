# Configuration management

Project done during Full Stack Software Engineering studies at **ALX AFRICA SE School**. This project is an introduction to Configuration Management, this project contains very basic Puppet manifests. In this project, I started working with Puppet as a configuration management
tool. I practiced writing Puppet manifest files to create a file, install a
package, and execute a command.

## Table of contents

Files | Description
----- | -----------
[0-create_a_file.pp](./0-create_a_file.pp) | Puppet manifest that creates a file in the /tmp directory
[1-install_a_package.pp](./1-install_a_package.pp) | Puppet manifest that installs puppet-lint
[2-execute_a_command.pp](./2-execute_a_command.pp) | Puppet manifest that kills a process named killmenow
[killmenow](./killmenow) | Test bash script to kill with manifest 2-execute_a_command.pp

## Tasks :page_with_curl:

* **0. Create a file**
  * [0-create_a_file.pp](./0-create_a_file.pp): Puppet manifest file that
  creates a file `school` in the `/tmp` directory.
    * File permissions: `0744`.
    * File group: `www-data`.
    * File owner: `www-data`.
    * File content: `I love Puppet`.

* **1. Install a package**
  * [1-install_a_package.pp](./1-install_a_package.pp): Puppet manifest file
  that install `flask` from pip3.

* **2. Execute a command**
  * [2-execute_a_command.pp](./2-execute_a_command.pp): Puppet manifest file
  that kills the process `killmenow`.


  ## Autor

```Bright otu```
