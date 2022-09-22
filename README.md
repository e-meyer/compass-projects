# Perguntas

### 1. Para que serve o método Scrum?

Para gerenciar melhor projetos complexos, que poderão sofrer modificações, alterações ou upgrades durante todo seu ciclo de vida. Além disso, essa metodologia ágil busca quebrar os processos do desenvolvimento de software em processos menores, possibilitando uma organização e comunicação melhor entre os envolvidos.

### 2. Como funciona o método Scrum?

Primeiro, são designadas funções para os envolvidos no projeto:

-   Product Owner (PO): é o representante do cliente no time. Orienta a equipe na direção de como tem a visão do produto.
-   Scrum Master (SM): busca organizar e facilitar a comunicação e convívio da equipe, orientando-os quando necessário.
-   Desenvolvedores: coloca efetivamente a aplicação em desenvolvimento.

Depois de distribuídas as funções, entramos no ciclo do Scrum:

1. Organizar o backlog: responsabilidade do PO, encaixando o que é mais prioritário e o que agrega mais valor para a aplicação do cliente naquele momento.
2. Planejamento de sprints: juntamente a equipe de desenvolvimento, aqui é onde se decide quanto trabalho será realizado em um tempo acordado pela equipe.
3. Sprint: um período de tempo em que o trabalho será feito para entregar algo a mais ou corrigir algo na aplicação.
    - Scrum diário: reunião diária, ocorre todos os dias na mesma hora, onde os membros respondem três perguntas:
        - O que fez no dia anterior
        - O que vai fazer hoje
        - Se teve algum impedimento
4. Análise de sprint: no final da sprint, é visto o que foi desenvolvido durante aquele tempo. São trazidos de volta os itens do backlog vistos anteriormente para checar o que foi concluído, deixando o cliente decidir o que vai e o que não vai lançar no produto final.
5. Retrospectiva de sprint: momento em que se reúnem para uma discussão do que deu certo e o que não deu naquela sprint, vendo no que se pode melhorar.

### 3. O que é Git?

Git é um sistema de controle de versões, onde se pode acessar versões antigas de projetos, fazer alterações, trabalhar em conjunto com outras pessoas, o que em um ambiente de desenvolvimento é muito útil.

### 4. O que é um scrum Product Owner?

É o representante do cliente no time. Orienta a equipe na direção de como tem a visão do produto. Também é responsável pelo backlog do produto, priorizando o que é mais importante para o cliente naquele momento e tira dúvidas dos desenvolvedores.

### 5. Qual o comando para criação de um novo repositório no Git?

Para iniciar um novo repositório, usa-se ```git init```

### 6. Com o Git você pode propor mudanças (adicioná-las ao Index) usando um comando. Qual é esse comando? 

Para adicionar arquivos ao index, usa-se ```git add```

### 7. O que é a Branch master e para que serve? 

É a branch principal do software, a que tem a versão final e de lançamento dele.

### 8. Quais são os comandos usados para atualizar um repositório local e fazer merge de um outro branch ao seu branch ativo?

Para atualizar o repositório local, usa-se ```git push```.

Para fazer merge de outro branch com o branch ativo, vá-se ao branch que quer manter e executa ```git merge <nome da branch que quer juntar>```

### 9. Qual a diferença entre git e github?

Git é um software de controle de versões, com diversos comandos para versionar o software. O GitHub é como uma plataforma que hospeda os arquivos administrados pelo Git.

### 10. Quais os dois verbos http que podemos utiizar para realizar um update? Explique a diferença entre eles.

São os métodos PUT e POST, a diferença é feita mais por convenção, o primeiro para alterar e o segundo para incluir. Já pela documentação oficial, é observado que o PUT é usado mais para criar ou editar algo, já o POST pode ser usado para qualquer coisa na aplicação.

### 11. Qual o status code que pode ser usado na criação de um novo usuário? 

O Status 201 indica que o resultado de uma POST request foi aceito e os dados foram criados no banco de dados.  

