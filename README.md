# vagrant-dotnet
.NET Core dev environment, built with Vagrant and Ansible.

# Overview

- Based on Arch Linux x86_64 ([terrywang/archlinux](https://app.vagrantup.com/terrywang/boxes/archlinux))
- Includes:
  - Ansible
  - Mono
  - .NET Core 2
  - .NET Tools:
    - `dotnet-dev-certs`
    - `dotnet-aspnet-codegenerator`
  - HTTPS certificates
  
# Preresquities

Grab [Vagrant](https://www.vagrantup.com). That's it.

# Usage

```
vagrant up
vagrant ssh
```

And you'll be up and running in minutes.

# License

TBD
