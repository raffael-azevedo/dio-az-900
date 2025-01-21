# Resumo do lab:
- Vi uma tabela de exemplo de SLA da criação de algum recurso. Foi falado sobre o aumento do decimal do SLA, ou seja, quanto mais próximo de 100%, mais caro, porém provável que fique menos tempo offline ao longo do uso. Ao criar um serviço, precisa-se saber de antemão qual o tempo aceitável que este serviço fique indisponível.

- Falou-se sobre estratégias de disponibilidade (no menu de criação de máquina virtual). Cada uma tem por objetivo ser mais eficiente a depender do resultado a ser obtido. Falou-se sobre disponibilidade em zonas distintas e outros modelos (menos comentados). 

- Também vi sobre a replicação de armazenamento, que basicamente torna os dados redundantes ao criar, o que gera efetivamente mais custos, porém o SLA é diminuído (porque obviamente, caso o serviço fique indisponível num lugar, é rapidamente retomado por ter redundância).
