# Самоконтроль выполнения задания

1. group_vars/all
2. ansible-playbook -i /invetory/test.yml site.yml
3. ansible-vault encrypt <file_name>
4. ansible-vault decrypt <file_name>
5. ansible-vault view <file_name> (и ввести пароль)
6. ansible-playbook -i /invetory/test.yml site.yml --ask-vault-pass
7. winrm
8. ansible-doc -t connection ssh
9. remote_user
