# Avaliação de Analista de Qualidade

Questões Teóricas
<details>
    <summary>

## 1. Descreva a diferença entre QA, QC e Testing, fornecendo exemplos práticos de cada

    </summary>



### QA, QC e Testing: Uma Visão Geral

- **QA, QC e Testing** são termos frequentemente utilizados no contexto da garantia da qualidade, especialmente no desenvolvimento de software, mas também se aplicam a outros setores. Embora estejam interligados, cada um possui um foco e um conjunto de atividades específicas.

#### Quality Assurance (QA) - Garantia da Qualidade

- **Foco:** O QA se concentra em **prevenir** defeitos e garantir que os processos de desenvolvimento sejam eficientes e eficazes. É uma abordagem proativa que visa estabelecer um ambiente de qualidade desde o início do projeto.
- **Atividades:**
- **Definição de padrões e processos:** Estabelecer critérios de qualidade, melhores práticas e procedimentos para todas as fases do desenvolvimento.
- **Análise de riscos:** Identificar potenciais problemas e tomar medidas para mitigá-los.
- **Revisão de requisitos:** Garantir que os requisitos do cliente sejam claros e completos.
- **Treinamento:** Capacitar a equipe sobre as práticas de qualidade.
- **Exemplo:** Um time de QA pode criar um guia de estilo para o código, realizar revisões de código regularmente e estabelecer um processo de aprovação para mudanças no sistema.

#### Quality Control (QC) - Controle da Qualidade

- **Foco:** O QC se concentra em **identificar e corrigir** defeitos nos produtos ou processos. É uma abordagem reativa que visa garantir que o produto final atenda aos requisitos de qualidade.
- **Atividades:**
- **Testes:** Executar testes para verificar se o produto funciona conforme o esperado.
- **Inspeções:** Realizar inspeções visuais e funcionais para detectar defeitos.
- **Verificação de conformidade:** Comparar o produto com os requisitos e padrões estabelecidos.
- **Exemplo:** Um time de QC pode executar testes unitários, de integração e de sistema para identificar bugs em um software, além de realizar inspeções visuais para verificar se a interface do usuário está de acordo com as diretrizes de design.

#### Testing - Teste

- **Foco:** O testing é uma parte integrante do QC e envolve a execução de atividades para verificar se um produto ou sistema atende aos requisitos especificados.
- **Tipos de testes:**
- **Testes unitários:** Verificam o funcionamento de unidades individuais de código.
- **Testes de integração:** Verificam se diferentes componentes do sistema funcionam juntos.
- **Testes de sistema:** Verificam o sistema como um todo.
- **Testes de aceitação:** Verificam se o sistema atende aos requisitos do cliente.
- **Exemplo:** Um engenheiro de testes pode criar casos de teste para verificar se um formulário de cadastro funciona corretamente, incluindo a validação de dados e a exibição de mensagens de erro.

### Relação entre QA, QC e Testing

- **QA** estabelece as bases para a qualidade, definindo processos e padrões.
- **QC** implementa as atividades de controle da qualidade, incluindo os testes.
- **Testing** é uma parte fundamental do QC, fornecendo evidências de que o produto atende aos requisitos.

**Em resumo:**

- **QA** é a garantia de que estamos fazendo as coisas da maneira certa.
- **QC** é a verificação de que as coisas foram feitas corretamente.
- **Testing** é a atividade de verificar se o produto funciona como esperado.

**Exemplo prático unindo os três:**

Imagine o desenvolvimento de um aplicativo de e-commerce.

- **QA:** A equipe define um processo de desenvolvimento ágil, estabelece padrões de codificação e cria um guia de estilo para a interface do usuário.
- **QC:** A equipe realiza testes automatizados para verificar o funcionamento das funcionalidades do carrinho de compras, além de testes manuais para garantir a usabilidade da interface.
- **Testing:** Um engenheiro de testes cria casos de teste para verificar se o processo de pagamento funciona corretamente, incluindo a integração com diferentes gateways de pagamento.

**Em um projeto de sucesso, QA, QC e Testing trabalham em conjunto para garantir a entrega de um produto de alta qualidade.**

</details>

## 2. Explique como as metodologias ágeis (Scrum, Kanban) impactam o ciclo de teste de software

As metodologias ágeis, como Scrum e Kanban, revolucionaram a forma como desenvolvemos software, e o ciclo de teste não ficou de fora. Ao adotar uma abordagem mais flexível e iterativa, essas metodologias trouxeram uma série de mudanças significativas para o processo de testes.

### Impacto das Metodologias Ágeis no Ciclo de Teste

- **Teste Contínuo:** Ao invés de grandes ciclos de teste ao final do desenvolvimento, as metodologias ágeis incentivam o teste contínuo em cada sprint. Isso permite identificar e corrigir defeitos mais rapidamente, reduzindo o custo de correção e aumentando a qualidade do software.
- **Colaboração entre Desenvolvedores e Testers:** A comunicação e a colaboração são fundamentais nas metodologias ágeis. Desenvolvedores e testadores trabalham juntos desde o início do projeto, o que facilita a identificação de requisitos, a criação de testes e a resolução de problemas.
- **Automação de Testes:** A automação de testes é essencial para garantir a velocidade e a repetibilidade dos testes em um ambiente ágil. Ferramentas de automação permitem executar um grande número de testes em pouco tempo, liberando os testadores para se concentrarem em atividades de maior valor.
- **Testes de Aceitação pelo Usuário:** Os usuários finais estão mais envolvidos no processo de desenvolvimento ágil. Isso permite que eles forneçam feedback constante sobre o produto, garantindo que o software atenda às suas necessidades e expectativas.
- **Adaptação a Mudanças:** As metodologias ágeis são altamente adaptáveis a mudanças. Os planos de teste podem ser ajustados a cada sprint para refletir as novas funcionalidades e requisitos.

### Scrum e Kanban: Diferenças e Impactos no Teste

- **Scrum:**
  - **Papéis:** O Scrum Master facilita o processo, o Product Owner define os requisitos e a equipe de desenvolvimento é responsável pela implementação e pelos testes.
  - **Eventos:** As reuniões diárias, as revisões de sprint e as retrospectivas são oportunidades para discutir o progresso dos testes e identificar áreas de melhoria.
  - **Artefatos:** O Product Backlog contém os requisitos do produto, enquanto o Sprint Backlog detalha as tarefas a serem realizadas em cada sprint.

- **Kanban:**
  - **Fluxo de Trabalho:** O Kanban visualiza o fluxo de trabalho, desde a criação de um item até a sua conclusão. As tarefas são organizadas em colunas, como "A Fazer", "Em Andamento" e "Concluído".
  - **Limites de Trabalho em Processo (WIP):** O Kanban limita o número de tarefas em cada etapa, evitando que o trabalho seja sobrecarregado.
  - **Melhoria Contínua:** O Kanban enfatiza a melhoria contínua do processo, identificando e eliminando gargalos.

### Benefícios da Adoção de Metodologias Ágeis para o Teste de Software

- **Maior qualidade do software:** Devido ao teste contínuo e à colaboração entre as equipes.
- **Redução de custos:** Identificação e correção de defeitos mais cedo no ciclo de desenvolvimento.
- **Aumento da satisfação do cliente:** Entrega mais rápida de funcionalidades e maior alinhamento com as necessidades do usuário.
- **Maior flexibilidade:** Adaptação a mudanças e novos requisitos.
- **Aumento da produtividade:** Automação de testes e foco em atividades de maior valor.

Em resumo, as metodologias ágeis transformaram o ciclo de teste de software, tornando-o mais eficiente, colaborativo e focado na entrega de valor ao cliente. Ao adotar práticas ágeis, as equipes de desenvolvimento podem criar produtos de alta qualidade mais rapidamente e com menos riscos.

## 3. Elabore um plano de teste para uma aplicação web de Prova Online, considerando diferentes tipos de testes (funcional, não funcional, regressão, integração)

## 4. Discuta a importância da priorização de casos de teste e como isso afeta a eficácia do processo de teste

## 5. Descreva como integrar testes automatizados em um pipeline CI/CD, utilizando ferramentas como Jenkins ou GitLab CI ou Azure DevOps

## 6. Compare as ferramentas de automação de testes Cypress, Appium e Selenium, destacando vantagens e desvantagens de cada

## 7. Explique como lidar com elementos dinâmicos em uma página web durante a automação de testes

## 8. Descreva um caso de teste manual para uma funcionalidade de pagamento em um e-commerce, considerando diferentes métodos de pagamento

## 9. Discuta a importância do teste exploratório e como ele pode ser utilizado em conjunto com testes automatizados

## 10. Elabore um plano de teste para uma aplicação de realidade aumentada, considerando aspectos de usabilidade e experiência do usuário

## 11. Explique como priorizar e reportar defeitos encontrados durante testes manuais

## 12. Explique a importância dos testes de carga e stress em uma aplicação de software

## 13. Descreva como utilizar Git para controle de versão em um projeto de software

Questões Práticas

(Disponibilize o link do GitHub com a solução)

## 14. Desenvolva com Cypress um dos planos de teste criados para aplicação web de Prova Online

## 15. Desenvolva um caso de teste para uma funcionalidade específica de um aplicativo móvel de uma Clínica Odontológica, considerando diferentes cenários de uso

## 16. Escreva um exemplo de código em Cypress para automatizar um teste de login em uma aplicação web que usa Email, CPF e Senha para entrar no sistema

## 17. Elabore dois testes automatizados para uma API RESTfull de Controle de Ponto de funcionário,utilizando uma ferramenta de sua escolha

## 18. Crie um script Cypress que realize upload de um arquivo. O caminho do arquivo deve ser um parâmetro do script. Lidar com diferentes tipos de arquivos e cenários de erro (arquivo inexistente, tipo de arquivo incorreto)

## 19. Escreva um exemplo de código como realizar testes de performance em uma aplicação web, utilizando ferramentas de sua escolha

## 20. Elabore um exemplo de como realizar uma avaliação de segurança em uma API RESTfull