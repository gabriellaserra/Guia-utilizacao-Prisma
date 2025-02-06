# Visão Médio Prazo

Na aba visão médio-prazo o usuário poderá acompanhar atendimento das frentes de serviço, esta aba constitui uma grande tabela com as colunas: atendimento padrão, nome da premissa, recurso, frentes atuais e o percentual de atendimento do ano corrente mais o percentual de atendimento dos dois anos seguintes, por exemplo percentual de atendimento 2025, percentual de atendimento 2026 e percentual de atendimento 2027.

Frentes Atuais é a quantidade de serviços que temos disponíveis no momento para utilizarmos no Atendimento (esse dado vem da Disponibilidade da Árvore de Recursos). Enquanto frentes máximas é a quantidade máxima que temos em contrato para utilizarmos.

Esse painel de visão médio prazo tem como objetivo exibir o percentual anual de atendimento (e posteriormente capacidade) de cada frente de serviço. Esse painel é uma visão a médio prazo do Atendimento porque utilizamos o dado da demanda diária determinística calculada pelo DELFOS para fazer o cálculo do atendimento. 

Esse cálculo de atendimento do painel é feito avaliando quantos dias nós temos em que a quantidade de Frentes Máximas é menor do que a Demanda, dividido pelo total de dias do planejamento (como está por ano seria 365), o cálculo é feito então com 1 - esse valor pra pegar a porcentagem.

Vale ressaltar ainda que, no canto superior direito dessa tela o usuário também tem o botão de incluir contingentes, caso ele deseje visualizar a tabela com as atividades e recursos contingentes.

![alt text](image-12.png)
