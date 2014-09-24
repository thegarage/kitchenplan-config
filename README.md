# TheGarage Kitchenplan Config

Kitchenplan is a small tool to fully automate the installation and configuration of an OSX workstation (or server for that matter) using Chef. But while doing so manually is not a trivial undertaking, Kitchenplan has abstracted away all the hard parts.

# Installation

```bash
$ sudo gem install kitchenplan
```

# Setup

Ensure that there is a configuration file in the git repository that matches your operating systems username (ex: `config/people/ryansonnek.yml`)

# Usage

After installing the kitchenplan gem, run the `setup` command and follow the given instructions:

```bash
$ kitchenplan setup https://github.com/thegarage/kitchenplan-config.git
$ kitchenplan provision
```

## Copyright
Copyright (c) 2014 The Garage. See LICENSE.txt for further details.
