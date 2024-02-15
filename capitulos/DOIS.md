# 2. Processos
## Importância de Processos
- Assim como a produção de um carro, o desenvolvimento de software também segue um processo. Este processo, que pode ser pessoal ou em equipe, é essencial para garantir a qualidade e a produtividade. Ele ajuda a coordenar, motivar e organizar o trabalho dos desenvolvedores, alinhando-os com os objetivos da organização e evitando o trabalho descoordenado.

## Manifesto Ágil
- Os primeiros processos de desenvolvimento de software, como o Waterfall, eram sequenciais e semelhantes aos processos de Engenharia tradicional. No entanto, com o tempo, percebeu-se que o software é diferente de outros produtos de Engenharia, principalmente devido aos frequentes problemas enfrentados pelos projetos de software, como o não cumprimento de cronogramas e orçamentos.

    Em 2001, o Manifesto Ágil foi criado, valorizando:
    - Indivíduos e interações mais que processos e ferramentas.
    - Colaboração com o cliente mais que negociação de contratos.

## Extreme Programming
- Método ágil de desenvolvimento de software que enfatiza valores e princípios, como comunicação, simplicidade, feedback, coragem, respeito e qualidade de vida. XP não é prescritivo, mas é definido por práticas de desenvolvimento que são agrupadas em processos de desenvolvimento, programação e gerenciamento de projetos.

### Valores de XP
- Guiado por valores universais: comunicação, simplicidade e feedback. Esses valores ajudam a evitar erros, lidar com a complexidade e gerenciar riscos. Além disso, XP também valoriza coragem, respeito e qualidade de vida.

### Princípios de XP
- Humanidade: Ênfase na gestão de pessoas, reconhecendo que o capital humano é fundamental para o sucesso do projeto.
- Economicidade: Consciência de que odesenvolvimentode software é
uma atividade cara,demandando resultados econômicos.
- Benefícios Mútuos: Decisõesdevem beneficiar múltiplos
stakeholders,buscandoum equilíbrio entre aspartes envolvidas.
- Melhorias Contínuas: Defesadeum processodedesenvolvimento
continuamente aprimorado, com feedbackconstante.
- Falhas Acontecem: Reconhecimentodeque odesenvolvimentode
software envolve riscos e falhas,quenãodevem serusadaspara
punição.
- Baby Steps: Progresso seguro, testado e validado, favorecendo
melhorias contínuas em pequenospassos.
- Responsabilidade Pessoal: Defesada clarezadepapéis e
responsabilidadesna equipededesenvolvimento.

### Práticas sobre o Processo de Desenvolvimento
- No XP, os times incluem um representante dos clientes que entende o domínio do sistema a ser construído. Este representante escreve as "histórias de usuário", que são documentos resumidos descrevendo os requisitos do sistema. Essas histórias, escritas em cartões de papel, focam nas funcionalidades do sistema na visão dos usuários.


## Práticas de Programação
#### Design Incremental
- propõe que o design do sistema seja uma atividade contínua e incremental, em vez de concentrada no início do projeto. Isso permite adaptar o design à medida que os requisitos se tornam mais claros e mudam ao longo do projeto.
#### Programação em Pares
- prática onde duas pessoas trabalham juntas na mesma tarefa de codificação. Um líder (driver) escreve o código enquanto o outro (navegador) revisa.
#### Propriedade Coletiva do Código
- permite a qualquer desenvolvedor modificar qualquer parte do código, seja para implementar uma nova funcionalidade, corrigir um bug ou aplicar um refactoring, sem necessidade de autorização prévia.
#### Testes Automatizados:
- substituem os testes manuais por programas que verificam se as saídas de pequenas unidades do sistema são as esperadas. Isso reduz custos e permite a repetição dos testes a qualquer momento.
#### Desenvolvimento Dirigido por Testes (TDD).
- propõe a escrita de testes antes da implementação do código. Isso incentiva a criação de métodos com interfaces amigáveis e evita o adiamento da escrita de testes.
#### Build Automatizado
- refere-se à geração automatizada de uma versão executável do sistema, incluindo compilação e execução de testes. O objetivo é liberar os desenvolvedores de tarefas manuais e fornecer feedback rápido sobre possíveis problemas
#### Integração Contínua
- incentiva os desenvolvedores a integrar seu código frequentemente para minimizar conflitos. Serviços de integração contínua são usados para garantir a qualidade do código, executando o build e testes antes de cada integração.


## Práticas de Gerenciamento de Projetos
#### Ambiente de Trabalho
- O XP defende um ambiente de trabalho com times pequenos e dedicados, trabalhando juntos para facilitar a comunicação. O espaço deve ser informativo e as jornadas de trabalho devem ser sustentáveis, evitando longas horas que podem levar a problemas de saúde e rotatividade.
#### Contratos com Escopo Aberto
- permitem pagamento por hora trabalhada e flexibilidade para mudar requisitos. Isso favorece a comunicação e feedback, evitando a entrega de produtos com problemas conhecidos. Esses contratos são mais alinhados com os princípios do Manifesto Ágil

## Scrum 
- Scrum é um método ágil, iterativo e incremental para gerenciamento de projetos, não se limitando a projetos de software. Diferente do XP, que é voltado para desenvolvimento de software, o Scrum não propõe práticas de programação. O Scrum é bem definido, incluindo papéis, artefatos e eventos específicos.
### Papéis 
- Times Scrum são compostos por um Dono do Produto, um Scrum Master e desenvolvedores. 
  - O Dono do Produto define a visão do produto e maximiza o retorno do investimento. 
  - O Scrum Master garante a aderência às regras do Scrum e remove obstáculos. 
  - Os desenvolvedores, multidisciplinares, tomam decisões técnicas e estimam o tamanho das histórias.
### Principais Artefatos e Eventos
- O Backlog do Produto é uma lista dinâmica de histórias priorizadas, escritas e priorizadas pelo Dono do Produto, refletindo as funcionalidades a serem implementadas no projeto. Esse backlog é continuamente atualizado para refletir mudanças nos requisitos e na visão do produto.

- Sprint é o termo utilizado no Scrum para se referir a uma iteração, com duração de até um mês. Ao final de uma Sprint, o objetivo é entregar um produto potencialmente pronto para entrar em produção, com valor tangível para o cliente.

- O Planejamento do Sprint marca o início de uma Sprint e é uma reunião dividida em duas partes. Na primeira, o Dono do Produto propõe histórias, e o time decide se pode implementá-las. Na segunda, os desenvolvedores quebram as histórias em tarefas e estimam a duração delas.

- O Backlog do Sprint é o artefato gerado no final do Planejamento do Sprint, contendo a lista de tarefas do Sprint e sua duração. Assim como o Backlog do Produto, é dinâmico, permitindo ajustes durante a Sprint, exceto para o objetivo do Sprint, que é uma lista de histórias fixa.

## Kanban 
- Originado na Toyota, é um método de produção visual que ajuda as equipes a trabalhar de forma eficiente. No desenvolvimento de software, introduzido pela Microsoft, ele promove um ritmo sustentável de trabalho e melhoria contínua. Diferente do Scrum, é mais simples e não possui sprints ou papéis rígidos. O Quadro Kanban, seu principal artefato, guia o fluxo de trabalho através de colunas representando diferentes etapas do processo.

## Quando Não Usar Métodos Ágeis? 
1. **Design Incremental**: Métodos ágeis podem não ser adequados quando o domínio do sistema é novo e complexo, ou quando o custo de mudanças futuras é alto. Nesses casos, uma fase de design e análise inicial pode ser necessária.

2. **Histórias do Usuário**: Se o projeto é de uma área totalmente nova para a equipe de desenvolvedores, uma especificação detalhada de requisitos no início do projeto pode ser importante.

3. **Envolvimento do Cliente**: Se os requisitos do sistema são estáveis e conhecidos pela equipe de desenvolvedores, não é necessário ter um Representante dos Clientes ou Dono do Produto integrado à equipe.

4. **Documentação Leve e Simplificada**: Em domínios onde falhas podem causar danos graves, como nas áreas médicas e de transporte, documentações detalhadas de requisitos e de projeto são obrigatórias.

5. **Times Auto-organizáveis**: A autonomia das equipes ágeis pode ser incompatível com organizações que têm uma tradição de níveis hierárquicos e controle rígidos.

6. **Contratos com Escopo Aberto**: Algumas organizações podem não se sentir seguras para assinar contratos com escopo aberto, especialmente se não tiverem experiência prévia com desenvolvimento ágil.