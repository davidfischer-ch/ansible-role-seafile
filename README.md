# Ansible Role Seafile

Library of Ansible plugins and roles for deploying various services.
See [ansible-roles](https://github.com/davidfischer-ch/ansible-roles) for additional documentation.

This repository hosts the role Seafile and may depend of other roles and plugins of the library.

## Status

Not (yet) implemented:

* Handling of multi-tier architecture (database external host, ...)

* Role actions such as configure, ...
* Mounting the data directory. I think this roles should not take this responsibility. When deploying more than one web host, make sure your PlayBook mount the data directory prior to calling this role.

## Dependencies

See [meta](meta/main.yml).

## Variables

TODO VARIABLES

## License

See [LICENSE.rst](LICENSE.rst).

## Authors

See [AUTHORS](AUTHORS).

2014-2022 - David Fischer
