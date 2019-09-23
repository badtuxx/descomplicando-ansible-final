# descomplicando-ansible
**Seja bem-vindo ao último exercicio do treinamento Descomplicando o Ansible.**

Temos esses playbooks que utilizamos no decorrer do treinamento, porém o estagiario acabou fazendo algumas alterações e o playbook parou de funcionar. :/

Sua missão é fazer com que esses playbooks possam ser executados e assim criando o nosso cluster Kubernetes.

Além de arrumar o que está quebrado, você terá que garantir algumas premissas básicas para o projeto, como:
- Toda informação sensível deverá estar protegida pelo Vault
- Nosso playbook deverá suportar nossas 03 ambientes, testing, staging e production. Portanto as variaveis de ambiente, secrets e outras informações deverão ser configuradas levando isso em consideração.
- O cluster Kubernetes deverá ser formado por 3 nodes, com os nomes kubernetes-$ENVIRONMENT-0[1-3]. Exemplo: kubernetes-production-01
- Todas as tasks deverão ter tags e essas tags referenciadas nos arquivos main.yml do playbook
- Quer fazer o deploy da app v2 e usar o canary? Legal! Mas e se der erro? Já tem o rollback? Ainda não? Putz, que triste, terá que criar.
- Todo playbook deverá ter um README.md com a descrição do que ele faz.

Pronto, super simples, não?!?

Lembre-se, para que você receba a sua badge, você deverá finalizar esse exercicio.
Terminou? Criar um repo no Github e nos envie o endereço para o email jeferson@linuxtips.com.br
