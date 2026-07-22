# Manual do Projeto

> **Status:** Modelo Operacional, identidade, estrutura pedagógica, níveis de autonomia e fluxo de aprovação aprovados. Os demais padrões serão complementados pelas DEC-05 a DEC-10.

## 1. Finalidade

Este documento explica como planejar, discutir, decidir, registrar, revisar, publicar e manter o Manual Completo da Plataforma ChatGPT.

A Constituição estabelece as regras obrigatórias. Este Manual explica como aplicá-las no trabalho diário.

## 2. Papéis

### GitHub

Mantém a memória permanente do projeto:

- Constituição;
- estado atual;
- decisões aprovadas;
- skills;
- roadmap;
- histórico de alterações;
- conteúdo aprovado e publicado.

### Linear

Mantém a execução do projeto:

- item atual;
- status;
- prioridades;
- dependências;
- bloqueios;
- critérios de aceitação;
- próxima etapa.

### ChatGPT

Atua como coordenador pedagógico, gerente do projeto, arquiteto de documentação e pesquisador técnico. Deve consultar GitHub e Linear, verificar sincronização e trabalhar somente no item atual.

### Conversa

Serve para discussão, estudo, escolhas e preparação de rascunhos. Uma mensagem no chat não se torna decisão oficial sem registro nas fontes do projeto.

## 3. Fluxo operacional dos chats

Antes de responder a uma solicitação relacionada ao projeto:

1. ler `docs/CONSTITUICAO_DO_PROJETO.md`;
2. ler `PROJECT_STATE.md`;
3. consultar `docs/DECISOES.md`;
4. consultar `docs/SKILLS.md` quando houver procedimento aplicável;
5. consultar `ROADMAP.md` quando a solicitação envolver sequência ou escopo;
6. consultar a issue ou projeto correspondente no Linear;
7. comparar GitHub e Linear;
8. confirmar qual é o único item em andamento;
9. responder somente dentro do escopo desse item.

Se GitHub e Linear divergirem, a resposta deve apontar a divergência e priorizar a sincronização antes de avançar.

## 4. Regra de sequência

```text
Item atual
    ↓
Discussão
    ↓
Aprovação do usuário
    ↓
Atualização dos documentos aplicáveis
    ↓
Atualização do Linear
    ↓
Verificação de sincronização
    ↓
Conclusão do item
    ↓
Liberação do próximo item
```

Não é permitido iniciar, desenvolver ou concluir uma etapa posterior antes de fechar esse ciclo.

## 5. Tratamento de ideias fora do foco

Quando surgir uma ideia relevante fora da etapa atual:

1. resumir a ideia sem aprofundá-la;
2. registrar no Backlog quando o usuário autorizar ou quando a regra de autonomia permitir;
3. manter a etapa atual como foco;
4. retomar a ideia somente quando ela se tornar o item oficial.

A criação de uma ideia no Backlog não altera o `PROJECT_STATE.md` e não inicia uma nova decisão.

## 6. Eventos e atualizações

### Decisão aprovada

Atualizar:

- `docs/DECISOES.md`;
- documento temático afetado;
- `PROJECT_STATE.md`;
- `CHANGELOG.md` quando a mudança for permanente;
- issue correspondente no Linear.

### Skill aprovada

Atualizar:

- `docs/SKILLS.md`;
- `PROJECT_STATE.md` quando alterar o fluxo ativo;
- `CHANGELOG.md` quando aplicável;
- Linear.

### Conteúdo pedagógico aprovado

Atualizar:

- arquivo da formação, módulo ou aula;
- índice correspondente;
- estado do conteúdo;
- Linear.

A publicação somente ocorre após autorização específica quando exigida pelas regras de autonomia.

### Correção editorial

Atualizar o arquivo afetado. Usar o Linear quando existir tarefa correspondente e registrar no `CHANGELOG.md` apenas alterações relevantes para rastreabilidade.

## 7. Padrão das decisões no chat

Quando uma decisão exigir escolhas:

- usar perguntas numeradas;
- apresentar até cinco alternativas identificadas por `A`, `B`, `C`, `D` e `E`;
- explicar apenas o necessário para decidir;
- colocar cada alternativa que possa ser enviada diretamente em uma caixa copiável separada;
- fornecer ao final uma caixa copiável com a resposta compacta;
- usar caixas copiáveis também para autorizações, confirmações e comandos operacionais;
- não introduzir uma nova decisão na mesma resposta.

Exemplo de alternativas:

```text
1A — Aprovar a opção A.
```

```text
1B — Aprovar a opção B.
```

Exemplo de resposta compacta:

```text
1A
2C
3B
```

Textos explicativos, relatórios e análises não precisam ficar integralmente em caixas. As caixas devem ser usadas nos trechos que o usuário provavelmente copiará e enviará como resposta ou comando.

## 8. Aplicação diária dos níveis de autonomia

### Nível 1 — Consulta Automática

Pode ser usado sem confirmação para ler, pesquisar, comparar, analisar e resumir fontes autorizadas diretamente relacionadas ao trabalho atual.

Regras práticas:

- usar somente leitura;
- limitar a consulta ao escopo necessário;
- não acessar e-mails, calendários, contatos, arquivos pessoais, outros repositórios ou serviços não relacionados sem solicitação ou autorização específica;
- tratar a documentação oficial da OpenAI como fonte primária para informações atuais da plataforma.

### Nível 2 — Preparação em Rascunho

Pode ser usado sem confirmação para preparar materiais na conversa ou em arquivos temporários de revisão.

Inclui textos, documentos, código, análises, planos, propostas, descrições de issues, mensagens, e-mails ainda não criados em sistemas externos, comandos, diffs e mensagens de commit.

Quando houver risco de confusão, o material deve ser marcado como **RASCUNHO**.

A preparação não autoriza gravação em sistemas externos.

### Nível 3 — Execução Controlada

É aplicado sempre que uma ação cria, altera, envia, publica, arquiva, exclui ou muda o estado de um sistema externo.

#### Execução Controlada Padrão

Uma solicitação direta, específica e clara pode funcionar como autorização quando a ação for privada ou interna, reversível, limitada, sem dados sensíveis, sem comunicação externa e sem alteração relevante do estado oficial.

Exemplos possíveis, conforme o contexto:

- criar um rascunho em sistema externo;
- criar issue interna;
- adicionar comentário operacional interno;
- criar branch ou arquivo em área de rascunho;
- criar evento;
- aplicar rótulo;
- arquivar mensagem.

#### Execução Controlada Crítica

Exige resumo prévio e confirmação explícita adicional quando a ação envolver publicação, envio a terceiros, commit ou merge, sobrescrita de arquivo oficial, exclusão, fechamento ou cancelamento de tarefa, alteração de roadmap, permissões, dados sensíveis, produção, execução em massa ou efeito de difícil reversão.

O resumo deve informar:

- sistema afetado;
- alvo;
- ação;
- efeito esperado;
- alcance;
- possibilidade de reversão;
- riscos relevantes.

### Escopo da autorização

Toda autorização é específica, delimitada e consumível. Ela termina quando a ação autorizada é concluída, cancelada ou quando houver mudança relevante de alvo, conteúdo, quantidade, contexto ou efeito.

Uma autorização não se estende automaticamente a ações futuras semelhantes.

### Regra de classificação

A classificação depende do contexto e do efeito real. Uma operação normalmente padrão deve ser tratada como crítica quando ocorrer em ambiente oficial ou público, envolver terceiros, dados sensíveis, produção, segurança, permissões, credenciais, impacto jurídico, financeiro ou reputacional, execução em massa ou difícil reversão.

Na dúvida razoável, classificar como crítica até que o escopo seja esclarecido.

## 9. Aplicação diária dos comandos da DEC-04

### 9.1 Reconhecimento da intenção

O projeto utiliza um modelo híbrido. Uma solicitação em linguagem natural direta, específica e inequívoca pode produzir o mesmo efeito de um comando canônico. O ChatGPT deve informar qual intenção reconheceu quando isso for relevante para a execução.

Mensagens ambíguas não devem ser tratadas como aprovação ou autorização.

Os comandos canônicos utilizam colchetes, letras maiúsculas, português do Brasil e a estrutura `AÇÃO + OBJETO`.

### 9.2 Aprovar um material

Comandos:

```text
[APROVAR CONTEÚDO]
[APROVAR DECISÃO]
[APROVAR ENTREGA]
```

Procedimento:

1. identificar a versão aprovada;
2. encerrar a revisão daquela versão;
3. registrar na conversa que a aprovação não autoriza gravação externa;
4. identificar os registros oficiais necessários;
5. preparar o resumo da execução quando o registro for necessário.

A aprovação não cria commit, não altera o Linear, não publica, não conclui e não inicia outra etapa.

### 9.3 Solicitar correções

```text
[SOLICITAR CORREÇÕES]
```

A solicitação deve indicar, quando aplicável:

- alvo;
- trecho ou aspecto afetado;
- mudança desejada;
- condições que devem ser preservadas.

O ChatGPT prepara uma nova versão e mantém o item em revisão. A nova versão não é considerada aprovada automaticamente.

### 9.4 Reabrir uma escolha

```text
[REABRIR ESCOLHA]
```

Procedimento:

1. identificar a pergunta ou escolha reaberta;
2. suspender provisoriamente somente a resposta anterior daquele ponto;
3. preservar as demais escolhas;
4. apresentar novamente o ponto necessário;
5. exigir nova resposta antes da consolidação final.

Uma decisão já concluída e registrada exige análise de impacto, proposta corretiva, autorização específica e histórico preservado.

### 9.5 Autorizar registro oficial

```text
[AUTORIZAR REGISTRO OFICIAL]
```

Antes de solicitar esse comando, apresentar:

- sistemas afetados;
- arquivos, documentos, issues ou registros atingidos;
- ações previstas;
- versão que será registrada;
- mudanças de status;
- resultado esperado;
- reversibilidade;
- riscos;
- estado esperado após a sincronização.

O comando autoriza somente o resumo imediatamente anterior ou explicitamente identificado. Depois da execução, informar alterações, commits ou evidências, estados no Linear, sincronização e falhas.

### 9.6 Autorizar publicação

```text
[AUTORIZAR PUBLICAÇÃO]
```

Antes da autorização, informar conteúdo e versão, canal, público ou destinatários, ação, alcance, momento quando aplicável, reversibilidade, riscos e evidência esperada.

A autorização não se estende a outros canais, versões, republicações, campanhas, gastos ou envios não descritos.

### 9.7 Autorizar outra execução crítica

```text
[AUTORIZAR EXECUÇÃO CRÍTICA]
```

Usar para exclusão, sobrescrita, merge, envio, alteração de permissões, dados sensíveis, operações em massa e outras ações críticas não classificadas como publicação.

Sem resumo válido, o comando solicita apenas a preparação da confirmação.

### 9.8 Validar a conclusão

```text
[CONCLUIR ETAPA]
```

Procedimento:

1. verificar a aprovação final;
2. verificar todas as escolhas e correções;
3. verificar critérios de aceitação;
4. identificar registros necessários;
5. verificar bloqueios e divergências;
6. confirmar o próximo item;
7. quando o registro estiver pendente, preparar o resumo e solicitar `[AUTORIZAR REGISTRO OFICIAL]`;
8. depois da execução, verificar GitHub, Linear, evidências e sincronização.

Somente declarar `ETAPA CONCLUÍDA` quando todas as condições forem satisfeitas. A conclusão não inicia automaticamente o próximo item.

### 9.9 Preparar a próxima decisão

```text
[INICIAR PRÓXIMA DECISÃO]
```

O comando somente poderá ser reconhecido depois da declaração `ETAPA CONCLUÍDA` da etapa anterior.

Procedimento:

1. reconstruir o contexto oficial;
2. confirmar sincronização;
3. verificar que nenhum item estrutural permanece em andamento;
4. identificar a próxima decisão obrigatória;
5. verificar dependências e bloqueios;
6. apresentar o resumo da transição;
7. solicitar nova autorização por `[AUTORIZAR REGISTRO OFICIAL]`;
8. somente depois da autorização, alterar GitHub e Linear, verificar a sincronização e apresentar a primeira pergunta da nova decisão.

O comando não ignora a sequência, não reutiliza autorização anterior e não inicia duas decisões simultaneamente.

## 10. Critério de conclusão

Uma tarefa não está concluída apenas porque foi discutida ou aprovada no chat.

Ela somente pode ser concluída quando:

- os critérios de aceitação foram atendidos;
- os arquivos aplicáveis foram atualizados;
- o Linear foi atualizado;
- GitHub e Linear indicam o mesmo estado;
- o próximo item foi confirmado.

## 11. Estrutura documental enxuta

Documentos centrais:

```text
README.md
PROJECT_STATE.md
ROADMAP.md
CHANGELOG.md

docs/
├── CONSTITUICAO_DO_PROJETO.md
├── DECISOES.md
├── SKILLS.md
└── MANUAL_DO_PROJETO.md
```

Não criar novos documentos por conveniência. Um novo documento somente deve existir quando os documentos centrais não comportarem claramente a informação e houver aprovação explícita.
