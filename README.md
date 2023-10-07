# **template-ansible**
===========================

Description of a ansible playbook

*Requirements*
--------------

Requirements for this ansible

*Role Variables*
----------------

This is a list of required and optinal variables and parameters for this role:

| **Parameter**                  | **Description**            | **Type** |     **Default**     |**Required**|
|--------------------------------|----------------------------|----------|:-------------------:|:----------:|
| variable_input        | description             |  type  | default value          |     yes/no     |

*Dependencies*
--------------

Dependencies for this ansible role.

*Example Playbook*
------------------

This is an example of use role with optionals and required parameters:

*playbook-file.yml*
```yaml
    - hosts: example
      roles:
        - example-role
      vars:
        var_input_1: XXXXXXXX
        var_input_2: 00000000
```

These are some examples of the use of this playbook with the different tags that can be used in this role:

Install and configure for example
```bash
  ansible-playbook -i inventory playbook-file.yml
```
*License*
---------

MIT

*Author Information*
--------------------

This role was created in 2023 by:

- Fernando Hernández San Felipe (ironwolphern@outlook.com)
