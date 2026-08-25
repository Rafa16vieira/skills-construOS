---
name: orcamento-medicao
description: >-
  Orçamento e medição de obra: quantitativos, memória de cálculo, SINAPI/SICRO,
  composição, BDI, orçamento sintético/analítico e boletim de medição. Use quando
  houver levantamento de materiais/serviços, preço, BDI, "quanto custa", medição
  mensal, glosa, ou comparação de propostas.
---

# Orçamento e Medição

Herda diagnóstico do master/orquestrador. Não inventar preços de mercado sem marcar **[PREMISSA ADOTADA]** e data-base.

## Quando usar

Quantitativos, composições, BDI, SINAPI/SICRO/própria, estimativa, orçamento sintético/analítico, medição, reajuste, confronto com proposta.

## Perguntas que destravam

1. Escopo exato e nível (estimativo | sintético | analítico)?
2. Referência de preço (SINAPI, SICRO, tabela local, composição própria) e data-base?
3. BDI desejado / já contratado? Incidências (ISSQN, PIS/COFINS, risco)?
4. Há projeto/levantamento ou só descrição verbal?
5. Objetivo: orçar, medir, glosar, ou defender valor ao cliente?

## Protocolo

1. Fixar unidade e critério de medição (o que entra/sai do serviço).
2. Memória de cálculo aberta: fórmula → quantidade → perda → total.
3. Separar: material | mão de obra | equipamento | BDI | impostos (se pedido).
4. Medição: confrontar contrato × executado × evidência (RDO/fotos — `relatorios-acompanhamento`).
5. Sem tabela oficial em mãos: estimar com premissa e exigir confirmação na fonte.

## Formato de saída

1–7 padrão. Em análise: tabelas simples (serviço | und | qtd | preço | total). Em medição: período, itens, % e valor.

## Cuidados

- Perda e produtividade alteram quantitativo — declarar.  
- Não confundir custo direto com preço de venda.  
- Aditivo/escopo novo → `contratos-licitacoes`.  
- Desembolso/retenção → `financeiro-obra`.
