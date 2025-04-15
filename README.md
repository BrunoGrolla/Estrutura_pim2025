# 📌 Sistema de Chamados com Soluções IA  

![Status](https://img.shields.io/badge/status-em%20planejamento-blue)

Um sistema de chamados para empresas que utiliza **Inteligência Artificial** para sugerir possíveis soluções antes da intervenção humana, otimizando o suporte técnico e reduzindo o tempo de atendimento

---

## 📖 Sobre o Projeto  .
O **Sistema de Chamados com Soluções IA** é uma plataforma desenvolvida para empresas que desejam aprimorar o suporte técnico por meio da automação inteligente.  

🔹 **Objetivo principal:** Reduzir o tempo de resposta no atendimento de chamados utilizando IA para sugerir soluções automáticas.  
🔹 **Como funciona?** O usuário abre um chamado, a IA analisa a descrição do problema e sugere possíveis soluções com base em uma base de conhecimento e aprendizado de máquina. Caso nenhuma sugestão resolva a questão, o chamado é encaminhado para um atendente humano.  
🔹 **Público-alvo:** Empresas que buscam melhorar o suporte técnico e reduzir custos operacionais.  
🔹 **Benefícios esperados:**  
✔ Agilidade no atendimento  
✔ Redução da carga de trabalho do suporte humano  
✔ Aprendizado contínuo para aprimorar as respostas  

---

# 📋 Requisitos do Sistema de Chamados

## 🔐 Login de Funcionário
- Login com e-mail e senha
- Validação de credenciais antes do acesso
- Verificação de hierarquia (atendente/gerente/admin)

## 📝 Cadastro de Chamado
- Criação de chamados com título, descrição, área e prioridade
- Notificação por e-mail ao criar chamado

## ⚠️ Prioridade de Chamado
- Classificação em Baixa/Média/Alta prioridade
- Notificação imediata para Alta prioridade
- Reclassificação por atendentes/gerentes

## ⏱️ SLA (Service Level Agreement)
- Prazos máximos por prioridade:
- Alertas de proximidade do prazo limite
- Relatórios de cumprimento/violação de SLA

## 🏷️ Segmentação de Área
- Roteamento automático para áreas 
- Visualização restrita por área
- Acompanhamento em tempo real pelo solicitante

## 🤖 Inteligência Artificial
- Sugestão de soluções baseadas em histórico
- Classificação automática de prioridade
- Recomendação de área responsável

---

## 📌 Backlog do Produto  
O backlog contém as principais funcionalidades que serão desenvolvidas no sistema.  

### **📍 Épicos e Funcionalidades**  
✅ **Login de Funcionário**  

✅ **Cadastro de Chamado**  

✅ **Prioridade de Chamado**  

✅ **SLA**  

✅ **Segmentação de Área**  

✅ **Inteligência Artificial**  

---

## 📌 Diagramas do Sistema  
Os diagramas a seguir ilustram a estrutura e funcionamento do sistema.

## 📌 Diagramas do Sistema

### 1. Diagrama de Casos de Uso  
![Login de Funcionário](https://i.imgur.com/JbR5WFF.png)  
![Cadastro de Chamado](https://i.imgur.com/45fvIXg.png)  
![Prioridade de Chamado](https://i.imgur.com/j66C0tJ.png)  
![SLA](https://i.imgur.com/JO3SYQe.png)  
- O SLA para o desenvolvimento de diagramas de casos de uso estabelece que o fornecedor se compromete a entregar o diagrama inicial em até 7 dias úteis, com até duas rodadas de revisão dentro do prazo de 5 dias úteis para cada solicitação de alteração. O diagrama deverá refletir com precisão os requisitos do sistema, e após a entrega, o cliente terá direito a suporte por até 15 dias úteis para ajustes ou esclarecimentos. Caso haja descumprimento dos prazos ou requisitos, serão aplicadas penalidades, conforme acordado no contrato, incluindo possíveis descontos ou prorrogação sem custos adicionais.
![Segmentação de Área](https://i.imgur.com/bZmkFj5.png)  
-Segmentação de Área:

A segmentação de área de atendimento permite ao administrador do sistema definir e organizar as áreas responsáveis pelo tratamento dos chamados técnicos. Essa segmentação possibilita o roteamento automático dos chamados conforme o conteúdo informado pelo usuário, otimizando o fluxo de atendimento e contribuindo para maior agilidade e assertividade na resolução de problemas.

Objetivos:
-Direcionar chamados para a equipe correta de forma automática.

-Filtrar visualizações e acessos por área de atuação.

-Melhorar o tempo de resposta e a eficiência no atendimento.-Alimentar o sistema de IA com dados segmentados por área, aprimorando sugestões de soluções futuras.

_Ator Principal
-Administrador

_Atores Secundários
-Sistema
-Atendente
-Usuário

![Inteligência Artificial](https://i.imgur.com/ibRFKUi.png)  

### 2. Diagrama de Classes  
![Login de Funcionário](https://i.imgur.com/yfkmZQe.png)  
![Cadastro de Chamado](https://i.imgur.com/5xqC676.png)  
![Prioridade de Chamado](https://i.imgur.com/2qeqUqu.png)  
![SLA](https://i.imgur.com/CMoWTLr.png)  
![Segmentação de Área](https://i.imgur.com/YWVXTEP.png) 
![Inteligência Artificial](https://i.imgur.com/HX2Ha8V.png)  

### 3. Diagrama de Sequência  
![Login de Funcionário](https://i.imgur.com/62JYV3O.png)  
![Cadastro de Chamado](https://i.imgur.com/MGZmQZg.png)  
![Prioridade de Chamado](https://i.imgur.com/DITTVXe.png)  
![SLA](https://i.imgur.com/Qo94bfn.png)  
![Segmentação de Área](https://i.imgur.com/bMPBbdx.png)  
![Inteligência Artificial](https://i.imgur.com/hxR2Cu6.png)  

### 4. Diagrama de Implantação  

### 5. Sprints Planejadas
Cada sprint terá duração de 2 semanas.

#### Sprint 1 - Autenticação e Perfis de Usuário
Estabelecer a base de segurança e autenticação do sistema.

-Implementar sistema de login com e-mail e senha
-Validação de credenciais
-Diferenciação de perfis (usuário comum, atendente, gerente, admin)
-Controle de sessão

#### Sprint 2 - Abertura e Gestão de Chamados
Permitir a criação e visualização dos chamados.

-Cadastro de chamado (título, descrição, área, prioridade)
-Notificação por e-mail na criação
-Listagem de chamados por usuário
-Visualização de detalhes de um chamado

#### Sprint 3 - Gestão de Prioridades e SLA
Implementar lógica de prioridade e controle de prazos.

-Classificação de prioridade (Baixa, Média, Alta)
-Reclassificação por atendentes/gerentes
-Configuração de SLAs por prioridade
-Alertas de proximidade do prazo limite
-Relatórios de cumprimento/violação de SLA

#### Sprint 4 - Segmentação de Área e Roteamento
Organizar o atendimento por áreas específicas.

-Cadastro e gestão de áreas
-Roteamento automático com base na descrição
-Visualização restrita de chamados por área
-Acompanhamento em tempo real do chamado pelo solicitante

#### Sprint 5 - Inteligência Artificial
Início da criação com IA.

-Integração com motor de IA (ex: modelo NLP treinado ou integração com serviço externo)
-Sugestão de solução com base na descrição do problema
-Classificação automática da prioridade
-Sugestão de área responsável

#### Sprint 6 - Refinamento da IA + Relatórios Gerenciais
Aprimorar automações e oferecer dashboards.

-Treinamento contínuo do modelo de IA
-Feedback de efetividade da sugestão (foi útil ou não)

#### Sprint 7 - Testes Finais
Garantir qualidade do sistema antes da entrega.

-Testes automatizados e manuais
-Ajustes finais.

### ✅ Requisitos Funcionais por Módulo
#### Login de Funcionário
-O sistema deve permitir login com e-mail e senha.
-O sistema deve validar credenciais e exibir mensagens de erro apropriadas.
-O sistema deve identificar e controlar o nível de acesso com base no perfil do usuário.

#### Cadastro de Chamado
-O usuário deve poder registrar um novo chamado com título, descrição, área e prioridade.
-O sistema deve notificar o usuário por e-mail após o cadastro do chamado.
-O usuário pode acompanhar o status do chamado em tempo real.

#### Prioridade de Chamado
-O sistema deve classificar chamados em Baixa, Média ou Alta prioridade.
-O sistema deve notificar imediatamente o atendente no caso de prioridade Alta.
-Atendentes e gerentes podem reclassificar a prioridade de um chamado.

#### SLA 
-O sistema deve atribuir prazos máximos para resolução conforme a prioridade.
-O sistema deve emitir alertas próximos ao vencimento do SLA.
-O sistema deve gerar relatórios de cumprimento ou violação de SLA.

#### Segmentação de Área
-O sistema deve permitir o cadastro de áreas de atendimento.
-O sistema deve realizar roteamento automático com base na descrição.
-O sistema deve restringir visualizações de chamados a membros da respectiva área.

#### Inteligência Artificial
-A IA deve analisar a descrição do chamado e sugerir possíveis soluções.

### ✅ Requisitos Não Funcionais (Simplificados)
#### Segurança
-O sistema deve ter login com senha protegida.
-Apenas usuários autorizados podem acessar suas áreas específicas.

#### Desempenho
-O sistema deve carregar as páginas em até 3 segundos.
-As sugestões da IA devem aparecer em até 5 segundos.

#### Disponibilidade
-O sistema deve funcionar de forma estável durante o horário comercial.

#### Usabilidade
-O sistema deve ser fácil de usar, com botões e textos claros.
-Deve funcionar bem em computadores e celulares.

#### Compatibilidade
-O sistema deve funcionar nos navegadores mais usados (Chrome, Firefox, Edge).


## 📝 Status do Projeto  
- [x] Definição do escopo  
- [x] Modelagem dos diagramas UML  
- [ ] Desenvolvimento do sistema, banco de dados e interface. *(Em desenvolvimento...)*  
- [ ] Testes e ajustes  
- [ ] Lançamento   

---

## 📄 Licença  
Este projeto está sob a licença **MIT**. Para mais detalhes, veja o arquivo [LICENSE](LICENSE).

---

📌 **Equipe de desenvolvedores:

- [Bruno Grolla G925FE9](https://github.com/BrunoGrolla)  
- [Gabriel Guimarães F35CCG3](https://github.com/guimagabs)  
- [Matheus Silva G1013I7](https://github.com/MatheusSilva77)
- [Luciano Rafael N0841D5](https://github.com/lozss)
- [Marcella Mendes G8227I5](https://github.com/mahsouz444)
- [Halysson Lucas R189031](https://github.com/Hass-Lima)
  
---** 


