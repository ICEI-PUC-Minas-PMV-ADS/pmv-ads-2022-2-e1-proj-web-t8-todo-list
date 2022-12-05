# Contexto 
A autogestão é uma habilidade comportamental que tem ganho grande atenção nos últimos tempos. Muito necessária no mundo empresarial, seja pela nova realidade do teletrabalho ou para o incremento da produtividade, o exercício da autonomia e auto-organização permite que o agente executor seja protagonista no processo ao qual está envolvido, mitigando erros e com ganho de eficiência em suas ações por meio da otimização do tempo (ALMEIDA LOPES et al; 2021). 
 
Assim como algumas habilidades laborais são transpostas para realidade cotidiana, a capacidade de autogestão tem grande aplicação ao usuário comum e possibilita inúmeros benefícios. A ida aos supermercados é um evento corriqueiro na vida de todos os brasileiros e seja por estímulos marqueteiros ou por impulsividade, também é frequente a aquisição de itens não planejados. A falta de organização contribui significativamente para "fuga de dietas", baixa qualidade nutricional ou de produtos apelativos que não atenderão as necessidades reais do usuário além de ocasionar gastos maiores e não previstos frente aos necessários. 

Portanto, é de grande valia a criação e disponibilização de ferramentas que fomentem a prática da autogestão e permitam que o usuário comum tenha uma jornada mais consciente quanto as suas necessidades de consumo nos supermercados. 

## Problema
A falta de organização e planejamento atrelados a impulsividade são elementos chave para a baixa qualidade do controle orçamentário ao longo da jornada de compras em supermercados. Ainda, é recorrente que itens essenciais sejam esquecidos e com isso a justificativa primordial para o início da jornada de compras perca seu objetivo. Tais condicionantes podem ser evitadas por meio do uso de ferramentas de autogestão, como propõe o presente projeto, minimizando desperdícios e gastos não previstos. 

## Objetivos
De forma geral, o objetivo desse trabalho é entregar uma aplicação web que consiga auxiliar usuários a fazerem um check-list dos seus itens de compra em supermercado de forma prática, intuitiva e efetiva.  

Mais especificamente: 

1. Apresentar visualmente um rascunho claro dos itens à serem adquiridos;    
2. Entregar um layout de fácil interação que consiga ser assimilado por diversos públicos e idades;  
3. Possibilitar que, ao término da compra, o usuário saiba quais itens de fato resolveu adquirir, o valor que gastou e quais itens dispensou. 

## Justificativa
Com margens de lucro cada vez mais restritas, seja pela aproximação dos fabricantes ao público final facilitando assim o acesso aos bens de consumo, ou pelos altos custos operacionais, os supermercados passaram a desenvolver estratégias próprias para estimular o incremento dos gastos e tempo de permanência dos consumidores em loja. 

A temática não é nova e inúmeros estudos ao redor do globo já foram desenvolvidos sobre o comportamento do consumidor. É consenso geral e conforme ressaltado por ANGELO, C. F. DE et al; 2003; em seu trabalho: "As compras não planejadas em supermercados: a importância do tempo e da organização da loja na determinação dos gastos.", que o tempo de permanência em loja é diretamente proporcional ao valor gasto pelo consumidor e esse gasto é afetado pela disposição dos produtos. 

O comportamento do usuário é, portanto, determinante para sua capacidade de gerar economia. Logo, ao dispor de uma ferramenta própria para realizar o planejamento dos itens que serão adquiridos, ganha-se eficiência de tempo e minimizam-se as chances de que compras não previstas sejam realizadas por impulsividade. 

## Público-Alvo
Embora todas as pessoas possam se beneficiar da ferramenta proposta, que possui aplicação múltipla em diversas temáticas, o foco deste trabalho está voltado para a jornada de consumo em supermercados, dado que são eventos recorrentes e que demandam parte significativa do orçamento familiar e/ou pessoal. 

Existem, de modo generalista, dois grupos de usuários de características antagônicas que são eles: 

1. Jovens que vão fazer compras para alguém ( 16 até 25 anos ); 
2. Adultos e Idosos que farão compras para si ( 25 anos + ); 

## Especificações do Projeto
Definido o público, temos que a ferramenta deve ser acessível permitindo seu uso adequado dentre os múltiplos perfis etários. 

## Personas
<div align="center">
img src="![BrunoAlan](https://user-images.githubusercontent.com/110849216/205555102-f05394a9-8ff8-4f59-8e2c-4a78040f5c91.jpg)" width="700px" /
</div>


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

