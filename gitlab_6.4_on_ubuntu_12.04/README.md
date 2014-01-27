ansible-playbooks
=================

ansible playbooks for servers

- change site ip in stage.
- ansible-playbook -i stage gitlab.yml

check after play in /home/git/gitlab

    sudo -u git -H bundle exec rake gitlab:env:info RAILS_ENV=production
    sudo -u git -H bundle exec rake gitlab:check RAILS_ENV=production

