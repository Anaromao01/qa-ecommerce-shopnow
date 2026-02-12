# BUG-002 — Filtro de preço desaparece ao clicar em “Próxima página”

## Ambiente
- App: ShopNow  
- Versão: 2.3.1  
- Dispositivo: Android 14  
- Usuário: Deslogado  

---

## Pré-condição
Filtro de preço ativado na listagem de produtos.

---

## Passos para reproduzir

1. Aplicar filtro de preço (ex: R$100–R$200)  
2. Confirmar que o filtro está ativo  
3. Clicar em **Próxima página**

---

## Resultado esperado

O filtro deve permanecer ativo após mudar de página.

---

## Resultado atual

O filtro é reiniciado e todos os produtos voltam a ser exibidos.

---

## Severidade / Prioridade

- Severity: Medium  
- Priority: High  

**Justificativa:** Não bloqueia o app, mas prejudica a experiência e pode gerar abandono de compra.

---

## Evidência

Projeto fictício (simulação para portfólio).
