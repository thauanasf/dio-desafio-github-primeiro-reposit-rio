# Desafio de Projeto sobre Git/GitHub da Dio
Repositório criado para o desafio de projeto 
## links  Úteis
[Sintaxe Basica Markdown](https://www.markdownguide.org/getting-started/)



## Uma introdução ao GIT :computer:

###  O que é o Git

*O Git é um projeto de código aberto maduro e com manutenção ativa desenvolvido em 2005 por Linus Torvalds, o famoso criador do kernel do sistema operacional Linux. Um número impressionante de projetos de software depende do Git para controle de versão, incluindo projetos comerciais e de código-fonte aberto.* *De longe, o sistema de controle de versão moderno mais usado no mundo hoje é o Git*

### Desempenho

*Diferente de alguns softwares de controle de versão, o Git não se deixa enganar pelos nomes dos arquivos ao determinar qual deve ser o armazenamento e o histórico de versões da árvore de arquivos. Em vez disso, o Git se concentra no conteúdo do arquivo. Afinal, os arquivos de código-fonte são renomeados, divididos e reorganizados com frequência. O formato do objeto dos arquivos de repositório do Git usa uma combinação de codificação delta (armazenamento de diferenças de conteúdo) e compactação e armazena com clareza o conteúdo do diretório e os objetos de metadados da versão.*

**exemplo:** *digamos que uma desenvolvedora, Alice, faça alterações no código-fonte, adicionando um recurso para a próxima versão, 2.0, e faça o commit dessas alterações com mensagens descritivas. Ela então trabalha em um segundo recurso e faz o commit dessas alterações também. Como esperado, eles são armazenados como peças de trabalho separadas no histórico de versões. Alice então muda para o branch da versão 1.3 do mesmo software para corrigir um erro que afeta apenas a versão mais antiga. O objetivo disso é permitir que a equipe de Alice lance uma versão de correção de bug, a versão 1.3.1, antes que a versão 2.0 esteja pronta. Alice pode retornar ao branch 2.0 para continuar trabalhando nos novos recursos da versão 2.0*

### Segurança 

*O conteúdo dos arquivos, bem como os verdadeiros relacionamentos entre arquivos e diretórios, versões, tags e commits, todos esses objetos no repositório do Git são protegidos com um algoritmo de hash de criptografia seguro chamado SHA1. Isso protege o código e o histórico de alterações contra alterações acidentais e maliciosas e garante que o histórico tenha rastreabilidade total.* *Alguns outros sistemas de controle de versão não têm proteções contra alterações secretas posteriores. Isso pode ser uma vulnerabilidade séria de segurança das informações para qualquer empresa que depende do desenvolvimento de software.*



### Flexibilidade

*Um dos principais objetivos de design do Git é a flexibilidade. O Git é flexível em vários aspectos: suporte a vários tipos de fluxos de trabalho de desenvolvimento não lineares, em eficiência em projetos pequenos e grandes e em compatibilidade com muitos sistemas e protocolos existentes.*  



### Controle de Versões com Git 

*Hoje, o Git é a melhor escolha para a maioria das equipes de software. Embora cada equipe seja diferente e deva fazer a própria análise, aqui estão os principais motivos pelos quais o controle de versão com Git é preferido em vez de alternativas:*

**O Git é bom**

*O Git tem a funcionalidade, desempenho, segurança e flexibilidade que a maioria das equipes e desenvolvedores individuais precisa. Esses atributos do Git são explicados acima. Nas comparações lado a lado com a maioria das outras alternativas, muitas equipes acham que o Git é muito favorável.*

**Git é um padrão de fato**

*Um grande número de desenvolvedores já tem experiência com o Git e uma proporção significativa de recém-formados pode ter experiência apenas com o Git. Embora algumas empresas precisem escalar a curva de aprendizado ao migrar para o Git de outro sistema de controle de versão, muitos desenvolvedores existentes e futuros não precisam ser treinados no Git.* *Além dos benefícios de um grande conjunto de talentos, a predominância do Git também significa que muitas ferramentas e serviços de software de terceiros já estão integrados 8ao Git, incluindo IDEs e novas ferramentas de uso como o cliente de desktop DVCS Sourcetree, software de rastreamento de itens e projetos, Jira, e serviço de hospedagem de código, Bitbucket.*

------

Se você é um desenvolvedor inexperiente que quer desenvolver habilidades valiosas em ferramentas de desenvolvimento de software, quando se trata de controle de versão, o Git deve ser um dos itens na lista.

------



### Git é um projeto de código aberto de qualidade

*O Git é um projeto de código aberto muito bem suportado, com mais de uma década de administração sólida. Os mantenedores do projeto mostraram um julgamento equilibrado e uma abordagem madura para atender às necessidades de longo prazo dos usuários, com lançamentos regulares que melhoram a usabilidade e a funcionalidade. É fácil examinar a qualidade do software de código aberto, e inúmeras empresas dependem muito dessa qualidade.**O Git tem excelente suporte da comunidade e uma vasta base de usuários. A documentação é excelente e abundante, incluindo livros, tutoriais e sites dedicados. Existem também podcasts e tutoriais em vídeo.**O código aberto reduz o custo para desenvolvedores amadores, pois eles podem usar o Git sem pagar uma taxa. Para uso em projetos de código aberto, o Git é sem dúvida o sucessor das gerações anteriores de sistemas bem-sucedidos de controle de versão de código aberto, SVN e CVS.*

### Crítica ao Git

*Uma crítica comum ao Git é que pode ser difícil de aprender. Algumas das terminologias do Git vão ser novas para os iniciantes e, para usuários de outros sistemas, a terminologia do Git pode ser diferente, por exemplo, revert no Git tem um significado diferente do que no SVN ou CVS. No entanto, o Git é muito capaz e disponibiliza muitos recursos aos usuários. Aprender a usar esses recursos pode levar algum tempo. No entanto, uma vez aprendidos, podem ser usados pela equipe para aumentar a velocidade de desenvolvimento.*





# O que é o GITHUB

*O GitHub é uma plataforma de hospedagem de código para controle de versão e colaboração. Ele permite que você e outras pessoas trabalhem juntos em projetos de qualquer lugar.*

*O GitHub é considerado uma ferramenta essencial para engenheiros de software, com uma popularidade sem igual. Atualmente, ele acomoda mais de 25 milhões de usuários. Isso significa que há um número considerável de profissionais que estão procurando o GitHub para melhorar o fluxo de trabalho e a colaboração.**Em suma, o GitHub é um serviço baseado em nuvem que hospeda um sistema de controle de versão (VCS) chamado Git. Ele permite que os desenvolvedores colaborem e façam mudanças em projetos compartilhados enquanto mantêm um registro detalhado do seu progresso.*

## O que é um sistema de controle de versão?

*Sempre que desenvolvedores criam um novo projeto eles continuam criando atualizações no código base. Mesmo depois de o projeto ser lançado é comum a atualização de versões, correção de bugs, adição de novas ferramentas, etc. O sistema de controle de versão ajuda a acompanhar as mudanças feitas no código base. E mais, ele também registra quem efetuou a mudança e permite a restauração do código removido ou modificado. Não há códigos sobrescritos uma vez que o Git salva múltiplas cópias no repositório.*

##  Como Começar a Usar o GitHub

*Basta clicar nesse **link**: [https://docs.github.com/en/get-started/quickstart/hello-world]()  para você saber todo o passo a passo de como começar a usar o GITHUB*



