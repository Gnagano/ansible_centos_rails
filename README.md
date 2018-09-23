# Install rails with ruby in rbenv

===

Ansible Role: Install rails with ruby in rbenv

## Requirements

- ruby version is `>= 2.2`

- The variables `rbenv_install_dir` and `rails_required_libraries` are required.
  In default, there are defined in `defaults/main.yml`

## Role Variables

- rbenv_install_dir

  The variable `rbenv_install_dir` is where rbenv is installed.
  The default value is `/opt/anyenv/envs/rbenv`.

- rails_required_libraries

  The libraries required to install rails.

- ruby_version

  The variable `ruby_version` is the version you want to install.
  The default value is `4.1.6`. If you do not define, version `4.1.6` will be installed.
