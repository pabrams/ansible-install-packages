# automating package installs with ansible

## install ansible

`yay -S ansible`

## execute playbooks

Upgrading the system requires root user,
`sudo ansible-playbook -u ansible upgrade-update.yml -vvv`

The site.yml playbook uses yay, so doesn't require sudo.
`ansible-playbook -u ansible site.yml -vvv`
