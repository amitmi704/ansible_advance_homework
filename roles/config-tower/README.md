Role Name
=========

A brief description of the role goes here.
Configure Ansible Tower:
  - Create Homework project
  - Create Inventories
  - Create Groups
  - Add Credentials
  - Create Templates

Requirements
------------

Requires the following OpenTLC services deployed:

Ansible Advanced - Homework
Ansible Advanced - OpenStack
Ansible Advanced - Three Tier App

Role Variables
--------------

Set the following environment variables:

TOWER_GUID: OpenTLC GUID of the Ansible Tower deployment
OSP_GUID: OpenTLC GUID of the OpenStack deployment
OPENTLC_LOGIN: OpenTLC Username
OPENTLC_PASSWORD: OpenTLC Password
GITHUB_REPO: GitHub Repo URL for the "Ansible Advance Homework" project
REGION: Cloud region
RH_MAIL_ID: RedHat Login Email Address

Dependencies
------------

N/A

Example Playbook
----------------

No Playbook level settings expected to call role:

- hosts: localhost
  gather_facts: false
  become: yes
  roles:
    - config-tower

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
