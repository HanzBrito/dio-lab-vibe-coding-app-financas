# 💸 App de Organização de Finanças Pessoais — HanzBrito Vibe Coding

## 1. Visão do Produto
Aplicativo de finanças pessoais que permite ao usuário registrar receitas, despesas e contas a pagar, acompanhar saldo e visualizar relatórios e gráficos.  
O diferencial é a abordagem **Vibe Coding**: interação leve e conversacional com IA, transformando prompts em soluções.

---

## 2. Problema
Muitas pessoas não conseguem manter controle financeiro porque:
- Aplicativos exigem muita entrada manual.
- Orçamentos são vistos como tediosos.
- Falta clareza sobre saldo, gastos e compromissos futuros.

---

## 3. Público-Alvo
Usuários que desejam organizar suas finanças sem burocracia.  
Exemplo: Pessoa com renda mensal de R$ 3.500 que precisa controlar aluguel, alimentação, transporte, lazer e contas.

---

## 4. Objetivo
Permitir visão clara da vida financeira, respondendo perguntas como:
- Quanto dinheiro eu tenho?
- Quanto recebi este mês?
- Quanto gastei?
- Onde estou gastando mais?
- Quais contas ainda preciso pagar?
- Quanto consegui economizar?

---

## 5. Funcionalidades (MVP)
- **Cadastro de receita** (entrada de dinheiro).
- **Cadastro de despesa** (saída de dinheiro).
- **Categorias** (moradia, alimentação, transporte, saúde, lazer, etc.).
- **Dashboard** com KPIs: saldo atual, receitas, despesas, economia.
- **Gráficos**: gastos por categoria, receitas x despesas, evolução do saldo.
- **Contas a pagar** com status (pendente, pago, atrasado).
- **Filtros** por período, categoria, tipo, forma de pagamento e status.
- **Histórico financeiro** em tabela.

---

## 6. Regras de Negócio
- Receita aumenta saldo: `Saldo = Saldo anterior + Receita`.
- Despesa reduz saldo: `Saldo = Saldo anterior - Despesa`.
- Conta paga entra nas despesas realizadas.
- Conta pendente aparece como compromisso futuro.
- Filtros atualizam KPIs e gráficos.

---

## 7. Interface (MVP)
- **Header:** Meu Controle Financeiro.
- **Dashboard:** saldo atual, receitas, despesas, economia.
- **Gráficos:** pizza (categorias), barras (receitas x despesas), linha (evolução saldo).
- **Ações rápidas:** nova receita, nova despesa, nova conta.
- **Histórico:** lista de movimentações.

---

## 8. Responsividade
Compatível com desktop, notebook, tablet e celular.

---

## 9. Fora do Escopo Inicial
- Integração bancária.
- Open Finance.
- Cartão automático.
- Investimentos e criptomoedas.
- IA avançada.
- Sincronização bancária.

---

## 10. Métricas de Sucesso
- Usuário consegue cadastrar receitas e despesas.
- Visualiza saldo e KPIs corretamente.
- Acompanha contas e status.
- Identifica principais gastos.
- Consulta histórico.
- Analisa evolução financeira via gráficos.

---

## 11. Vibe Coding
O desenvolvimento segue o conceito de **Vibe Coding**:
- Conversas naturais com IA.
- Prompts claros e bem estruturados.
- MVP rápido e funcional.
- Foco em experiência leve e criativa.


## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

 Meu **prompt final** (PRD); 

```txt markdown
Hoje
# PRD — Meu Controle Financeiro

## 1. Visão do produto

Criar um aplicativo de finanças pessoais que permita ao usuário registrar suas receitas e despesas, acompanhar seu saldo e entender para onde seu dinheiro está indo.

O sistema deverá transformar os registros financeiros em informações visuais e fáceis de entender.

---

# 2. Problema

Muitas pessoas recebem dinheiro durante o mês, realizam diversos pagamentos e compras, mas não conseguem visualizar claramente:

* quanto receberam;
* quanto gastaram;
* quanto ainda possuem;
* onde estão gastando mais;
* quais contas ainda precisam pagar;
* quanto conseguem economizar.

O aplicativo deverá centralizar essas informações.

---

# 3. Público-alvo

### Usuário principal

Pessoas que desejam organizar suas finanças pessoais.

### Exemplo

Uma pessoa que recebe R$ 3.500 por mês e precisa controlar:

* aluguel;
* alimentação;
* transporte;
* cartão de crédito;
* contas;
* lazer;
* investimentos.

---

# 4. Objetivo do produto

Permitir que o usuário tenha uma visão clara da própria vida financeira.

O sistema deverá responder perguntas como:

1. Quanto dinheiro eu tenho?
2. Quanto recebi este mês?
3. Quanto gastei?
4. Onde estou gastando mais?
5. Quanto ainda posso gastar?
6. Quais contas ainda preciso pagar?
7. Quanto consegui economizar?

---

# 5. Funcionalidades

## F1 — Cadastro de receita

O usuário poderá registrar uma entrada de dinheiro.

Exemplo:

```text
Descrição: Salário
Valor: R$ 3.500,00
Categoria: Salário
Data: 05/09/2026


## F2 — Cadastro de despesa

O usuário poderá registrar uma saída de dinheiro

Descrição: Supermercado
Valor: R$ 450,00
Categoria: Alimentação
Data: 10/09/2026
Forma de pagamento: Cartão


## F3 — Categorias

O sistema deverá permitir categorizar os gastos.

Categorias iniciais:

* Moradia
* Alimentação
* Transporte
* Saúde
* Educação
* Lazer
* Compras
* Contas
* Investimentos
* Outros


# 6. Dashboard financeira

A tela principal deverá apresentar os principais indicadores.

### KPI 1 — Saldo atual


Receitas - Despesas


### KPI 2 — Receitas do mês

Total recebido no período selecionado.

### KPI 3 — Despesas do mês

Total gasto no período selecionado.

### KPI 4 — Economia

Valor que sobrou depois das despesas.


Receitas - Despesas


# 7. Gráficos

## Gráfico 1 — Gastos por categoria

Mostrar quanto o usuário gastou em cada categoria.

Exemplo:


Alimentação     R$ 650
Moradia         R$ 1.000
Transporte      R$ 300
Lazer           R$ 200
Compras         R$ 450
`

## Gráfico 2 — Receitas x despesas

Comparar receitas e despesas ao longo dos meses.

Exemplo:


Janeiro     Receita: R$ 3.500 | Despesa: R$ 2.800
Fevereiro   Receita: R$ 3.500 | Despesa: R$ 3.100
Março       Receita: R$ 3.700 | Despesa: R$ 2.900


## Gráfico 3 — Evolução do saldo

Mostrar como o saldo do usuário evoluiu durante o período.



# 8. Contas a pagar

O usuário poderá cadastrar contas futuras.

Exemplo:


Aluguel
Vencimento: 10/10/2026
Valor: R$ 1.000
Status: Pendente


Status possíveis:

* Pendente
* Pago
* Atrasado


# 9. Filtros

O usuário poderá filtrar os dados por:

* período;
* categoria;
* tipo de movimentação;
* forma de pagamento;
* status.

### Exemplo


Período: Setembro/2026
Categoria: Alimentação
Tipo: Despesa


O sistema deverá mostrar somente as despesas de alimentação de setembro.

---

# 10. Regras de negócio

### Regra 1 — Receita

Uma receita aumenta o saldo.

```text
Saldo = Saldo anterior + Receita


### Regra 2 — Despesa

Uma despesa reduz o saldo.

```text
Saldo = Saldo anterior - Despesa


### Regra 3 — Conta paga

Quando uma conta for marcada como "Pago", ela deverá ser considerada no cálculo das despesas realizadas.

### Regra 4 — Conta pendente

Uma conta pendente deverá aparecer como compromisso financeiro futuro.

### Regra 5 — Filtros

Quando o usuário aplicar um filtro, os KPIs e gráficos deverão ser atualizados de acordo com o período selecionado.

---

# 11. Critérios de aceitação

## Receitas

* [ ] O usuário consegue cadastrar uma receita.
* [ ] O sistema calcula corretamente o valor.
* [ ] A receita aparece no histórico.
* [ ] A receita altera o saldo.

## Despesas

* [ ] O usuário consegue cadastrar uma despesa.
* [ ] O sistema permite selecionar uma categoria.
* [ ] A despesa aparece no histórico.
* [ ] A despesa reduz o saldo.

## Dashboard

* [ ] O saldo é exibido corretamente.
* [ ] O total de receitas é exibido.
* [ ] O total de despesas é exibido.
* [ ] O valor economizado é calculado.
* [ ] Os gráficos apresentam os dados registrados.

## Contas

* [ ] O usuário consegue cadastrar uma conta.
* [ ] O usuário consegue marcar uma conta como paga.
* [ ] O sistema identifica contas pendentes.
* [ ] O sistema identifica contas atrasadas.

---

# 12. Histórico financeiro

O sistema deverá apresentar uma tabela:

| Data  | Descrição | Categoria   | Tipo    |    Valor | Status   |
| ----- | --------- | ----------- | ------- | -------: | -------- |
| 05/09 | Salário   | Salário     | Receita | R$ 3.500 | Recebido |
| 08/09 | Aluguel   | Moradia     | Despesa | R$ 1.000 | Pago     |
| 10/09 | Mercado   | Alimentação | Despesa |   R$ 450 | Pago     |

---

# 13. Interface

A tela inicial deverá possuir:

### Header

**Meu Controle Financeiro**

### Dashboard

* Saldo atual
* Receitas
* Despesas
* Economia

### Gráficos

* Gastos por categoria
* Receitas x despesas
* Evolução do saldo

### Ações

* * Nova receita
* * Nova despesa
* * Nova conta

### Histórico

Lista das movimentações financeiras.

---

# 14. Responsividade

O sistema deverá funcionar em:

* Desktop
* Notebook
* Tablet
* Celular

---

# 15. Fora do escopo da primeira versão

Não serão implementados inicialmente:

* integração bancária;
* Open Finance;
* cartão de crédito automático;
* investimentos;
* criptomoedas;
* inteligência artificial;
* sincronização bancária automática.

Esses recursos poderão ser adicionados posteriormente.

---

# 16. Métricas de sucesso

O produto será considerado funcional quando o usuário conseguir:

1. cadastrar receitas;
2. cadastrar despesas;
3. visualizar seu saldo;
4. acompanhar contas;
5. identificar seus principais gastos;
6. consultar seu histórico;
7. analisar sua evolução financeira através dos gráficos.
8. MVP

revise este PRD (Product Requirement Document)  para me como um profissional de análise de sistema
Resumo executivo
Documento revisado do PRD — Meu Controle Financeiro com foco técnico e operacional para uso por analistas de sistema, PO e time de desenvolvimento. Contém: escopo claro, requisitos funcionais priorizados, regras de negócio formalizadas, modelo de dados sugerido, endpoints API básicos, critérios de aceitação testáveis, UX mínimo para o MVP e roadmap de entrega.

Escopo e objetivos (visão técnica)
Objetivo principal: permitir que o usuário registre receitas, despesas e contas a pagar, acompanhe saldo e visualize relatórios e gráficos que expliquem para onde o dinheiro está indo.

Escopo do MVP (incluir):

Cadastro de receitas e despesas.

Categorias configuráveis.

Dashboard com KPIs (Saldo, Receitas do período, Despesas do período, Economia).

Gráficos: Gastos por categoria; Receitas x Despesas por mês; Evolução do saldo.

Contas a pagar com status e vencimento.

Filtros por período, categoria, tipo, forma de pagamento e status.

Histórico transacional paginado.

Fora do escopo do MVP (confirmado):

Integração bancária automática; Open Finance; sincronização de cartões; investimentos; IA.

Requisitos funcionais detalhados, user stories e critérios de aceitação
Prioridade Alta (MVP)
F1 — Cadastro de receita

User story: Como usuário, quero registrar uma receita para que o saldo seja atualizado.

Campos: id, descrição, valor, categoria, data, conta (opcional), forma de recebimento, observações, usuário_id.

Critérios de aceitação: receita criada; aparece no histórico; saldo atualizado corretamente.

F2 — Cadastro de despesa

User story: Como usuário, quero registrar uma despesa para controlar gastos.

Campos: id, descrição, valor, categoria, data, forma de pagamento, conta vinculada, status (Pago/Pendente/Atrasado), usuário_id.

Critérios de aceitação: despesa criada; categoria selecionável; aparece no histórico; reduz saldo quando marcada como Pago.

F3 — Categorias

User story: Como usuário, quero categorias padrão e poder criar categorias customizadas.

Critérios de aceitação: categorias iniciais disponíveis; usuário pode criar/editar/excluir categorias próprias.

Contas a pagar

User story: Como usuário, quero cadastrar contas com vencimento para visualizar compromissos futuros.

Campos: id, título, valor, vencimento, recorrência, status, usuário_id.

Critérios de aceitação: conta criada; status alterável; contas pendentes aparecem em lista de compromissos; contas pagas entram nas despesas realizadas.

Dashboard e KPIs

User story: Como usuário, quero ver saldo e KPIs do período selecionado.

Critérios de aceitação: KPIs atualizam com filtros; cálculos corretos.

Filtros e histórico

User story: Como usuário, quero filtrar histórico por período, categoria, tipo, forma de pagamento e status.

Critérios de aceitação: filtros aplicados; KPIs e gráficos atualizados conforme filtro.

Prioridade Média
Exportar CSV do histórico.

Paginação e ordenação do histórico.

Notificações locais para contas próximas do vencimento.

Prioridade Baixa (futuro)
Multi-moeda; multi-conta bancária; relatórios fiscais.

Regras de negócio e cálculos (formal)
R1 — Atualização de saldo

Quando criar receita (status recebido):

Saldo = Saldo anterior + Valor_receita

Quando criar despesa marcada como Pago:

Saldo = Saldo anterior - Valor_despesa

Despesas pendentes não alteram saldo até serem marcadas como Pago.

Contas pagas são convertidas em despesa com referência à conta original.

R2 — Status de conta

Pendente: vencimento futuro.

Pago: data de pagamento registrada; contabilizada como despesa.

Atrasado: data atual > vencimento e status != Pago.

R3 — Filtros

KPIs e gráficos devem recalcular agregações apenas sobre o conjunto filtrado.

R4 — Recorrência

Lançamentos recorrentes geram eventos futuros sem alterar saldo até que sejam marcados como Pago/Recebido.

Modelo de dados sugerido (resumo) e API básica
Tabelas principais (resumido)
Entidade	Campos principais	Observação
users	id; nome; email; senha_hash	autenticação
transactions	id; user_id; tipo; descrição; valor; categoria_id; data; forma_pagamento; status	tipo: receita/despesa
categories	id; user_id; nome; tipo	tipo: receita/despesa/ambos
bills	id; user_id; título; valor; vencimento; recorrência; status	contas a pagar
accounts	id; user_id; nome; saldo_inicial	contas do usuário (opcional)


Endpoints REST sugeridos (exemplos)
Método	Endpoint	Função
POST	/api/transactions	Criar receita/despesa
GET	/api/transactions?period=YYYY-MM	Listar histórico com filtros
PATCH	/api/transactions/{id}	Atualizar status/editar
POST	/api/bills	Criar conta a pagar
PATCH	/api/bills/{id}/pay	Marcar como pago
GET	/api/dashboard?period=YYYY-MM	Retornar KPIs e dados para gráficos


Observação técnica: usar paginação, autenticação JWT e validação de entrada no backend; aplicar timezone consistente (UTC) e converter para exibição local.

UX / Dashboard / Visualizações e critérios de teste
Tela principal (MVP):

Header: título e menu.

KPIs em destaque: Saldo atual, Receitas (período), Despesas (período), Economia.

Ações rápidas: botão Nova receita, Nova despesa, Nova conta.

Gráficos: pizza/treemap para Gastos por categoria; barras para Receitas x Despesas; linha para Evolução do saldo.

Histórico: tabela com colunas Data | Descrição | Categoria | Tipo | Valor | Status.

Recomendações de interação:

Filtro por período com presets (Mês atual, Últimos 3 meses, Ano).

Drill-down: clicar em categoria filtra histórico e atualiza KPIs.

Indicação visual de contas vencendo em 7 dias e contas atrasadas.

Casos de teste essenciais (exemplos):

Criar receita R$3500 em 05/09/2026 → verificar histórico e saldo.

Criar despesa R$450 categoria Alimentação → verificar redução do saldo somente se marcada Pago.

Criar conta com vencimento futuro → aparece em lista de compromissos; não altera saldo.

Aplicar filtro Setembro/2026 + Categoria Alimentação → KPIs e gráficos refletem apenas esse subconjunto.

Não-funcionais, segurança e roadmap MVP
Não-funcionais

Segurança: TLS em trânsito; senhas com hashing; proteção contra CSRF/SQLi; políticas de CORS.

Performance: respostas de dashboard < 500ms para até 10k transações por usuário.

Disponibilidade: SLA objetivo 99.5% para MVP.

Escalabilidade: arquitetura stateless para backend; banco relacional com índices em user_id e data.

Roadmap sugerido

Sprint 0: Infra, autenticação, modelo de dados.

Sprint 1: CRUD transações + categorias + histórico.

Sprint 2: Dashboard KPIs + filtros.

Sprint 3: Gráficos e contas a pagar.

Sprint 4: QA, testes de aceitação, ajustes UX.

Release: MVP público.

Métricas de sucesso (MVP)

90% das operações de cadastro completadas sem erro.

KPIs corretos em 100% dos cenários de teste.

Tempo médio de resposta do dashboard < 500ms.
```



Ideia

Captura rápida do problema, público e objetivo. Resultado: one‑pager com hipótese de valor.

PRD (Product Requirement Document)

Documento estruturado com visão, público, funcionalidades, regras de negócio, KPIs e critérios de aceitação.

Design

Wireframes, fluxos de tela, protótipos de baixa fidelidade; validação de usabilidade com 2–3 usuários.

Decisões técnicas

Escolha de arquitetura, modelo de dados, APIs, autenticação, limites de performance e decisões de infra.

FSD (Functional Specification Document)

Especificação técnica detalhada por feature: endpoints, payloads, contratos, validações, mensagens de erro e testes esperados.

Código

Implementação guiada por SDD/BDD/TDD; PRs pequenos; integração contínua e testes automatizados.
### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  

No README do seu repositório, inclua:

minha foto do produto com lovable

<img width="1366" height="1305" alt="image" src="https://github.com/user-attachments/assets/05b9d036-17ca-417a-a7cd-6445650f5be1" />

Meu link do site: https://hanzbrito.lovable.app/

Interações com lovable

Sobre a linguagem: aqui o app é feito em HTML, CSS e JavaScript

ajuste por favor

O erro da tela em branco era de uma versão antiga carregada no navegador; recarreguei e as quatro telas (Painel, Lançamentos, Contas a pagar, Categorias) abrem sem erros.



## 💬Conclusão
Vibe Coding é sobre clareza, curiosidade e criatividade — não sobre perfeição técnica. O objetivo é aprender a pensar junto com a IA, transformando ideias em conceitos práticos e enxergando a tecnologia como extensão do seu raciocínio criativo. Cada interação é um experimento: quanto mais clara e intencional for sua comunicação, mais úteis e surpreendentes serão os resultados. Use esse processo para iterar rápido, validar hipóteses e evoluir o produto com foco em valor real para o usuário.
