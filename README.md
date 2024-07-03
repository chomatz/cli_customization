# cli_customization
ansible role for customizing the command line interface

## requirements
requires the following role(s):
- [text_editor](https://github.com/chomatz/text_editor)


## variables

## dependencies

## examples
```
- name: install powerline
  ansible.builtin.include_role:
    name: cli_customization
    tasks_from: powerline_install.yml

```
