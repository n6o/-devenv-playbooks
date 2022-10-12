# virt-playbooks

[Directory layout: Ansible playbooks best practices](https://docs.ansible.com/ansible/2.9/user_guide/playbooks_best_practices.html#directory-layout)

## Run

```
$ ansible-playbook devenv.dist.yml
```

## Run with tag

```
$ ansible-playbook --tags apt,dotfiles devenv.dist.yml
```

## List tasks

```
$ ansible-playbook --list-tasks devenv.dist.yml
```

## Download playbook manually

```
$ curl -o archive/devenv.dist.yml https://raw.githubusercontent.com/n6o/virt-playbooks/main/devenv.dist.yml
```
