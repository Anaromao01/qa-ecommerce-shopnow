# BUG-001 — Checkout retorna para Home ao finalizar pedido

## Ambiente
- App: ShopNow  
- Versão: 2.3.1  
- Dispositivo: Android 14  
- Usuário: Logado  

---

## Pré-condição
Usuário deve estar logado e com produto no carrinho.

---

## Passos para reproduzir

1. Estar logado no aplicativo  
2. Adicionar um produto ao carrinho  
3. Inserir endereço válido  
4. Inserir forma de pagamento válida  
5. Clicar em **Finalizar Pedido**

---

## Resultado esperado

O sistema deve concluir o pedido e exibir a mensagem:

✅ “Pedido concluído com sucesso” + comprovante.

---

## Resultado atual

Ao clicar em **Finalizar Pedido**, o app retorna para a Home sem concluir o pedido.

---

## Severidade / Prioridade

- Severity: High  
- Priority: High  

**Justificativa:** Bug bloqueia o fluxo principal de compra e pode gerar abandono de carrinho.

---

## Evidência

Projeto fictício (simulação para portfólio).
