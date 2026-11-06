# Documento de Requisitos — Controle Financeiro Pessoal

## 1. Identificação do projeto

**Nome:** Sistema de Controle Financeiro Pessoal  
**Disciplina:** Projeto de Software  
**Professor:** Jefferson Brandão  
**Equipe:** Rafaella Bocardi / Giovanna Amaro

## 2. Descrição do problema

Muitas pessoas possuem dificuldades para controlar suas finanças pessoais, principalmente por não registrarem adequadamente suas receitas e despesas. Essa falta de organização dificulta a identificação dos principais gastos, o acompanhamento do saldo disponível e o planejamento financeiro mensal. Como consequência, podem ocorrer gastos desnecessários, dificuldades para economizar e perda de controle sobre o orçamento pessoal.

## 3. Objetivo do projeto

Desenvolver um sistema web que permita aos usuários registrar, organizar e acompanhar suas receitas e despesas, facilitando o controle financeiro pessoal.

## 4. Usuários e stakeholders

- **Usuário final:** pessoa que utilizará o sistema para controlar suas finanças.
- **Equipe de desenvolvimento:** responsável pela criação, testes e manutenção do sistema.
- **Professor orientador:** responsável por acompanhar e avaliar o projeto.

## 5. Requisitos funcionais (RF)

Os requisitos funcionais descrevem as funcionalidades que o sistema deverá oferecer.

| Código | Descrição |
|---|---|
| RF01 | O sistema deve permitir o cadastro de usuários com nome, e-mail e senha. |
| RF02 | O sistema deve permitir que usuários realizem login e logout. |
| RF03 | O sistema deve permitir cadastrar receitas, informando descrição, valor, categoria e data. |
| RF04 | O sistema deve permitir cadastrar despesas, informando descrição, valor, categoria e data. |
| RF05 | O sistema deve permitir consultar, editar e excluir lançamentos financeiros. |
| RF06 | O sistema deve permitir classificar receitas e despesas em categorias. |
| RF07 | O sistema deve permitir filtrar movimentações por mês e ano. |
| RF08 | O sistema deve apresentar o total de receitas, despesas e saldo do período selecionado. |

## 6. Requisitos não funcionais (RNF)

Os requisitos não funcionais descrevem características de qualidade e funcionamento do sistema.

| Código | Descrição |
|---|---|
| RNF01 | O sistema deve possuir uma interface simples e intuitiva. |
| RNF02 | O sistema deve garantir que cada usuário tenha acesso somente às suas informações financeiras e armazenar senhas de forma segura. |
| RNF03 | O sistema deve possuir interface responsiva, adaptando-se a computadores, tablets e celulares. |
| RNF04 | O sistema deve armazenar os dados em um banco de dados, mantendo as informações após o encerramento da sessão. |

## 7. Escopo do projeto

### 7.1. Dentro do escopo

- Cadastro e autenticação de usuários.
- Cadastro de receitas e despesas.
- Edição e exclusão de movimentações financeiras.
- Organização dos lançamentos por categorias.
- Filtros de movimentações por período.
- Visualização do saldo e dos totais financeiros.
- Interface responsiva.

### 7.2. Fora do escopo

- Integração com contas bancárias.
- Pagamentos e transferências financeiras.
- Controle de investimentos.
- Integração automática com cartões de crédito.
- Inteligência artificial para análise de gastos.
- Aplicativo mobile nativo.

## 8. Tecnologias previstas

- **Frontend:** React.js
- **Backend:** C# com ASP.NET Core Web API
- **Banco de dados:** SQL Server
- **Versionamento:** Git e GitHub

## 9. Resultado esperado

Ao final do desenvolvimento, espera-se obter uma aplicação web funcional que permita aos usuários controlar suas receitas e despesas, consultar movimentações financeiras e acompanhar seu saldo mensal de forma organizada e segura.