# qa-ecommerce-shopnow
# 🧪 Projeto QA — Ecommerce ShopNow (Fictício)

Este repositório contém um **projeto fictício de testes de software**, criado com fins de **aprendizado, prática e portfólio profissional em QA**.

O objetivo é demonstrar habilidades em:
- Criação de casos de teste
- Escrita de bug reports profissionais
- Análise de severidade e prioridade
- Visão de impacto no usuário e no negócio
- Organização e documentação de testes

> ⚠️ **Observação:**  
> Este projeto é fictício. O aplicativo “ShopNow” não é real e foi utilizado apenas para simular cenários comuns de um ecommerce.

---

## 📦 Escopo do Projeto

Aplicativo mobile de ecommerce com as seguintes funcionalidades simuladas:

- Login de usuário
- Listagem de produtos
- Filtro por preço
- Carrinho de compras
- Checkout
- Pagamento via PIX

---

## ✅ Funcionalidades Testadas

- Login
- Carrinho
- Filtro de produtos
- Checkout e pagamento

---

## 🐞 Bugs Reportados

### 🔴 BUG001 — Checkout
**Título:** Ao clicar em “Finalizar Pedido”, o app retorna para Home  
**Severidade:** High  
**Prioridade:** High  

**Descrição:**  
Após concluir todas as etapas do checkout, o usuário não consegue finalizar o pedido, sendo redirecionado para a tela inicial.

---

### 🟠 BUG002 — Filtro de preço
**Título:** Filtro de preço desaparece ao clicar em “Próxima página”  
**Severidade:** Medium  
**Prioridade:** High  

**Descrição:**  
Ao navegar entre páginas, o filtro aplicado é perdido, exibindo produtos fora do critério selecionado.

---

### 🔴 BUG003 — Pagamento PIX (CRÍTICO)
**Título:** Loading infinito ao selecionar pagamento via PIX  
**Severidade:** Critical  
**Prioridade:** P0  

**Descrição:**  
Após selecionar PIX como forma de pagamento, o sistema permanece em loading infinito, bloqueando a finalização da compra.

**Impacto:**  
- Bloqueio de pagamento  
- Risco financeiro para o negócio  
- Abandono de carrinho  

---

## 🧪 Casos de Teste

| ID | Título |
|----|-------|
| TC001 | Login com credenciais válidas |
| TC002 | Login com senha inválida |
| TC003 | Adicionar produto ao carrinho |
| TC004 | Filtrar produtos por preço |
| TC005 | Finalizar pedido via PIX |

Os casos de teste estão escritos seguindo boas práticas de QA:
- Pré-condição
- Passos
- Resultado esperado

---

## 📊 Resumo QA

- Funcionalidades críticas testadas com foco em experiência do usuário
- Bug crítico identificado no fluxo de checkout via PIX
- Sistema **não recomendado para release** devido a risco financeiro

### Status da Release
❌ **Não recomendada**

---

## 📌 Recomendações

- Priorizar correção do BUG003 (PIX) — prioridade P0
- Implementar timeout e fallback no fluxo de pagamento
- Garantir persistência de filtros entre páginas
- Melhorar logs e mensagens de erro no checkout

---

## 👩‍💻 Autora

**Ana Claudia Romão**  
QA em transição de carreira | Testes Manuais | Qualidade de Software  

🔗 GitHub: https://github.com/Anaromao01
