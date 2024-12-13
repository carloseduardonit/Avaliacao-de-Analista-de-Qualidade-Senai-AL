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

<details>
  <summary>

## 2. Explique como as metodologias ágeis (Scrum, Kanban) impactam o ciclo de teste de software

  </summary>
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
  - **Fluxo de Trabalho:**
  O Kanban visualiza o fluxo de trabalho, desde a criação de um item até a sua conclusão. As tarefas são organizadas em colunas, como "A Fazer", "Em Andamento" e "Concluído".
  - **Limites de Trabalho em Processo (WIP):**
  O Kanban limita o número de tarefas em cada etapa, evitando que o trabalho seja sobrecarregado.
  - **Melhoria Contínua:**
  O Kanban enfatiza a melhoria contínua do processo, identificando e eliminando gargalos.

### Benefícios da Adoção de Metodologias Ágeis para o Teste de Software

- **Maior qualidade do software:**
Devido ao teste contínuo e à colaboração entre as equipes.
- **Redução de custos:**
Identificação e correção de defeitos mais cedo no ciclo de desenvolvimento.
- **Aumento da satisfação do cliente:**
Entrega mais rápida de funcionalidades e maior alinhamento com as necessidades do usuário.
- **Maior flexibilidade:**
Adaptação a mudanças e novos requisitos.
- **Aumento da produtividade:**
Automação de testes e foco em atividades de maior valor.

Em resumo, as metodologias ágeis transformaram o ciclo de teste de software, tornando-o mais eficiente, colaborativo e focado na entrega de valor ao cliente. Ao adotar práticas ágeis, as equipes de desenvolvimento podem criar produtos de alta qualidade mais rapidamente e com menos riscos.
</details>

<details>
  <summary>

## 3. Elabore um plano de teste para uma aplicação web de Prova Online, considerando diferentes tipos de testes (funcional, não funcional, regressão, integração)

  </summary>

- Plano de Teste para Aplicação Web de Prova Online

### 3.1. Introdução

#### 3.1.1 Objetivo

Este plano de teste tem como objetivo definir as estratégias e os procedimentos para garantir a qualidade da aplicação web de prova online, abrangendo testes funcionais, não funcionais, de regressão e de integração.

#### 3.1.2 Escopo

O escopo deste plano inclui todos os módulos da aplicação, desde o cadastro de usuários até a geração de relatórios de desempenho.

#### 3.1.3 Critérios de Entrada e Saída

- **Entrada:** Requisitos funcionais e não funcionais completos, ambiente de teste configurado e aplicação estável.
- **Saída:** Relatórios de testes detalhados, identificação de defeitos e aprovação para produção.

### 3.2. Tipos de Testes e Objetivos

- **Testes Funcionais:**
  - Verificar se todas as funcionalidades da aplicação estão funcionando conforme os requisitos.
- **Objetivos:**
  - Cadastro e login de usuários.
  - Criação e edição de provas.
  - Realização de provas por alunos.
  - Correção automática de provas.
  - Geração de relatórios.
- **Testes Não Funcionais:**
  - Avaliar o desempenho, usabilidade, segurança e compatibilidade da aplicação.
- **Objetivos:**
  - **Desempenho:** Tempo de resposta, capacidade de carga, uso de recursos.
  - **Usabilidade:** Facilidade de uso, intuitividade da interface.
  - **Segurança:** Proteção de dados, autenticação, autorização.
  - **Compatibilidade:** Funcionamento em diferentes navegadores e dispositivos.
- **Testes de Regressão:**
  - Verificar se novas funcionalidades não introduziram defeitos em funcionalidades já existentes.
- **Objetivos:**
  - Executar testes funcionais e não funcionais em todas as versões da aplicação.
- **Testes de Integração:**
  - Verificar a interação entre os diferentes componentes da aplicação.
- **Objetivos:**
  - Integração com banco de dados, sistemas de pagamento (se houver) e outros sistemas externos.

### 3.3. Estratégias e Técnicas de Teste

- **Testes manuais:** Para cenários complexos e testes exploratórios.
- **Testes automatizados:** Para testes repetitivos e de regressão, utilizando ferramentas como Selenium.
- **Testes de unidade:** Para verificar o funcionamento de módulos individuais.
- **Testes de API:** Para testar as interfaces de programação da aplicação.

### 3.4. Ambiente de Teste

- **Hardware:** Especificações dos servidores, dispositivos móveis.
- **Software:** Sistema operacional, banco de dados, navegadores, ferramentas de teste.
- **Dados:** Criação de um banco de dados de teste com dados realistas.

### 3.5. Critérios de Aceitação

- **Cobertura de testes:** Percentual de requisitos cobertos pelos testes.
- **Número de defeitos:** Quantidade de defeitos encontrados e corrigidos.
- **Tempo de execução dos testes:** Tempo médio para executar todos os testes.

### 3.6. Riscos e Mitigação

- **Riscos:** Defeitos críticos, atrasos na entrega, falta de recursos.
- **Mitigação:** Planos de contingência, comunicação frequente, acompanhamento do progresso.

### 3.7. Recursos

- **Equipe:** Testadores, desenvolvedores, analistas de qualidade.
- **Ferramentas:** Ferramentas de gerenciamento de testes, ferramentas de automação, ferramentas de análise de dados.

### 3.8. Cronograma

- **Atividades:** Criação de casos de teste, execução de testes, análise de resultados, geração de relatórios.
- **Prazos:** Datas de início e fim de cada atividade.

### 3.9. Documentação

- **Casos de teste:** Descrição detalhada de cada caso de teste, incluindo pré-condições, passos, resultados esperados e resultados reais.
- **Relatórios de defeitos:** Descrição detalhada de cada defeito encontrado.
- **Relatórios de testes:** Resumo dos resultados dos testes.

**Observações:**

- Este é um plano de teste genérico e pode ser adaptado de acordo com as especificidades da aplicação.
- É importante revisar e atualizar este plano regularmente ao longo do projeto.
- A comunicação entre a equipe de desenvolvimento e a equipe de testes é fundamental para o sucesso do projeto.

**Considerações Adicionais:**

- **Testes de usabilidade:** Avaliar a experiência do usuário com a aplicação.
- **Testes de segurança:** Verificar a vulnerabilidade da aplicação a ataques.
- **Testes de desempenho sob carga:** Simular um grande número de usuários simultâneos.
- **Testes de compatibilidade em diferentes dispositivos e navegadores:** Garantir que a aplicação funcione corretamente em diferentes ambientes.

Ao seguir este plano de teste, é possível garantir que a aplicação web de prova online seja entregue com alta qualidade e atenda às necessidades dos usuários.

</details>

<details>
  <summary>

## 4. Discuta a importância da priorização de casos de teste e como isso afeta a eficácia do processo de teste

  </summary>

A priorização de casos de teste é uma prática fundamental em qualquer processo de garantia de qualidade de software. Ela consiste em ordenar os casos de teste de acordo com sua importância e criticidade, visando otimizar o tempo e os recursos alocados para os testes.

### Por que a Priorização é Essencial?

- **Limitação de Tempo e Recursos:** Em projetos reais, o tempo e os recursos são limitados. Priorizar os casos de teste permite focar nos mais críticos e garantir que as funcionalidades mais importantes sejam testadas.
- **Gerenciamento de Riscos:** Ao identificar e priorizar os casos de teste que mais impactam o sistema, é possível reduzir o risco de falhas em áreas críticas.
- **Adaptação a Mudanças:** Em projetos ágeis, as prioridades podem mudar frequentemente. A priorização permite ajustar os planos de teste de acordo com as novas demandas.
- **Melhora da Eficiência:** Ao executar os casos de teste mais importantes primeiro, é possível identificar e corrigir defeitos mais rapidamente, acelerando o processo de desenvolvimento.

**Como a Priorização Afeta a Eficácia do Processo de Teste?**

- **Aumento da Cobertura de Testes:** Ao focar nos casos de teste mais importantes, é possível garantir uma maior cobertura de testes, reduzindo o risco de falhas.
- **Redução do Tempo de Teste:** A execução de um número menor de casos de teste, mas com maior impacto, reduz o tempo necessário para completar os testes.
- **Melhora da Qualidade do Software:** A identificação e correção de defeitos mais críticos no início do ciclo de desenvolvimento contribui para a entrega de um software com maior qualidade.
- **Melhor Tomada de Decisão:** A priorização permite que as equipes de teste tomem decisões mais informadas sobre quais testes executar e quando.

**Critérios para Priorização de Casos de Teste:**

- **Risco:** Casos de teste que envolvem funcionalidades críticas ou que podem causar maior impacto no sistema devem ter alta prioridade.
- **Impacto do Usuário:** Casos de teste que afetam diretamente a experiência do usuário também devem ser priorizados.
- **Estabilidade do Sistema:** Casos de teste que verificam a estabilidade do sistema, como testes de desempenho e de carga, são importantes.
- **Frequência de Falhas:** Casos de teste que identificaram defeitos em versões anteriores do software podem ser priorizados.
- **Custos de Correção:** Casos de teste que, se falharem, resultarão em custos de correção mais elevados, devem ser priorizados.

**Técnicas de Priorização:**

- **Análise de Risco:** Identificar os riscos associados a cada caso de teste.
- **Matriz de Risco:** Criar uma matriz que relaciona a probabilidade de ocorrência de um defeito com o impacto desse defeito.
- **Pareto:** Aplicar a regra dos 80/20, onde 80% dos defeitos são causados por 20% dos casos de teste.
- **Priorização Baseada em Valor de Negócio:** Priorizar os casos de teste que agregam mais valor ao negócio.

**Conclusão:**

A priorização de casos de teste é uma prática essencial para garantir a eficácia do processo de teste. Ao focar nos casos de teste mais importantes, as equipes de teste podem reduzir o tempo e os custos, aumentar a qualidade do software e tomar decisões mais estratégicas.

</details>  

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
