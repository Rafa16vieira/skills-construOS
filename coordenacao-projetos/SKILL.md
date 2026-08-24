---
name: coordenacao-projetos
description: >-
  Coordenação e compatibilização de projetos: arquitetura × estrutura ×
  instalações, interferências, revisão de plantas, layout de canteiro e
  decisões de interface. Use quando houver conflito entre disciplinas,
  "não fecha no projeto", alteração de layout, ou alinhamento arquiteto/
  calculista/instaladores.
---

# Coordenação de Projetos

Herda diagnóstico do master/orquestrador. Não redesenha projeto executivo — organiza interfaces e decisões.

## Quando usar

Compatibilização, interferência (prumada × viga, shaft, pé-direito), revisão de planta, RFI, layout de canteiro, alinhamento arquitetura/estrutura/MEP.

## Perguntas que destravam

1. Disciplinas em conflito e versão/data dos projetos?
2. Fase: anteprojeto | executivo | obra (já executando)?
3. Sintoma: colisão geométrica, especificação, sequência, ou custo?
4. Quem decide (cliente, arquiteto, RT estrutura, gestor)?
5. Há modelo BIM / apenas PDF / croqui de campo?

## Protocolo

1. Registrar interferência: onde | quem | impacto (obra/custo/prazo).  
2. Opções A/B com prós/contras técnicos — sem inventar cotas.  
3. Encaminhar RFI objetivo ao projetista dono da disciplina.  
4. Em obra: solução de campo só com **[PREMISSA]** + validação do RT.  
5. Layout de canteiro: fluxo de material, segurança (`seguranca-epi`), vizinhos.

## Formato de saída

1–7 padrão. Incluir matriz simples: interferência | disciplina | opção | responsável.

## Cuidados

- Mudança estrutural/hidráulica → `engenheiro-civil-consultor-master`.  
- Aditivo por alteração → `contratos-licitacoes` + `orcamento-medicao`.  
- Documento de aprovação → `burocracia-documental`.
