[![Build Status](https://travis-ci.org/marvel-nccr/ansible-role-cp2k.svg?branch=master)](https://travis-ci.org/marvel-nccr/ansible-role-cp2k)

# Ansible Role: marvel-nccr.cp2k

An ansible role to install  a recent version of [CP2K](https://www.cp2k.org/) on Ubuntu.

## Installation

`ansible-galaxy install marvel-nccr.cp2k`

## Role Variables

See `defaults/main.yml`

## Example Playbook

```
- hosts: machines
  roles:
  - role: nccr-marvel.slurm
```

## Tests

This role uses [Molecule](https://molecule.readthedocs.io/en/latest/#) and
Docker for tests. Once Docker is installed, run tests using

```bash
pip install -r requirements.txt
molecule test
```

## License

MIT

## Contact

Please direct inquiries regarding Quantum Mobile and associated ansible roles to the [AiiDA mailinglist](http://www.aiida.net/mailing-list/).
