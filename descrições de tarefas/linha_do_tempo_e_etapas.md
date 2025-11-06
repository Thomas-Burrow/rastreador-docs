## Subetapas do etapa oficina
Ver com o grupo do banco de dados para criar uma tabela de subetapas
que contem
* Nome da etapa
* Tempo esperado
* possivelmente tipo de mecânico que realiza etapa
e uma tabela que relaciona esses etapas com a ordem de serviço:
* Ordem de serviço
* Subetapa
* Indice da etapa
* Mecanico atribuido para etapa
TODO: importar etapas para este sistema

## Visualizar etapas já realizadas
Ver com o grupo de banco de dados para criar uma tabela para armazenar eventos
Essa tabela provavelmente deve conter por linha:
* Usuário que criou evento
* Ordem de serviço para evento
* timestamp do evento
* qual evento é
1. Mostrar, em ordem cronológica esses eventos de forma legivel para humanos

## Programando as etapas
Com as tabelas de etapas e usuarios, mostrar um seletor de etapa e mecânico para associar para esta etapa, e adicionar conjunto para tabela.
Idealmente mostrar um autofill com o nome dos mecanicânicos relevantes (precisa de javascript, perguntar para grupo de interface?).
Possivelmente permitir reordenar etapas (fazer um update com novo indices para todas as etapas da ordem de serviço?)