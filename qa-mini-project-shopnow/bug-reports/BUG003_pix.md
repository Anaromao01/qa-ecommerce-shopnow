# BUG-003 — Loading infinito ao selecionar pagamento via PIX

## Ambiente
- App: ShopNow  
- Versão: 2.3.1  
- Dispositivo: Android 14  
- Usuário: Logado  

---

## Pré-condição

- Usuário logado  
- Usuário sem cartão cadastrado  
- Produto adicionado ao carrinho  

---

## Passos para reproduzir

1. Acessar o app com perfil logado  
2. Adicionar um produto ao carrinho  
3. Inserir endereço válido  
4. Selecionar pagamento via **PIX**  
5. Confirmar a forma de pagamento

---

## Resultado esperado

O app deve exibir:

✅ QR Code PIX  
✅ Código para copiar e pagar

---

## Resultado atual

O app permanece em loading infinito, impedindo o pagamento.

---

## Severidade / Prioridade

- Severity: Critical  
- Priority: High (P0)

**Justificativa:** Bloqueia pagamento via PIX, causando perda de receita e abandono de compra.

---

## Evidência

Projeto fictício (simulação para portfólio).
