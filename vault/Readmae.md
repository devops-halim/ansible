## vault
1. ansible-vault encrypt vars/api_key.yml
2. ansible-playbook -i inventory main.yml --ask-vault-pass
3. ansible-playbook -i inventory main.yml --vault-password-file /home/user/.ansible/my_api_key.txt
4. ansible-vault decrypt vars/api_key.yml  
5. ansible-vault rekey vars/api_key.yml  chang the PW for vault
