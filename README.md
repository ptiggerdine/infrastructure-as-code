# Infrastructure as Code
This project is a skeleton for infrastructure as code implementations. You can use it to quickly bootstrap your own infrastructure as code projects. Inspired from abhishektiwari

The seed contains a sample infrastructure as code implementation which includes,

- Git for versioning infrastructure as code 
- Terraform, CloudFormation, YAML and Python Scripts for infrastructure provisioning
- Puppet/Chef for configuration management 
- Docker for container management
- Vagrant for local testing and development using Puppet/Chef solo
- Shared for scripted install of provisioning serivces, puppet and continuous integration of infrastructure  

# Prerequisites

## Git
You need Git to clone this seed repository. You can get git [here](http://git-scm.com/). For the Puppet modules and Chef cookbooks, we are using [Git submodules](https://git-scm.com/docs/git-submodule).

### Updating submodules

All submodules,

```
git submodule foreach --recursive git pull
```

A specific module,

```
cd your/submodule
git pull origin master
```

## Virtualbox and Vagrant

You will need to install Virtualbox and Vagrant.

# I don't want ...
I don't want some of the folders in this seed, well just add folder name or pattern in `.gitignore` - Love to understand how this works. Create local repo; create .gitignore; clone orginal repo?

