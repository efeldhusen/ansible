Ansible
=======

Ansible for Eric Feldhusen's Personal Use

## Installation

Checkout the application from GitHub:

    $ git clone git@github.com:efeldhusen/ansible.git
    $ cd ansible

## Usage

Dry-run of Ansible playbook

    $ ansible-playbook playbook_name.yml --check

Actual run of Ansible playbook

    $ ansible-playbook playbook_name.yml

Run a command across machines

    $ ansible servers -a "grep '001C7BEEBC9A' /usr/local/nagios/etc/conf.d/modems.cfg" -u joebob

### Ansible Galaxy Usage

    $ cd ansible
    $ ansible-galaxy install username.playbook

### Ansible Galaxy Example

    $ cd ansible
    $ ansible-galaxy install geerlingguy.nginx


## Contributing

1. Fork it ( https://github.com/efeldhusen/ansible/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
