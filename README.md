- [About](#about)
- [Installation](#installation)

# About

Ansible role to disable SSH password and root login

# Installation

Add the following to `requirements.yml`:

```
- src: https://github.com/carbonique/ansible-role-ssh.git
  scm: git
  name: ssh
  version: #Leave empty for latest. To download a specific version: use the tag as listed in repo
```

For system wide installation:
`ansible-galaxy install -r requirements.yml`

For installation to the current directory:
`ansible-galaxy install --roles-path . -r requirements.yml`

