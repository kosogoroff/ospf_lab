# Репозиторий ля развёртывания стенда выполненного домашнего задания по занятию "33 - Динамическая маршрутизация OSPF"

Для развёртывания стенда введите следующие команды:

```
git clone https://github.com/kosogoroff/ospf_lab.git
cd ospf_lab
vagrant up
```

Для создания репозитория использовались следующие команды:

```
[admin_insta11@mv334 ospf_lab]$ git init
подсказка: Using 'master' as the name for the initial branch. This default branch name
подсказка: is subject to change. To configure the initial branch name to use in all
подсказка: of your new repositories, which will suppress this warning, call:
подсказка: 
подсказка: 	git config --global init.defaultBranch <name>
подсказка: 
подсказка: Names commonly chosen instead of 'master' are 'main', 'trunk' and
подсказка: 'development'. The just-created branch can be renamed via this command:
подсказка: 
подсказка: 	git branch -m <name>
Инициализирован пустой репозиторий Git в /home/admin_insta11/ospf_lab/.git/
[admin_insta11@mv334 ospf_lab]$ 
[admin_insta11@mv334 ospf_lab]$ git add .
[admin_insta11@mv334 ospf_lab]$ 
[admin_insta11@mv334 ospf_lab]$ git commit -m "first commit"
[master (корневой коммит) 4298637] first commit
 12 files changed, 549 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 Vagrantfile
 create mode 100644 ansible/ansible.cfg
 create mode 100644 ansible/hosts
 create mode 100644 ansible/playbook.yml
 create mode 100644 ansible/templates/01-netcfg.yaml
 create mode 100644 ansible/templates/daemons
 create mode 100644 ansible/templates/frr-router1.conf
 create mode 100644 ansible/templates/frr-router2.conf
 create mode 100644 ansible/templates/frr-router3.conf
 create mode 100644 ansible/templates/iptables_rules.ipv4
[admin_insta11@mv334 ospf_lab]$ 
[admin_insta11@mv334 ospf_lab]$ git branch -M main
[admin_insta11@mv334 ospf_lab]$ 
[admin_insta11@mv334 ospf_lab]$ git remote add origin https://github.com/kosogoroff/ospf_lab.git
[admin_insta11@mv334 ospf_lab]$ 
[admin_insta11@mv334 ospf_lab]$ git push -u origin main

(gnome-ssh-askpass:270861): dbind-WARNING **: 23:00:29.022: Couldn't connect to accessibility bus: Empty address ''

(gnome-ssh-askpass:270878): dbind-WARNING **: 23:00:34.414: Couldn't connect to accessibility bus: Empty address ''
Перечисление объектов: 16, готово.
Подсчет объектов: 100% (16/16), готово.
При сжатии изменений используется до 24 потоков
Сжатие объектов: 100% (14/14), готово.
Запись объектов: 100% (16/16), 6.19 КиБ | 1.24 МиБ/с, готово.
Total 16 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/kosogoroff/ospf_lab.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
[admin_insta11@mv334 ospf_lab]$ 

```
