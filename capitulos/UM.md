# 1. Introdução

A Engenharia de Software é uma área da Computação que busca soluções para desenvolver sistemas de software de forma produtiva e com qualidade. Ela surgiu no final da década de 60, quando os computadores começaram a se popularizar e novas aplicações se tornaram possíveis. Hoje, o software está presente em diversos aspectos da vida moderna, desde sistemas de informação em empresas até dispositivos e produtos de engenharia.

#### Conferência da OTAN:
- A Conferência da OTAN em 1968 marcou a criação da Engenharia de Software, enfatizando a necessidade de princípios práticos e teóricos na construção de software. Hoje, sabe-se que o software não deve ser construído em fases estritamente sequenciais e existem padrões, bibliotecas e frameworks disponíveis para reutilização.

#### Não existe bala de prata
- Frederick Brooks, pioneiro da Engenharia de Software, argumenta que existem dificuldades essenciais e acidentais no desenvolvimento de software. As essenciais são inerentes à área e não serão superadas por novas tecnologias ou métodos. Portanto, não existem "balas de prata" ou soluções milagrosas na Engenharia de Software.

## O que se Estuda em Engenharia de Software?
O SWEBOK (Guide to the Software Engineering Body of Knowledge), documento, organizado pela IEEE Computer Society. Define 12 áreas de conhecimentos na Engenhariade Software:

1. Engenharia de Requisitos

2. Projeto de Software

3. Construção de Software

4. Testes de Software

5. Manutenção de Software

6. Gerência de Configuração

7. Gerência de Projetos

8. Processos de Software

9. Modelos de Software

10. Qualidade de Software

11. Prática Profissional

12. Aspectos Econômicos

### Engenharia de Requisitos
- A Engenharia de Requisitos é um conjunto de atividades para definir, analisar, documentar e validar os requisitos de um sistema. Os requisitos podem ser funcionais (o que o sistema deve fazer) ou não-funcionais (como o sistema deve operar). Por exemplo, em um sistema de home-banking, os requisitos funcionais incluem operações bancárias, enquanto os não-funcionais incluem desempenho, disponibilidade, segurança, privacidade, entre outros.

### Projeto de Software
- O projeto de software define as principais unidades de código e suas interfaces, sem entrar em detalhes de implementação. Interfaces providas são serviços que uma unidade de código oferece, enquanto interfaces requeridas são aquelas necessárias para o funcionamento da unidade. Por exemplo, a classe ContaBancaria fornece uma interface e depende da interface da classe Cliente. Quando o projeto é feito em um nível mais alto, ele é classificado como projeto arquitetural.

### Construção de Software
- A Construção é a fase de implementação ou codificação do sistema. Envolve decisões sobre algoritmos, estruturas de dados, frameworks, bibliotecas, tratamento de exceções, padrões de nomes, layout e documentação de código. Também inclui a escolha de ferramentas de desenvolvimento, como compiladores, IDEs, depuradores, gerenciadores de bancos de dados e ferramentas de interface.

### Testes de Software
- Testes de software envolvem a execução de um programa para verificar seu comportamento. Existem vários tipos de testes, incluindo testes de unidade, integração, performance e usabilidade. Testes servem para verificação (garantir que o sistema atende à sua especificação) e validação (garantir que o sistema atende às necessidades dos clientes). A diferença entre verificação e validação é resumida pelas perguntas: "Estamos implementando o sistema corretamente?" e "Estamos implementando o sistema correto?". Além disso, é importante distinguir entre defeitos, bugs e falhas.

### Manutenção e Evolução de Software
- A manutenção pode ser classificada em corretiva (corrigir bugs reportados), preventiva (corrigir bugs latentes), adaptativa (adaptar o sistema a mudanças no ambiente), refactoring (melhorar o código ou projeto mantendo o comportamento) e evolutiva (incluir novas funcionalidades ou aperfeiçoar as existentes). Essas manutenções permitem que os sistemas de software sejam usados por décadas, preservando seu valor para os clientes.

### Gerência de Configuração
- A Gerência envolve o uso de sistemas de controle de versões, como o git, para armazenar e restaurar todas as versões de um software. Além disso, inclui a definição de políticas para gerenciar as versões de um sistema, incluindo a identificação das releases. As releases podem ser identificadas no formato x.y.z, onde cada incremento representa uma correção de bugs (patch), pequenas funcionalidades (versão minor) ou grandes mudanças (versão major). Esse esquema é conhecido como versionamento semântico.

###
- Negociação de contratos, gerência de recursos humanos, gerência de riscos, marketing e finanças. Stakeholders, que são todas as partes interessadas no projeto, incluem desenvolvedores, clientes, gerentes, empresas subcontratadas, fornecedores e até governos. Uma peculiaridade dos projetos de software, como observado por Frederick Brooks, é que adicionar novos desenvolvedores a um projeto atrasado pode atrasá-lo ainda mais.

    **Lei de Brooks:**
    "A inclusão de novos desenvolvedores em um projeto que está atrasado contribui para torná-lo ainda mais atrasado."

### Processos de Desenvolvimento de Software
- Definem as atividades e etapas para construir e entregar um sistema. Existem dois tipos principais: Processos Waterfall (ou em cascata) e Processos Ágeis (ou incrementais ou iterativos). Waterfall, inspirado em engenharias tradicionais, propõe etapas sequenciais, mas foi criticado por atrasos e problemas. Em contraste, os processos ágeis, propostos em 2001, defendem a construção incremental e iterativa do sistema, validando pequenos incrementos de funcionalidade com os usuários. Já os processos ágeis tiveram grande impacto na indústria de software e são usados por diversas organizações, a ideia é que um sistema deve ser construído de forma incremental e iterativa.

    Fases de um processo Waterfall:
![Processo de Waterfall](https://engsoftmoderna.info/figs/cap1/waterfall.svg)

### Modelos de Software
- representações de alto nível de um sistema, usados para analisar suas propriedades e características essenciais sem a necessidade de examinar o código-fonte. Eles podem ser criados antes da implementação do código (Engenharia Avante) ou para entender um código existente (Engenharia Reversa). Frequentemente, são baseados em notações gráficas, como a UML, que possui vários diagramas para representar diferentes aspectos de um sistema.

### Qualidade de Software
- A qualidade do software é avaliada em duas dimensões: externa (correção, robustez, eficiência, portabilidade, facilidade de uso e compatibilidade) e interna (modularidade, legibilidade do código, manutenibilidade e testabilidade). Para garantir a qualidade, são usadas métricas e práticas como revisões de código. As revisões ajudam a detectar bugs antecipadamente e garantem a qualidade interna do código.
### Prática Profissional
- A prática envolve questões desde a formação até a regulamentação da profissão. Há preocupações sobre a responsabilidade ética dos profissionais, especialmente em uma sociedade cada vez mais mediada por software. Sociedades científicas, como a ACM e a IEEE, possuem códigos de ética para orientar os profissionais a exercerem seu ofício de forma ética e respeitada.
### Aspectos Econômicos
- Decisões econômicas no desenvolvimento de sistemas, como o modelo de rentabilização ou o preço de um aplicativo. Um conceito importante é o custo de oportunidade, que são os benefícios perdidos ao escolher uma opção em detrimento de outra, como corrigir bugs ou implementar novas funcionalidades.
## Classificação de Sistemas de Software
- A classificação de Bertrand Meyer divide os sistemas de software em três tipos: 
  - Sistemas C (Casuais), que não precisam de alta qualidade e são pequenos e não críticos; 
  - Sistemas A (Acute), que são críticos e qualquer falha pode causar grande prejuízo, exigindo processos rígidos de desenvolvimento; e 
  - Sistemas B (Business), que se beneficiam dos conceitos de Engenharia de Software para aumentar a produtividade e a qualidade, tanto interna quanto externa.