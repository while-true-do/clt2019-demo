<!-- Header (auto generated) -->
![](https://img.shields.io/github/license/while-true-do/clt2019-demo.svg?style=flat)
![](https://img.shields.io/github/issues/while-true-do/clt2019-demo.svg?style=flat)

# clt2019-demo
<!-- ./Header (auto generated) -->
Repository to publish the demo "Deploy Nextcloud with Ansible" for CLT2019.

## Motivation

[while-true-do.io](https://while-true-do.io) is participating at
[Chemnitzer Linux-Tage 2019](https://chemnitzer.linux-tage.de/2019/de).

## Description

Our presentation is the
[Ansible Community Booth](https://chemnitzer.linux-tage.de/2019/de/programm/beitrag/177), supported from [Ansible](https://www.ansible.com).

In this repository you can find, used Ansible Playbooks and other files.

Be aware, that this playbook is not sufficient for any productive use. It is
only to show some features for users, which are not comfortable with Ansible.

## Requirements

To use the playbooks, you will need a working Ansible Environment.

## Installation

Install from git:

```
git clone https://github.com/while-true-do/clt2019-demo.git
```

## Usage

You need to edit the inventory and adjust it to your needs.

```
vi inventories/nc/inventory
```

Afterwards, you can use ansible to run the playbook.

```
ansible-playbook -K -i inventories/nc/inventory site.yml
```

## Testing

Most of the "generic" tests are located our
[Test Library](https://github.com/while-true-do/test-library). Tests and
instructions for a single repository are located in the
[Test Directory](./tests).

## Contribute

Thank you so much for considering to contribute. We are very happy, when somebody
is joining the hard work. Please fell free to open
[Bugs, Feature Requests](https://github.com/while-true-do/clt2019-demo/issues) or
[Pull Requests](https://github.com/while-true-do/clt2019-demo/pulls) after reading the [Contribution Guideline](https://github.com/while-true-do/doc-library/blob/master/documents/CONTRIBUTING.md).

## License

This work is licensed under a [BSD-3-Clause License](https://opensource.org/licenses/BSD-3-Clause).

## Contact

-   Site <https://while-true-do.io>
-   Twitter <https://twitter.com/wtd_news>
-   Code <https://github.com/while-true-do>
-   Mail [hello@while-true-do.io](mailto:hello@while-true-do.io)
-   IRC [freenode, #while-true-do](https://webchat.freenode.net/?channels=while-true-do)
-   Telegram <https://t.me/while_true_do>

<!-- ./Footer (auto generated) -->
