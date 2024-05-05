# Planejamento Análise Hierárquica de Tarefas para a aba de Monitoria
## Sumário
* [Introdução](#Introdução)
* [A Funcionalidade de Monitoria](#A-Funcionalidade-de-Monitoria)
* [Inspirações](#Inspirações)
* [Metodologia](#Metodologia)
* [Cronograma](#Cronograma)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)

## Introdução
Durante as entrevistas com os estudantes, um assunto discutido foi a necessidade de se ter uma funcionalidade destinada aos assuntos de monitoria, uma vez que ela não está presente no SIGAA. Deste modo, este documento tem o intuito de realizar um planejamento da análise das tarefas envolvidas no processo de pedido, monitoramento e troca de mensagens de monitorias na perspectiva do estudante ao se utilizar o SIGAA.

Com base nisso, para criar a área de monitoria é necessário garantir a eficiência e eficácia do sistema ao proporcionar uma experiência satisfatória aos usuários. Por isso, a análise de tarefas adotada nesta fase segue uma abordagem hierárquica, conhecida como **Análise Hierárquica de Tarefas (HTA)**, que permite uma representação sistemática das atividades em etapas menores e mais gerenciáveis. Com isso, ao decompor as metas dos estudantes em submetas e tarefas específicas, é possível identificar os pontos de entrada no sistema, as operações realizadas pelos usuários e os resultados esperados, algo que será apresentado nos documentos da execução da análise.

Além disso, a análise de tarefas para as funcionalidades presentes na aba de monitoria será conduzida utilizando o método **GOMS (Goals, Operators, Methods, e Selection Rules)**. Esse método é uma abordagem de avaliação de usabilidade que se concentra na compreensão de como os usuários interagem com um sistema para atingir seus objetivos. Com isso, o "Goals" (objetivos) referem-se aos resultados desejados pelos usuários, "Operators" (operadores) são ações mentais e físicas realizadas para alcançar esses objetivos, "Methods" (métodos) são as sequências de operadores necessárias para concluir uma tarefa e "Selection Rules" (regras de seleção) determinam como os usuários escolhem entre métodos alternativos. Ao aplicar o método GOMS, é possível identificar pontos de otimização e simplificação nas tarefas de monitoria.

## A Funcionalidade de Monitoria
A aba de monitoria no sistema do SIGAA será concebida com o objetivo de simplificar e agilizar os processos de monitoria que ocorrem semestralmente. Isso porque esta área poderá oferecer diversas ferramentas essenciais para alunos e, até mesmo, professores envolvidos no programa de monitoria.

Essa aba terá três funcionalidades principais, que incluem:

- A opção de solicitar monitoria, permitindo que os alunos requisitem a supervisão de um docente específico para uma disciplina em particular.
- A possibilidade de ter uma visão dos dados de monitoria que já exerceu ou exercita atualmente, além de permitir que os monitores documentem uma grade de horários de atendimento, que poderá ser disponibilizada no perfil da turma, facilitando a interação entre monitores e alunos.
- Possibilidade de solicitar o uso de salas para as sessões presenciais de monitoria.
- Comunicação privada, onde os monitores podem trocar mensagens com professores e alunos da turma.

## Inspirações

Para realizar a análise de tarefas da aba de monitoria, alguns projetos anteriores da disciplina e os materiais disponibilizados pelo professor serão utilizados como base e inspiração.

Os projetos utilizados como inspiração serão:

- [Projeto do Banco Central do Brasil](https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/analise_requisitos/analise_tarefas) (1)
- [Projeto BCE](https://interacao-humano-computador.github.io/2020.1-BCE/#/pages/ponto_de_controle_2/analise_tarefas) (3)
- [Projeto Domínio Público](https://interacao-humano-computador.github.io/2023.2-Dominio-Publico/analise_de_requisitos/analise_de_tarefas/goms/) (4)
- [Projeto Lichess](https://interacao-humano-computador.github.io/2022.2-Lichess/analise_requisitos/analise_tarefas/) (5)

Os materiais disponibilizados pelo professor são:
- Capítulo 6, Organização do espaço problema, do livro “Interação Humano-Computador”, de Barbosa e Silva. Edição de 2010. (2)

## Metodologia

Para analisar o processo das funcionalidades de monitorias na perspectiva do estudante, inicialmente, será realizada uma análise e uma compreensão dos objetivos gerais do usuário ao utilizar essa funcionalidade. Assim, esses objetivos serão divididos em subobjetivos mais específicos, que são então relacionados com as operações concretas que o estudante precisará realizar no SIGAA. Essas operações serão mostradas contextualmente.

Em seguida, para ser contextualizado dentro do fluxo de interação, será elaborado um diagrama, uma vez que ele fornecerá uma visão geral do processo, destacando as inter-relações entre as diferentes tarefas e ajudando a identificar possíveis gargalos ou lacunas no fluxo. Após a elaboração do diagrama, será elaborada uma tabela detalhando cada tarefa conforme o “input”, “feedback”, “plano” e “recomendação”.

Após a realização da análise hierárquica, será realizada a análise por meio do GOMS para as atividades. Para isso, será mais uma vez revisado o escopo da tarefa com os seus objetivos, então serão definidos os seus métodos e operações. Com isso, este processo visa garantir uma análise mais precisa das tarefas.

## Cronograma
A tabela 1 mostra o cronograma da análise de cada uma das funcionalidades:

**Tabela 1**: Cronograma

| Atividade | Data de início | Data de fim |
| - | - | - |
| Elicitar requisitos por meio de entrevistas | 20/04/2024 | 23/04/2024 |
| Definir objetivos de cada funcionalidade | 29/04/2024 | 29/04/2024 |
| Planejar como cada funcionalidade deve funcionar | 29/04/2024 | 29/04/2024 |
| Executar análise hierárquica da funcionalidade de pedido de monitoria | 30/04/2024 | 01/04/2024 |
| Executar análise GOMS da funcionalidade de pedido de monitoria | 30/04/2024 | 01/04/2024 |
| Executar análise hierárquica da funcionalidade de monitoramento de monitoria | 01/04/2024 | 01/04/2024 |
| Executar análise GOMS da funcionalidade de monitoramento de monitoria | 01/04/2024 | 01/04/2024 |
| Executar análise da funcionalidade de conversas privada | 03/04/2024 | 02/04/2024 |
| Executar análise GOMS da funcionalidade de monitoramento de monitoria | 01/04/2024 | 01/04/2024 |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

## Conclusão
O planejamento da execução da análise hierárquica de tarefas e da GOMS para a aba de monitoria apresenta uma estrutura sólida e abrangente para o desenvolvimento e aprimoramento desta funcionalidade que será criada no sistema do SIGAA.

## Referência Bibliográfica

1. Projeto do Banco Central do Brasil. Disponível em <https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/analise_requisitos/analise_tarefas> Acesso em 28 de abril de 2014.
   
2. Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do Usuário. Acesso em 28 de abril de 2024.
   
3. Projeto BCE. Disponível em <https://interacao-humano-computador.github.io/2020.1-BCE/#/pages/ponto_de_controle_2/analise_tarefas>

4. Projeto Domínio Público. Disponível em <https://interacao-humano-computador.github.io/2023.2-Dominio-Publico/analise_de_requisitos/analise_de_tarefas/goms/> Acesso em 28 de abril de 2014.
   
5. Projeto Lichess. Disponívem em <https://interacao-humano-computador.github.io/2022.2-Lichess/analise_requisitos/analise_tarefas/> Acesso em 28 de abril de 2014.

## Histórico de Versão
| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e realização do documento| Larissa Stéfane | - | 28/04/2024 |
