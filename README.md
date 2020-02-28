# jonsible.filter_plugins

[![Build Status](https://travis-ci.com/jonsible/filter_plugins.svg?branch=master)](https://travis-ci.com/jonsible/filter_plugins)
[![Galaxy](https://img.shields.io/badge/galaxy-jonsible.filter__plugins-blue.svg)](https://galaxy.ansible.com/jonsible/filter_plugins/)

Role to include custom filter plugins

## Requirements

None.

## Role Variables

### Default usage

Add this role into your meta/main.yml to use it with your role :  
```
  dependencies:
    - jonsible.filter_plugins
```


You can then use these filters :  
```python
def dict_filter_keys(_dict, _regex): # Selects keys in _dict matching regexes in _regex (list)
def dict_strip_keys(_dict, _regex):  # Strips keys in _dict matching regexes _regex (list)
def dict_merge(_ldict, _rdict):      # Merges right dict into left dict
```
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
     - role: jonsible.filter_plugins
```

## License

GPL-3.0-or-later

## Author Information

This role was created in 2020 by [Jonathan Scherrer].
