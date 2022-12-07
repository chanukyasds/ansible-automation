# rolegrants

Code to automate granting / revoking access to users in database for multiple hosts

- clean code with easy understanding to add future requests

- host level variables are declared which can be filtered by {{ inventory_hostname }} and can run for multiple databases and schemas.

- won't run on existing access of users 

- check for user existing and create it on the flow




# hba conf deployment :

Ansible templates used to deploy pg_hba.conf into hosts and reload based on changes in it.

group_vars and handlers has been used.
