# Ansible role to configure GitLab App servers

## Variables

`gitlab_access_url` - External loadbalancer fqdn

`gitlab_db_instance_address` - Database connection address

`gitlab_db_instance_username` - Database access user

`gitlab_db_instance_password` - Database access user password

`gitlab_regis_endpoint` - Redis connection address

`gitlab_token` - Token string for internal services communication (Gitaly, etc...)
