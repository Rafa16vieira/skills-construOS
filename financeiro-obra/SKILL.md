---
name: financeiro-obra
description: >-
  Financeiro de obra: fluxo de caixa, desembolso, recebíveis, retenções, curva
  de desembolso, adiantamentos e conciliação medição×pagamento. Use quando
  houver "não tem caixa", retenção contratual, previsão de desembolso, atraso de
  recebimento ou alinhamento medição/pagamento.
---

# Financeiro de Obra

Herda diagnóstico do master/orquestrador. Não é contabilidade fiscal completa — foco em caixa e contrato da obra.

## Quando usar

Fluxo de caixa, desembolso, recebimento, retenção, adiantamento, previsão mensal, conciliação medição × NF × pagamento.

## Perguntas que destravam

1. Horizonte (semana / mês / até o fim) e regime (empreitada, admin.)?
2. Saldo de caixa da obra (ou da empresa) e compromissos já assumidos?
3. Cronograma de medições/recebíveis e retenções (% e liberação)?
4. Despesas críticas à frente (folha, concreto, fornecedor)?
5. Objetivo: prever, cortar, negociar prazo, ou explicar furo de caixa?

## Protocolo

1. Separar: custo incorrido | compromisso | desembolso | recebível.  
2. Montar visão por período: entradas − saídas = saldo projetado.  
3. Amarrar medição (`orcamento-medicao`) ao contrato (`contratos-licitacoes`).  
4. Ruptura de caixa que para obra → alertar `planejamento-obra` + `estoque-suprimentos`.  
5. Sem números: pedir ou marcar **[PREMISSA ADOTADA]** com cenários (base / pessimista).

## Formato de saída

1–7 padrão. Preferir tabela por mês/semana: item | tipo | valor | data | status.

## Cuidados

- Não confundir lucro contábil com caixa.  
- Impostos/BDI detalhados → complementar com `orcamento-medicao`.  
- Decisão de priorizar pagamento é do gestor; você expõe impacto.
