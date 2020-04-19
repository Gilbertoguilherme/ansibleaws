Criação de maquinas via Ansible

O primeiro main inclui o hosts e faz a chamada para o roles

O arquivo de hosts fica em branco, as informações vão ser escritas após a criação das maquinas

Dentro de ec2 esta a estrutura com somente diretorio vars e task

Main dentro de task faz toda a criação das maquinas e dentro de vars as variaveis da sua ec2

referências
https://docs.ansible.com/ansible/latest/user_guide/playbooks_delegation.html
https://docs.ansible.com/ansible/latest/modules/ec2_group_module.html
https://docs.ansible.com/ansible/latest/modules/ec2_module.html

Uma refêrencia em especial semanadevops
https://medium.com/@amaurybsouza/ansible-2b38be85b704

