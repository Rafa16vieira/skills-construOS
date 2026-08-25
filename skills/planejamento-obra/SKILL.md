---
name: planejamento-obra
description: >-
  Planejamento e controle de obra: cronograma físico-financeiro, curva S,
  caminho crítico, sequenciamento, plano de ataque e recuperação de prazo.
  Use quando o gestor falar de prazo, atraso, etapas, precedência, marco,
  desvio de avanço, "quando termina", "como recuperar o cronograma" ou
  montagem de programa de obra.
---

# Planejamento de Obra

Herda `engenheiro-civil-consultor-master` + `orquestrador-gestao-obra`: diagnóstico antes de prescrição, 3–5 perguntas, **[PREMISSA ADOTADA]**, ressalva ART no fim se houver decisão técnica embutida.

## Quando usar

Cronograma, curva S, caminho crítico, sequenciamento, plano de ataque, análise de desvio (previsto × realizado), aceleração/compressão de prazo.

## Perguntas que destravam

1. Tipo/porte da obra e etapa atual?
2. Prazo contratual / data-marco e % avanço previsto × real?
3. Já existe EAP/cronograma (MS Project, Excel, Primavera) ou partir do zero?
4. Restrições: mão de obra, fornecedor, chuva, liberação de frente, pagamento?
5. Objetivo: montar, validar, recuperar atraso ou comunicar cliente/diretoria?

## Protocolo

1. Classificar: concepção | baseline | execução | recuperação.
2. Identificar atividades no caminho crítico (não otimizar folga primeiro).
3. Separar atraso por causa: escopo, produtividade, externo, financeiro.
4. Propor no máximo 3 ações de recuperação, com impacto estimado em dias.
5. Se faltar calendário/produtividade: **[PREMISSA ADOTADA]** (ex.: dias úteis, turno único).

## Formato de saída

1. Entendimento  
2. Premissas e dados  
3. Análise (rede lógica / crítico / desvio)  
4. Resposta direta (plano ou ações)  
5. Cuidados (risco de compressão, qualidade, segurança)  
6. Próximos passos  
7. Ressalva final  

## Entregáveis típicos

- Lista de etapas com precedência e duração estimada  
- Leitura de curva S (atraso/adianto e tendência)  
- Plano de ataque por frente de serviço  
- Checklist de marcos de medição alinhados ao contrato (cruzar com `contratos-licitacoes` / `financeiro-obra`)
