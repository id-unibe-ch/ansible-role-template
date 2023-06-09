# template

An Ansible role that manages template. Currently the role has the following
features:

* template feature 1
* template feature 2
* template feature 3

## Requirements

No prerequisites necessary at the moment.

## Role Variables

Available variables are listed below, along with default values (see also `defaults/main.yml`):

> **Note:**

> * All variabled should start with the role name (e.g. `template_`)
> * OS-specific variables should be set in the `vars` directory and start with `__template_`

### template_variable

    template_variable: "42"

Specifies the number that template uses

## Example Playbook

Including an example of how to use your role (for instance, with variables passed
in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: << .Namespace >>.<< .Name >>
           vars:
             << .Name >>_x: 42

## Compatibility

This role has been written for and tested on and is therefore compatible with:
<< range .Platforms >>
<< if eq . "rockylinux8" >> * Rocky-8<<end>>
<< if eq . "rockylinux9" >> * Rocky-9<<end>>
<< if eq . "ubuntu2004" >> * Ubuntu 20.04<<end>>
<< if eq . "ubuntu2204" >> * Ubuntu 22.04<<end>>
<< end >>

## License

<< .License >>

## Author Information

The role was created in 2023 by the << .Author >> at << .Company >>
