# Escopo Atual
<small>Integrado com </small> ![alt text](tags/tag_cw_recursos.svg)

Permite visualizar o **Escopo Atual** disponível no CW Recursos. As cores indicam o nível de atendimento de Recursos (materiais e serviços).  

Nesta tela, é exibido um cronograma em formato Gantt não editável, onde são representadas as sondas e suas respectivas alocações, que podem ser tarefas ou eventos.  

A cor das tarefas varia conforme o atendimento por ID Recurso, refletindo o pior caso entre as atividades nos seguintes status:

- Atende: existem recursos disponíveis para atender a tarefa.  

- Não atende: não há recursos suficientes para atender a demanda.  

- Não calculado: tarefas no passado não são calculadas.  

## Funcionalidades

### Tooltip

Permite exibir informações adicionais ao passar o mouse sobre uma alocação.  

### Painel Lateral de Detalhes

Permite visualizar informações detalhadas ao clicar sobre uma alocação. As seções disponíveis são: 

- Identificação: exibe dados da tarefa.  

- Atendimento: apresenta informações sobre as atividades e recursos envolvidos.  

### Incluir contingentes
![alt text](icons/incluir_contingente.svg)

Permite visualizar a tabela com os recursos contingentes.  

### Visualização de Atendimento
Permite filtrar as tarefas consideradas no atendimento. As opções disponíveis são:  

- Todos os recursos 
 ![alt text](icons/visualizacao_atendimento.svg)

- Todos os materiais 
![alt text](icons/badge_materiais.svg)

- Todos os serviços 
![alt text](icons/badge_servico.svg)

- Um ou mais recursos selecionados 
![alt text](icons/badge_selecionar_recurso.svg)

Ao aplicar um desses filtros, as cores das tarefas refletirão o pior caso de atendimento dentro do conjunto filtrado.  

### Zoom
![alt text](icons/zoom.svg)

Permite ajustar a quantidade de períodos exibidos na linha do tempo. 

- Reduzir o zoom: amplia o horizonte temporal, exibindo mais anos.  

- Aumentar o zoom: detalha períodos menores, focando em um ano específico.  

### Filtro 
![alt text](icons/filtro.svg)

Permite filtrar as tarefas de acordo com as seguintes categorias: 

- Cluster

- Bacia  

- Projeto

- Tipo de serviço

- Tipo de tarefa  

- Atendimento padrão

- Sondas

O filtro funciona como uma interseção entre as categorias selecionadas.  

### Resumo
![alt text](icons/resumo.svg)

Permite visualizar o indicador de quantidade de tarefas por atendimento ID Recurso. Esse painel lateral também funciona como um filtro de tarefas.