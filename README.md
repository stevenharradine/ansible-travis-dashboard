# ansible-travis-dashboard
Ansible role for setting up and running Travis Dashboard

[![licence](https://img.shields.io/badge/licence-ISC-blue.svg)](https://opensource.org/licenses/ISC)

Tunables
--------
* `travis_dashboard_user` (string) - user to run as
* `travis_dashboard_directory` (string) - the diectory to clone too
* `travis_dashboard_install_name` (string) - the folder name to clone into
* `travis_dashboard_organization` (string) - the organization to create the dashboard for
* `travis_dashboard_use_node_server` (boolean) - yes the built in standalone node server
* `travis_dashboard_github_token` (string) - github token, should have read access to repositories

Example Playbook
----------------
    - hosts: servers
      roles:
         - role: stevenharradine.travis-dashboard

Contributors
------------
* Steven Harradine
