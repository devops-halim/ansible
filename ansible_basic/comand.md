1. ansible-vault create learn_ansible.yaml
2. ansible-vault edit learn_ansible.yaml
3. ansible-playbook learn_ansible.yaml -i inventory --ask-vault-pass
4. ansible-playbook learn_ansible.yaml -i inventory --vault-password-file password.txt
5. ansible-playbook registering-variables.yml -i inventory  -v

6. ansible-galaxy init test-role-1