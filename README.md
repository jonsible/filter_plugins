# jonsible.filter-plugins

[![Build Status](https://travis-ci.com/jonsible/filter-plugins.svg?branch=master)](https://travis-ci.com/jonsible/filter-plugins)
[![Galaxy](https://img.shields.io/badge/galaxy-jonsible.filter--plugins-blue.svg)](https://galaxy.ansible.com/jonsible/filter-plugins/)

Role to include custom filter plugins

## Requirements

None.

## Role Variables

### Default usage

As default filters is installed and running.
If you want to adapt this to your needs look at the [Advanced usage](#advanced-usage) section.

### Advanced usage

For more advanced usage the following variables are available:
```yaml
# see defaults/main.yml
```

## Dependencies

None

## Example Playbook

Install filters with the default settings
```yaml
- hosts: all
  roles:
     - role: jonsible.filter-plugins
```

## License

MIT

## Author Information

This role was created in 2020 by [Jonathan Scherrer].
