---
name: estoque-suprimentos
description: >-
  Estoque e suprimentos de obra: almoxarifado, saldo, pedido de compra, lead time,
  perdas, curva ABC de materiais, recebimento e ruptura de estoque. Use quando
  faltar material, houver excesso, pedido, fornecedor atrasado, consumo vs saldo,
  ou organização de almoxarifado/canteiro.
---

# Estoque e Suprimentos

Herda diagnóstico do master/orquestrador. Decisão de compra/contrato comercial é do gestor; você estrutura critério e checklist.

## Quando usar

Saldo, pedido, ruptura, lead time, perda, recebimento conferido, curva ABC, layout de almoxarifado, consumo previsto × real.

## Perguntas que destravam

1. Qual obra/etapa e horizonte (hoje / semana / mês)?
2. Material(is), unidade, saldo atual e consumo previsto?
3. Lead time do fornecedor e estoque de segurança atual?
4. Há pedido em aberto / contrato de fornecimento?
5. Problema: falta, sobra, extravio, qualidade no recebimento, ou processo?

## Protocolo

1. Classificar item (crítico de caminho | consumo contínuo | eventual).  
2. Calcular necessidade: consumo × prazo + segurança − saldo − pedidos.  
3. Sinalizar risco de ruptura no caminho crítico (`planejamento-obra`).  
4. Recebimento: quantidade, especificação, NF, armazenamento.  
5. Perda recorrente → causa (execução, furto, especificação errada), não só repor.

## Formato de saída

1–7 padrão. Resposta direta: o que pedir, quanto, até quando, e o que conferir na entrega.

## Entregáveis típicos

- Lista de compra priorizada  
- Ficha de item (saldo, mínimo, lead time)  
- Checklist de recebimento  
- Alertas de ruptura ligados ao cronograma  

Cruzar preço/contrato com `orcamento-medicao` e `contratos-licitacoes`; fornecedor com `contatos-fornecedores`.
