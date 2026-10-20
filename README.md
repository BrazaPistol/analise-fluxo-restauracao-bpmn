Modelagem BPMN(Business Process Model and Notation ou Modelo e Notação de Processos de Negócios): Fluxo de Solicitação e Restauração de Dados.

---------------------------------------------------------------------------------------------------------
# Modelagem BPMN — Fluxo de Solicitação e Restauração de Dados!

## DESCRIÇÃO
Projeto de modelagem e análise de processo baseado em experiência
real de suporte de TI, documentando o fluxo de solicitação,
restauração e validação de dados a partir de backups.

## PROCESSO AS-IS (atual)
![Fluxo atual](diagramas/fluxo-atual.png)
- Ator principal: Suporte de TI
- Ator secundário: Usuário solicitante
- Pontos de decisão: existência do dado no backup; validação

## GARGALOS 
1. Falta de padronização na abertura do chamado
2. Ausência de verificação prévia da janela de backup
3. Validação informal com o usuário
4. Causa raiz não registrada

## PROCESSO TO-BE (proposto)
![Fluxo proposto](diagramas/fluxo-proposto.png)
- Formulário padronizado de solicitação
- Checklist de validação com o usuário
- Registro obrigatório de causa raiz

## MÉTRICAS SUGERIDAS
- Tempo médio de restauração (SLA)
- % de restaurações validadas na primeira tentativa
- % de chamados sem causa raiz registrada

## Ferramentas
- BPMN 2.0 — draw.io (diagrams.net)

## Aprendizados
Valorização aos detalhes de uma tarefa cotidiana, por mais que seja um processo antigo, novas variáveis sempre encontram jeito de serem descobertas.
