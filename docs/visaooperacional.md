# Visão Operacional
<small>Integrado com </small> ![alt text](tags/tag_pront.svg)

Este painel permite a visualização das **Respostas de Prontidão** registradas no PRONT.  

Nesta interface, é exibido um cronograma em formato Gantt não editável, onde são representadas as sondas e suas respectivas alocações, que podem ser tarefas ou eventos.  

A cor das tarefas varia conforme a resposta de prontidão, refletindo o pior caso entre as respostas do grupo.  

## Funcionalidades

### Tooltip

Exibe informações adicionais ao passar o mouse sobre uma alocação.  

### Painel Lateral de Detalhes

Permite visualizar mais informações ao clicar sobre uma alocação. As seções disponíveis são:  

- Resposta: detalhes sobre as respostas de cada grupo.  

- Recurso: informações sobre as atividades e recursos apontados.  

- Detalhes: dados da tarefa.  

### Modo de Visualização
![alt text](icons/visualizacao_atendimento.svg)

Permite filtrar as tarefas consideradas no atendimento. As opções disponíveis são:  

- Todas as tarefas.  

- Todas as tarefas de um Grupo.  

- Todas as tarefas relacionadas a um ou mais Recursos.  

Ao aplicar um desses filtros, as cores das tarefas refletirão o pior caso de resposta dentro do conjunto filtrado.  

### Zoom
![alt text](icons/zoom.svg)

Permite ajustar a quantidade de períodos exibidos na linha do tempo.  

- Reduzir o zoom: amplia o horizonte temporal, exibindo mais anos.  

- Aumentar o zoom: detalha períodos menores, focando em um ano específico.  

### Filtro 
![alt text](icons/filtro.svg)

Permite filtrar as tarefas de acordo com as seguintes categorias:  

- Cluster

- Executante

- Bacia  

- Projeto

- Tipo de serviço

- Tipo de tarefa  

O filtro funciona como uma interseção entre as categorias selecionadas.  

### Filtro de Sondas
![alt text](icons/filtro_sonda.svg)

Permite filtrar as sondas do cronograma.

### Resumo
![alt text](icons/resumo.svg)

Permite visualizar o indicador de quantidade de tarefas por resposta de prontidão. Esse painel lateral também funciona como um filtro de tarefas.




