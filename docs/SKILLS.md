# Catálogo de Skills

> **Status:** esqueleto inicial. As skills serão debatidas e aprovadas em DEC-08 / LEA-111. Os comandos operacionais da DEC-04 já estão aprovados.

## Objetivo

Padronizar procedimentos repetíveis do projeto. Skills não substituem memória nem decisões oficiais; elas definem como executar tipos específicos de trabalho.

## Estrutura padrão de uma Skill

Cada skill deverá conter:

1. identificador;
2. nome;
3. finalidade;
4. gatilhos de ativação;
5. pré-condições;
6. fontes obrigatórias;
7. procedimento;
8. restrições;
9. resultado esperado;
10. comandos disponíveis ao usuário.

## Catálogo inicial proposto

- SKILL-001 — Planejar Formação
- SKILL-002 — Planejar Módulo
- SKILL-003 — Produzir Aula
- SKILL-004 — Revisar Aula
- SKILL-005 — Aprovar Conteúdo
- SKILL-006 — Publicar no GitHub
- SKILL-007 — Atualizar Linear
- SKILL-008 — Revisar Informações da OpenAI
- SKILL-009 — Fechar Módulo
- SKILL-010 — Fechar Formação

As skills acima continuam como propostas e somente poderão ser aprovadas na DEC-08.

## Comandos operacionais aprovados

A DEC-04 aprovou o modelo híbrido entre linguagem natural clara e comandos canônicos. Os comandos utilizam colchetes, letras maiúsculas, português do Brasil e a estrutura `AÇÃO + OBJETO`.

### Aprovação

- `[APROVAR CONTEÚDO]`
- `[APROVAR DECISÃO]`
- `[APROVAR ENTREGA]`

A aprovação fixa a versão aceita, mas não autoriza registro oficial, publicação, conclusão ou avanço.

### Correção e reabertura

- `[SOLICITAR CORREÇÕES]`
- `[REABRIR ESCOLHA]`

O primeiro solicita uma nova versão de material em revisão. O segundo reabre somente uma escolha da decisão atual antes do registro definitivo.

### Registro e execução

- `[AUTORIZAR REGISTRO OFICIAL]`
- `[AUTORIZAR PUBLICAÇÃO]`
- `[AUTORIZAR EXECUÇÃO CRÍTICA]`

Esses comandos somente produzem execução quando existe resumo prévio válido, com sistemas, alvos, ações, alcance, efeito, reversibilidade e riscos aplicáveis. A autorização é específica, delimitada e consumível.

### Conclusão e transição

- `[CONCLUIR ETAPA]`
- `[INICIAR PRÓXIMA DECISÃO]`

`[CONCLUIR ETAPA]` solicita a validação final e não conclui automaticamente o item. `[INICIAR PRÓXIMA DECISÃO]` prepara a transição somente após a conclusão oficial da etapa anterior e não altera sistemas sem nova autorização.

## Limitação

Um arquivo Markdown não cria botões interativos nativos na interface do ChatGPT. Os comandos funcionam como opções textuais padronizadas e, quando houver suporte de interface, poderão ser associados a controles interativos.
