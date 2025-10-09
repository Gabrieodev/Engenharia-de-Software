# 🧠 Engenharia de Software

## Aula 1

### 📘 Engenharia de Software – Fundamentos

A **Engenharia de Software** é o ramo da engenharia que aplica métodos científicos, técnicos e organizacionais para o desenvolvimento de **sistemas de software confiáveis, eficientes e de qualidade**.

Ela não trata apenas da programação, mas de **todo o processo de criação e manutenção** de um sistema, conhecido como **ciclo de vida do software** — que vai desde a **ideia inicial e o levantamento de requisitos**, passando pelo **projeto e codificação**, até chegar aos **testes, implantação e manutenção**.

O principal objetivo é garantir que o produto final **atenda às necessidades do usuário**, dentro do prazo, do orçamento e com qualidade. Para isso, os engenheiros utilizam **metodologias de desenvolvimento** (como ágil, cascata, incremental), **ferramentas de apoio** (IDEs, controle de versão) e **boas práticas** de documentação e testes.

---

### 🧩 Características do Software

O software é um **produto diferente dos bens físicos**, com características únicas:

* **Produto desenvolvido, não manufaturado:** criado por meio de **projeto e lógica**, não de montagem em linha de produção.
* **Não se desgasta, mas se deteriora:** pode **ficar obsoleto** ou falhar conforme o ambiente e as necessidades mudam.
* **Feito sob medida:** desenvolvido para **resolver um problema específico**, o que o torna poderoso, porém menos adaptável.
* **Quanto mais especializado, menos flexível:** sistemas focados em um único objetivo exigem **grande esforço para adaptação**.
* **Tamanho influencia na manutenção:** projetos grandes precisam de **mais recursos humanos e técnicos** para manter a qualidade.

---

### 🎯 Em Resumo

A Engenharia de Software busca **organização, qualidade e previsibilidade** no desenvolvimento.
Combina **ciência da computação, gestão de projetos e boas práticas de engenharia**, transformando ideias em soluções tecnológicas que evoluem com o mundo digital.

---

## 🧠 Natureza e Ciclo de Vida do Software x Hardware

Embora trabalhem juntos, **software e hardware** têm naturezas diferentes:

### ⚙️ Ciclo de Vida do Hardware

Segundo Pressman (2011), o hardware segue a **“curva da banheira”**:

* **Início:** altas taxas de falhas por defeitos de fabricação.
* **Estabilidade:** período de funcionamento confiável.
* **Desgaste:** falhas aumentam por **poeira, calor, vibração e uso contínuo**.

### 💻 Ciclo de Vida do Software

O **software não sofre desgaste físico**, mas se **degrada logicamente**:

* **Início:** manutenção intensa para correção de falhas.
* **Estabilidade:** funcionamento com poucas falhas.
* **Degradação:** modificações sucessivas introduzem **novos erros** e aumentam a complexidade.

🔍 **Conclusão:** o software **não envelhece**, mas **se deteriora pela falta de controle e excesso de modificações**.

---

## 🧩 Características Fundamentais do Software

* **Produto intelectual:** criado por lógica e projeto.
* **Não se desgasta fisicamente.**
* **Feito sob medida.**
* **Complexidade impacta custos e manutenção.**

---

## ⚠️ A Crise do Software (década de 1960)

Com o aumento da complexidade dos programas, surgiu a **Crise do Software**, que levou à criação da Engenharia de Software como disciplina formal.

### 💥 Principais causas:

* Falta de metodologias e planejamento;
* Projetos que **ultrapassavam prazos e orçamentos**;
* **Softwares ineficientes ou com falhas**;
* **Comunicação deficiente** entre analistas e usuários;
* Ausência de **métricas e controle de qualidade**.

Essa crise mostrou a necessidade de aplicar **princípios de engenharia** no desenvolvimento de software: planejamento, documentação, testes e padronização.

---

## 🧱 Definições de Engenharia de Software

### 📖 Segundo Friedrich Bauer (apud Pressman, 2011):

> “Engenharia de Software é o estabelecimento e o emprego de sólidos princípios de engenharia de modo a obter software de maneira econômica, que seja confiável e funcione de forma eficiente em máquinas reais.”

### 🧠 Segundo o IEEE:

> É a aplicação de uma abordagem **sistemática, disciplinada e quantificada** ao desenvolvimento, operação e manutenção de software.

Essas definições destacam o uso de **métodos científicos, processos bem definidos e ferramentas** para garantir **qualidade e previsibilidade**.

---

## ⚙️ Camadas da Engenharia de Software (Pressman, 2011)

1. **Foco na Qualidade:** compromisso contínuo com a melhoria de produtos e processos.
2. **Processo:** organiza o trabalho e garante previsibilidade — inclui **planejamento, cronogramas e controle de qualidade**.
3. **Métodos:** fornecem o **conhecimento técnico**, envolvendo:

   * Levantamento de requisitos;
   * Análise e modelagem;
   * Codificação e testes;
   * Suporte e manutenção.
4. **Ferramentas:** recursos automatizados que apoiam o processo, como IDEs, Git, testes automatizados e integração contínua.

---

## 🧭 Conclusão

A **Crise do Software** revelou que **programar não é engenheirar software**.
A Engenharia de Software surgiu para **planejar, medir, controlar e evoluir** sistemas com foco em qualidade.

Com **processos estruturados, métodos técnicos e ferramentas adequadas**, a disciplina garante que o software seja **eficiente, sustentável e seguro**, acompanhando o ritmo da inovação tecnológica.

---

## Aula 2 – Requisitos

### 🎯 Objetivos da Aula

* **Motivar a utilização da gerência de requisitos** no dia a dia dos projetos;
* **Apresentar os conceitos fundamentais** da gerência de requisitos;
* **Explorar os artefatos principais** utilizados nesse processo.

> ⚠️ Desenvolver sistemas vai muito além da programação! Antes de escrever uma linha de código, é essencial entender o problema, levantar as necessidades e alinhar expectativas com o cliente.

---

### 🧱 Importância da Gerência de Requisitos

O gerenciamento de requisitos é o **primeiro passo para garantir um sistema de qualidade**, entregue **no prazo**, **dentro do orçamento** e que realmente **atenda às necessidades do cliente**.

Uma **má gestão de requisitos** pode levar a retrabalho, atrasos e altos custos de manutenção. Erros descobertos após a entrega de um sistema podem custar **até 100 vezes mais** do que se fossem identificados durante a fase de especificação.

---

### 💸 Custo dos Erros

Erros em requisitos são os **mais caros** de corrigir quando descobertos tardiamente.
Principais causas:

* Técnicas de elicitação ou validação de requisitos inadequadas;
* Desconhecimento do domínio do problema;
* Inexperiência da equipe;
* Falta de acordo com o cliente;
* Falta de acompanhamento das mudanças de requisitos.

🔹 **Conclusão:** quanto mais cedo o erro é descoberto, **menor o custo** de correção.

---

### 📘 Conceitos Fundamentais

#### O que é um Requisito?

> Uma condição que o sistema deve contemplar para solucionar uma necessidade do cliente.

#### O que é Gerência de Requisitos?

> Processo sistemático para **capturar, organizar, documentar e gerenciar requisitos**, garantindo um **acordo contínuo** entre o cliente e a equipe sobre alterações ou exclusões de requisitos.

---

### ⚙️ Tipos de Requisitos

#### 🟢 Requisitos Funcionais

São as **funcionalidades específicas** que o sistema deve realizar.
**Exemplos:**

* Permitir o registro de usuários;
* Realizar consultas no banco de dados;
* Gravar imagens;
* Calcular impostos.

#### 🔵 Requisitos Não Funcionais

São as **características de qualidade** e restrições do sistema.
**Exemplos:**

* **Desempenho:** páginas devem carregar em menos de 3 segundos;
* **Segurança:** dados sensíveis devem ser criptografados;
* **Usabilidade:** interface simples e intuitiva;
* **Confiabilidade:** o sistema não deve falhar mais de X vezes por mês.

---

### 🔍 Análise do Problema

Antes de desenvolver qualquer sistema, é essencial **entender o problema real**.
Etapas principais:

1. **Compreender a necessidade real do cliente;**
2. **Identificar stakeholders** (pessoas envolvidas no sistema);
3. **Definir fronteiras e restrições** do sistema;
4. Criar um **glossário comum** de termos;
5. Documentar a **visão geral do sistema** (problema, solução, características);
6. **Formalizar o acordo** entre cliente e desenvolvedores.

👉 Essa fase evita retrabalho e garante que todos falem a “mesma língua”.

---

### 🧩 Modelos de Processos de Software

Os modelos de processo orientam **como o desenvolvimento é estruturado**. Eles representam **diferentes abordagens** para construir e evoluir sistemas.

#### 1. **Modelo em Cascata (Clássico)**

* Desenvolvimento **sequencial e linear** (análise → projeto → implementação → testes → manutenção);
* Ideal quando os requisitos são **bem definidos e estáveis**;
* Pouco recomendado hoje, pois **não lida bem com mudanças** durante o processo.

#### 2. **Modelo Incremental**

* O sistema é desenvolvido **em partes (incrementos)**;
* Permite **entregar versões parciais** que já agregam valor ao cliente;
* Cada incremento adiciona novas funcionalidades.

> Exemplo: primeiro módulo de login → depois relatórios → depois pagamentos.

#### 3. **Modelos Evolucionários**

Esses modelos aceitam que o software **evolui com o tempo**, adaptando-se às mudanças do negócio e às novas demandas do cliente.

* **Prototipação:** desenvolvimento iterativo com feedback contínuo do usuário; versões simples evoluem até o sistema final.
* **Modelo Espiral:** combina características do modelo cascata e da prototipagem; a cada iteração, o sistema é aprimorado com novos requisitos e validações.

---

### 🔄 Ciclo de Vida e Manutenção

Após a entrega do software:

* Defeitos não descobertos surgem no início da operação;
* O sistema entra em fase de **estabilidade**;
* **Novas modificações** podem introduzir erros, elevando os custos;
* O software **não se desgasta fisicamente**, mas **deteriora-se logicamente** com o tempo se não for atualizado.

---

### 💡 Conclusão

A **engenharia de requisitos** é essencial para o sucesso de qualquer projeto de software.
Ela garante:

* Melhor **comunicação com o cliente**;
* **Redução de retrabalho** e custos;
* **Aumento da qualidade e confiabilidade** do sistema.

> Em resumo, um sistema bem planejado é resultado de **requisitos bem gerenciados** — o código é apenas a consequência de um entendimento claro do problema.

---

# 🧠 Engenharia de Software

## Aula 3 – Engenharia de Requisitos

### 🎯 Objetivo da Aula

Compreender o papel da **Engenharia de Requisitos** dentro do ciclo de vida do software, identificando como ela transforma **necessidades do cliente** em **especificações técnicas claras e rastreáveis**.

A aula destaca a importância de **evitar ambiguidades**, **controlar mudanças** e **garantir que o sistema realmente resolva o problema proposto**, mantendo sempre o foco na qualidade e no alinhamento entre **usuário, equipe técnica e negócio**.

### 📘 Contexto Visual

A imagem a seguir ilustra o papel central da **Engenharia de Requisitos** como elo entre as necessidades do cliente e as soluções técnicas desenvolvidas pela equipe.
Ela evidencia como essa etapa organiza, documenta e traduz expectativas em requisitos bem definidos.

<img width="212" height="217" alt="Captura de tela 2025-10-08 210347" src="https://github.com/user-attachments/assets/b4fa3330-4988-4f70-b290-f78a98bd7b65" />

---


### 📘 O que é Engenharia de Requisitos

A **Engenharia de Requisitos** é uma disciplina fundamental da Engenharia de Software que se concentra em **definir, documentar e manter os requisitos** de um sistema.
Ela busca traduzir as **necessidades e expectativas do cliente** em uma base sólida que orienta todo o desenvolvimento.

> 💡 Mais do que listar funcionalidades, a Engenharia de Requisitos busca **entender o contexto**, **os objetivos de negócio** e **a experiência do usuário final**, garantindo que o produto final tenha **valor real** e **qualidade técnica**.

---

### ⚖️ Requisitos x Regras de Negócio

É comum confundir **requisitos** com **regras de negócio**, mas são conceitos diferentes e complementares:

| Conceito             | Descrição                                                                        | Exemplo                                                                                                               |
| -------------------- | -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| **Requisito**        | Define **o que** o sistema deve fazer.                                           | Validar número de cartão de crédito; Processar uma venda.                                                             |
| **Regra de Negócio** | Define **como** o sistema deve operar segundo políticas e restrições da empresa. | O cliente só pode concluir o cadastro se tiver um cartão válido; Compras acima de 4 itens iguais têm 10% de desconto. |

➡️ Ou seja, **os requisitos seguem as regras de negócio**, garantindo que o software atenda às políticas e estratégias da organização.

---

### 🔄 Processo de Engenharia de Requisitos

A Engenharia de Requisitos envolve **cinco etapas principais**, que garantem clareza, consistência e rastreabilidade durante todo o ciclo de vida do projeto.

#### 1. **Elicitação dos Requisitos**

Coleta das **necessidades e expectativas** dos stakeholders (usuários, clientes, gestores etc.).
**Técnicas utilizadas:**

* Entrevistas;
* Questionários e pesquisas;
* Observação direta;
* Reuniões JAD (Joint Application Development);
* Workshops e brainstorming.

> O objetivo é capturar informações de forma colaborativa, garantindo que as necessidades reais sejam compreendidas.

---

#### 2. **Análise dos Requisitos**

Fase de **interpretação e refinamento** dos dados coletados.
Aqui são detectados **conflitos**, **inconsistências** e **prioridades**.
Também se avalia **se o requisito é realmente necessário** e se **agrega valor ao negócio**.

> Essa análise evita incluir exigências irrelevantes, duplicadas ou inviáveis.

---

#### 3. **Especificação dos Requisitos**

Consiste em **documentar os requisitos** de forma clara e estruturada.
Os principais artefatos produzidos incluem:

* **Documento de Visão** (propósito e objetivos do sistema);
* **Casos de Uso** (funcionalidades e interações do usuário);
* **Especificação de Interface Gráfica**;
* **Diagramas de fluxo ou modelos UML.**

> A boa documentação garante comunicação efetiva entre cliente, analistas e desenvolvedores.

---

#### 4. **Validação dos Requisitos**

Etapa para **garantir que os requisitos sejam corretos, completos e não ambíguos**.
É o momento de eliminar dúvidas e interpretações duplas, garantindo que o que foi escrito **reflete exatamente o que o cliente deseja**.

⚠️ **Exemplos de ambiguidade:**

* “O sistema deve ser fácil de usar.” → O que significa “fácil”?
* “O sistema deve ser rápido.” → Qual é o tempo máximo aceitável de resposta?

> A validação evita retrabalho, erros de interpretação e divergências futuras.

---

#### 5. **Gerenciamento dos Requisitos**

Refere-se ao **controle contínuo das mudanças** durante o projeto.
Como requisitos podem **mudar com o tempo**, é fundamental que cada alteração seja:

* **Rastreada** (origem e motivo da mudança);
* **Analisada quanto ao impacto** (prazo, custo e escopo);
* **Aprovada pelos stakeholders**.

> O gerenciamento mantém o projeto sob controle e garante que cada modificação seja legítima e viável.

---

### 🔁 Mudanças nos Requisitos

#### Por que os requisitos mudam?

* Perguntas erradas ou incompletas no início do projeto;
* Mudanças no negócio ou nas prioridades;
* Novas tecnologias ou limitações orçamentárias;
* Mudança de opinião dos usuários.

> As mudanças são **inevitáveis**, mas precisam ser **controladas e documentadas** para não comprometer o projeto.

---

### ⚙️ Análise de Impacto das Mudanças

Sempre que um requisito muda, é preciso **avaliar o impacto** sobre o sistema como um todo.

**Passos principais:**

1. Verificar se a mudança é realmente necessária;
2. Identificar quais requisitos e artefatos serão afetados;
3. Descrever a mudança e sua origem;
4. Estimar custo, esforço e riscos;
5. Decidir pela implementação ou não da mudança.

> Essa prática evita decisões impulsivas e protege a integridade do projeto.

---

### 🧭 Boas Práticas no Gerenciamento de Mudanças

* Manter **comunicação contínua com os stakeholders**;
* Ter um **canal formal** para solicitar alterações;
* **Documentar e rastrear** todas as mudanças;
* **Revisar o escopo** do projeto, se necessário;
* Garantir **acordo e aprovação** de todas as partes envolvidas.

---

### 🪞 A Importância dos Detalhes

> “Quem não dá importância aos detalhes, não terá êxito nas grandes coisas.”

Na engenharia de software, **detalhes definem a qualidade**.
Pequenas omissões ou ambiguidades em requisitos podem gerar **grandes retrabalhos e custos**.
Ser **detalhista** é compreender profundamente o problema, **antecipar riscos** e **assegurar qualidade em todas as etapas**.

---

### 💡 Conclusão

A Engenharia de Requisitos é o **alicerce de um software bem-sucedido**.
Ela garante:

* Clareza na comunicação com o cliente;
* Controle das mudanças e redução de falhas;
* Entregas mais previsíveis e de qualidade.

> Em resumo: **sem requisitos bem definidos, não há software bem desenvolvido.**
> A codificação é apenas a execução de um entendimento que deve começar claro, validado e bem gerenciado.

---


