# Manual do Projeto

> **Status:** Modelo Operacional, identidade, estrutura pedagógica e níveis de autonomia aprovados. Os demais padrões serão complementados pelas DEC-04 a DEC-10.

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

Os comandos e formatos exatos de aprovação serão definidos na DEC-04.

## 9. Critério de conclusão

Uma tarefa não está concluída apenas porque foi discutida ou aprovada no chat.

Ela somente pode ser concluída quando:

- os critérios de aceitação foram atendidos;
- os arquivos aplicáveis foram atualizados;
- o Linear foi atualizado;
- GitHub e Linear indicam o mesmo estado;
- o próximo item foi confirmado.

## 10. Estrutura documental enxuta

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
