
# Projeto Disciplina: Requisitos de Software

Olá! Este repositório faz parte do projeto da disciplina de Requisitos de Software da UTFPR - Campus Cornélio Procópio. 

## 1. Introdução

***1.1.  Nome do Grupo***

Nome do Grupo: **iCut**
Integrantes: Fraga013, gbrochi, GustavoSilva2005, l0destarz, ThalesGranja

***1.2.  Nome do Sistema***

iCut

***1.3.  Propósito do Sistema***

Este documento apresenta os requisitos dos usuários a serem desenvolvidos pela iCut, fornecendo aos desenvolvedores as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema.

O objetivo do sistema iCut é facilitar o processo de agendar um serviço em barbearias.

Aqui está o link para uma apresentação mais detalhada dos Requisitos de Usuário e Requisitos de Sistema: https://padlet.com/gsilva2005/kanban-h8jiv6iru3n1xb6z

***1.2.  Público Alvo***

Este documento se destina aos arquitetos de software, engenheiros de software, testadores, clientes... 

***1.3. Descrição dos usuários***

Os usuários finais serão os clientes da barbearia que vamos fornecer o sistema de controle de corte e estoque da mesma.

Aqui está o link para a apresentação dos potênciais clientes e barbeiro: https://encurtador.com.br/afjMZ

***1.4. Cenários***

**Cenário Antes:**

Paulo Ribeiro sempre teve dificuldade em gerenciar seu tempo para agendar um corte de cabelo. Ele precisava ligar para a barbearia durante o horário de expediente, o que nem sempre era possível devido ao seu trabalho. Quando conseguia ligar, às vezes encontrava a linha ocupada ou o atendente estava ocupado atendendo outros clientes. As tentativas de agendamento pessoalmente eram ainda mais complicadas, já que precisavam ser feitas durante horários de funcionamento que não coincidiam com sua disponibilidade. A gestão manual da barbearia frequentemente resultava em erros, como horários duplicados ou esquecidos, o que tornava a experiência frustrante e demorada. A falta de comunicação eficiente e a necessidade de lembrar manualmente de seu horário contribuíam para que Paulo frequentemente perdesse seus agendamentos.

**Cenário Depois:**

Após a barbearia adotar o iCut, Paulo Ribeiro passou a agendar seus cortes de cabelo diretamente pelo aplicativo, a qualquer hora do dia, sem precisar interromper seu trabalho. Ele pode ver os horários disponíveis em tempo real e escolher o que melhor se encaixa na sua agenda, com apenas alguns cliques. A interface intuitiva do iCut facilita o processo, permitindo que Paulo complete o agendamento em menos de um minuto.

Além disso, Paulo agora recebe confirmações imediatas e lembretes automáticos por SMS e e-mail, eliminando o risco de esquecer seu horário. A barbearia, por sua vez, gerencia seus horários de forma mais eficiente, sem agendamentos duplicados ou esquecidos. O sistema também mantém um histórico dos serviços de Paulo, permitindo que a barbearia ofereça um atendimento mais personalizado e sugerindo cortes e tratamentos baseados em suas preferências anteriores.

Com a conveniência proporcionada pelo iCut, Paulo sente-se muito mais satisfeito e valorizado como cliente. Ele conseguiu otimizar seu tempo e garantir que nunca mais perca um agendamento. A experiência aprimorada aumentou sua fidelidade à barbearia, e ele agora recomenda o serviço a amigos e familiares. A barbearia, por sua vez, viu um aumento na eficiência operacional e na satisfação do cliente, resultando em um negócio mais próspero e organizado.

## 2. Documentos gerais no repositório

***2.1. Requisitos***

| Nível de prioridade | Descrição |
| --- | ---|
| 1 | Alto |
| 2 | Médio |
| 3 | Baixo |

***2.1.1 Requisitos Funcionais***

| Requisitos Funcionais | Descrição | Prioridade |
| --- | --- | --- |
| `[RF01]` | O software deve permitir que o cliente faça o seu próprio cadastro no aplicativo. | 1 |
| `[RF02]` | O software deve permitir que o cliente marque um horário. | 1 |
| `[RF03]` | O software deve permitir que o cliente escolha um barbeiro de sua preferência para prestar o serviço escolhido. | 1 |
| `[RF04]` | O software deve permitir que o cliente veja os itens disponíveis para venda (objetos) no catálogo online e posteriormente ir para o carrinho, e optanto pelas formas de pagamento. | 2 |
| `[RF05]` | O software deve permitir que o cliente veja o catálogo de serviços da barbearia. | 1 |
| `[RF06]` | O software deve permitir que o barbeiro veja a quantidade de horas que o mesmo já trabalhou. | 3 |
| `[RF07]` | O software deve permitir que o cliente escolha qual tema de aplicativo ele quer (claro/escuro). | 3 |
| `[RF08]` | O software deve permitir que o cliente consulte o horário marcado (ver serviço, dia, horário e barbeiro). | 1 |
| `[RF09]` | O software deve permitir que o barbeiro consiga gerenciar seus horários (consegue bloquear horários da sua agenda para clientes não pegarem). | 1 |
| `[RF10]` | O software deve permitir que o barbeiro consiga marcar um horário para clientes já cadastrados. | 1 |
| `[RF11]` | O software deve permitir que o cliente faça uma avaliação após o serviço contratado(avaliação estrela e box de mensagem). | 1 |
| `[RF12]` | O software deve permitir que o cliente assinale a opção de fazer uma avaliação anônima. | 1 |
| `[RF13]` | O software deve permitir que o cliente edite seu horário previamente marcado(cancelar/remarcar reserva), esta opção fica disponível para o cliente até 24h antes da reserva. Caso ele tenha marcado o serviço no mesmo dia da reserva, ele consegue editar até 1h após a solicitação da reserva. | 1 |
| `[RF14]` | O software deve permitir que o barbeiro edite o status dos clientes para (inativo e viajante). | 2 |
| `[RF15]` | O software deve permitir que o cliente escolha entre pagar pelo app ou não. | 1 |

***2.1.2 Requisitos Não Funcionais***

| Requisitos Não Funcionais | Descrição | Prioridade |
| --- | --- | --- |
| `[RNF01]` | A interface do sistema deve ser intuitiva e fácil de usar, permitindo que novos usuários aprendam a utilizá-la completamente em até 2 minutos. | 1 |
| `[RNF02]` | O sistema deve permitir a conclusão de um agendamento de corte de cabelo com no máximo 5 interações (cliques) por meio de uma interface otimizada e eficiente. | 2 |
| `[RNF03]` | O sistema deve fornecer uma ajuda online claramente acessível e visível na interface, minimizando o esforço necessário para encontrá-la. | 1 |
| `[RNF04]` | O sistema deverá processar 100 requisições a cada segundo (visando maior velocidade na confirmação do agendamento). | 3 |
| `[RNF05]` | O instalador do sistema não deve ser superior a 150MB. | 1 |
| `[RNF06]` | O sistema deve suportar 20 usuários concorrentemente. | 2 |
| `[RNF07]` | O sistema deve ficar no ar 95% do tempo durante o mês (Aproximadamente 36h por mês, no máximo, fora do ar). | 1 |
| `[RNF08]` | Se o sistema falhar, os dados do usuário devem ser recuperados pelo sistema. | 1 |
| `[RNF09]` | O sistema deve ser operacionalizado no Android e IOS. | 1 |
| `[RNF10]` | Todos os documentos entregues devem seguir o cabeçalho e rodapé definido pela empresa. | 1 |
| `[RNF11]` | O sistema deve ser implementado na linguagem React Native/JavaScript. | 2 |
| `[RNF12]` | O sistema deve interagir com o sistema do banco para pagamento dos usuários. | 1 |
| `[RNF13]` | O sistema não deve revelar aos operadores nenhuma informação pessoal dos clientes. | 1 |
| `[RNF14]` | O acesso aos dados deve ser protegido. | 1 |
| `[RNF15]` | O sistema deve colocar automaticamente o status do cliente "em análise" depois de não frequentar a barbearia por 3 meses. | 1 |
| `[RNF16]` | O sistema deve mudar o status do cliente para ativo assim que ele marcar um serviço (com excessão do status "viajante"). | 1 |
| `[RNF17]` | O sistema deve ter uma função de status de cliente como: "ativo", "inativo", "em análise" e "viajante". | 1 |
| `[RNF18]` | O sistema deve armazenar o histórico de cada cliente baseado no cadastro. | 1 |
| `[RNF19]` | O sistema deve enviar uma notificação no dia seguinte para o cliente dar um feedback do serviço. | 2 |
| `[RNF20]` | O sistema deve enviar uma mensagem automática para o cliente no dia de seu corte, para relembrar do horário e serviço marcado. Se e somente se o cliente assinalou que gostaria de receber esse lembrete. | 1 |
| `[RNF21]` | O sistema só deve permitir o cadastro do cliente caso a idade dele seja acima ou igual a 14 anos, salvo as exceções. | 1 |
| `[RNF22]` | O sistema deve enviar uma mensagem, já definida, automaticamente para o cliente que entrar em status "em análise". | 2 |
| `[RNF23]` | O sistema deve gerar um QR code e um código copia e cola para o pagamento dentro do app. | 1 |
| `[RNF24]` | O sistema deve fornecer um relatório sobre status de clientes ou produtos da barbearia como solicitado pelo barbeiro. | 1 |


***2.2. Entrevista***

Você pode ver as peguntas para o roteiro de entrevista clicando [aqui](https://github.com/iCut-UTFPR/requisitos-software/blob/main/Entrevista/Perguntas%20sobre%20o%20software%20de%20barbearia.txt).

E para ver a resposta da entrevista é só clicar [aqui](https://github.com/iCut-UTFPR/requisitos-software/blob/main/Entrevista/Resposta%20da%20Entrevista%20sobre%20o%20software%20de%20barbearia.txt).

***2.3. Histórias de Usuário***

| N° | História de Usuário |
| --- | --- |
| 1 | Como um cliente, eu quero fazer meu próprio cadastro, para que eu consiga marcar um horário. |
| 2 | Como um cliente, eu quero fazer meu próprio agendamento do serviço que desejo, para que eu não precise ligar a barbearia. |
| 3 | Como um cliente, eu quero escolher o barbeiro que irá realizar o trabalho, para que eu consiga marcar um horário. |
| 4 | Como um cliente, eu quero ver os itens (objetos) disponíveis para a venda, para que eu não precise ligar perguntando dos itens. |
| 5 | Como um cliente, eu quero ver o catálogo, para que eu possa escolher qual serviço gostaria de agendar. |
| 6 | Como um barbeiro, eu quero de ver quantas horas já trabalhei, para saber como meus serviços estão indo. |
| 7 | Como um cliente, eu quero mudar alternar entre o tema claro e escuro dentro do aplicativo, para que eu tenha um maior conforto na hora de usar o aplicativo com o tema que desejo. |
| 8 | Como um cliente, eu quero consultar o horário que eu marquei, para que eu possa conferir o horário, serviço e barbeiro. |
| 9 | Como um barbeiro, eu quero gerenciar meus horários, para que eu possa bloquear meus horários para clientes não pegarem. |
| 10 | Como um barbeiro, eu quero agendar um horário para um cliente já cadastrado, para que os que não gostem de marcar por aplicativo tenham que entrar nele. |
| 11 | Como um cliente, eu quero fazer uma avaliação, dentro do aplicativo, do serviço prestado, para que eu dê um feedback se gostei ou não. |
| 12 | Como cliente, eu quero ter a possibilidade de escolher entre fazer a avaliação anônima ou não por uma check box na tela de avaliação, para que eu possa ser verdadeiro em minha avaliação sem ficar constrangido futuramente. |
| 13 | Como cliente, eu quero editar meu agendamento (cancelar/remarcar), para que eu possa cancelar ou remarcar caso precise. |
| 14 | Como barbeiro, eu quero mudar o status do cliente para "inativo" ou "viajante", para que eu consiga controlar melhor os status dos clientes. |
| 15 | Como cliente, eu quero escolher entre pagar pelo aplicativo ou não, para que eu tenha uma variedade de opções e visando praticidade também. |

***2.4. Protótipos***

Clique [aqui](https://github.com/iCut-UTFPR/requisitos-software/blob/main/Protótipo%20Aplicativo%20-%20iCut.zip) para baixar o arquivo .zip e ver o protótipo do aplicativo.

***2.5. Matrizes de Rastreabilidade***

Se você clicar [aqui](https://github.com/iCut-UTFPR/requisitos-software/tree/main/Matrizes%20de%20Rastreabilidade), você será redirecionado para ver as matrizes.

***2.6. Diagramas***

Clique no nome do diagrama para você ser redirecionado:
[Diagrama de Caso de Uso](https://github.com/iCut-UTFPR/requisitos-software/tree/main/Diagrama%20Caso%20de%20Uso),
[Diagrama de Atividade](https://github.com/iCut-UTFPR/requisitos-software/tree/main/Diagrama%20de%20Atividade),
[Diagrama de Classe](https://github.com/iCut-UTFPR/requisitos-software/tree/main/Diagrama%20de%20Classe).


## Referências

*<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>*

[1] “Glossário da _USina_”, <_id_doc glossário_>, Versão <_versão_>. Localização: <_localização_>.
