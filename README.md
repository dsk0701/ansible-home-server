# ansible home server

## install galaxy roles

    $ ansible-galaxy install --force -r requirements.yml

## execute playbook

    $ ansible-playbook -i {develop|production} site.yml --private-key=~/.ssh/XXX --ask-become-pass

