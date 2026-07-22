# Manual do Projeto

> **Status:** Modelo Operacional aprovado e em implantação pela LEA-115. Os demais padrões serão complementados pelas DEC-01 a DEC-10.

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
- fornecer uma caixa copiável com o formato de resposta;
- não introduzir uma nova decisão na mesma resposta.

Exemplo:

```text
1A
2C
3B
```

## 8. Critério de conclusão

Uma tarefa não está concluída apenas porque foi discutida ou aprovada no chat.

Ela somente pode ser concluída quando:

- os critérios de aceitação foram atendidos;
- os arquivos aplicáveis foram atualizados;
- o Linear foi atualizado;
- GitHub e Linear indicam o mesmo estado;
- o próximo item foi confirmado.

## 9. Estrutura documental enxuta

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