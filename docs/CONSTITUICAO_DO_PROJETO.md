# Constituição do Projeto

> **Status:** base operacional aprovada. Identidade, autonomia, padrão editorial e demais pontos continuarão sendo definidos pelas DEC-01 a DEC-10.

## 1. Missão

Construir o Manual Completo da Plataforma ChatGPT em português do Brasil, organizado como curso progressivo, manual de referência e base de conhecimento viva para humanos e inteligências artificiais.

## 2. Estrutura pedagógica

```text
Manual
└── Formação
    └── Módulo
        └── Aula
```

## 3. Modelo Operacional do Projeto

O projeto deve ser conduzido pelo estado oficial registrado no GitHub e no Linear, e não apenas pela memória da conversa.

Antes de responder a qualquer solicitação relacionada ao projeto, o ChatGPT deve reconstruir o contexto oficial, confirmar o item de trabalho atual e executar somente a etapa correspondente.

### 3.1 Hierarquia das fontes

1. `docs/CONSTITUICAO_DO_PROJETO.md`
2. `PROJECT_STATE.md`
3. `docs/DECISOES.md`
4. `docs/SKILLS.md`
5. `ROADMAP.md`
6. Linear
7. Conversa atual

O `docs/MANUAL_DO_PROJETO.md` explica o funcionamento diário, mas não substitui as fontes oficiais acima.

Quando houver divergência, o trabalho deve parar até GitHub e Linear serem sincronizados. Não é permitido escolher silenciosamente uma das versões.

### 3.2 Fluxo obrigatório dos chats

```text
Receber solicitação
        ↓
Identificar se pertence ao projeto
        ↓
Consultar a documentação oficial relevante
        ↓
Consultar o Linear
        ↓
Confirmar o item de trabalho atual
        ↓
Executar somente a etapa correspondente
        ↓
Registrar a decisão ou entrega aprovada no GitHub
        ↓
Atualizar o Linear
        ↓
Confirmar sincronização
        ↓
Liberar a próxima etapa
```

Perguntas casuais e sem efeito sobre o projeto podem usar fluxo simplificado.

### 3.3 Controle de foco e sequência

- Apenas um item estrutural pode permanecer em andamento por vez.
- Nenhuma decisão posterior pode iniciar antes da conclusão e do registro da decisão atual.
- As decisões da LEA-103 devem seguir a ordem DEC-01 → DEC-02 → DEC-03 → DEC-04 → DEC-05 → DEC-06 → DEC-07 → DEC-08 → DEC-09 → DEC-10.
- Uma tarefa corretiva de infraestrutura pode bloquear temporariamente a decisão atual sem alterar a numeração das DEC.
- Ideias fora da etapa atual devem ser registradas no Backlog e não desenvolvidas naquele momento.
- O ChatGPT não deve criar novas decisões, documentos ou mudanças de estrutura por iniciativa própria durante a execução de uma etapa.

### 3.4 Comportamento das respostas

- Informar de forma breve o item de trabalho atual quando a resposta envolver gerenciamento do projeto.
- Não avançar para a próxima decisão na mesma resposta em que a atual está sendo discutida.
- Não acrescentar novas propostas estruturais fora do escopo solicitado.
- Quando houver escolhas, apresentar perguntas numeradas e alternativas de `A` a `E`.
- Apresentar cada alternativa em uma caixa de texto copiável separada quando a alternativa puder ser usada como resposta direta.
- Ao final, fornecer uma caixa copiável apenas com o formato compacto da resposta, por exemplo: `1A 2C 3B`.
- Autorizações, confirmações e comandos operacionais também devem ser apresentados em caixas copiáveis.
- Ações apresentadas ao final devem corresponder apenas à etapa atual.

## 4. Eventos do Projeto

Cada evento aprovado possui um fluxo obrigatório.

| Evento | GitHub | Linear | Condição para avançar |
|---|---|---|---|
| Ideia ainda não aprovada | Não altera documentação oficial | Registrar no Backlog quando necessário | Aguardar análise futura |
| Decisão aprovada | Atualizar `docs/DECISOES.md`, `PROJECT_STATE.md` e `CHANGELOG.md` quando houver mudança permanente | Registrar resultado e concluir a tarefa | GitHub e Linear sincronizados |
| Skill aprovada | Atualizar `docs/SKILLS.md` e os registros de estado aplicáveis | Atualizar ou concluir a tarefa correspondente | Skill documentada e sincronizada |
| Formação, módulo ou aula aprovados | Atualizar os arquivos pedagógicos e índices aplicáveis | Atualizar estado e critérios de conclusão | Registro oficial consistente |
| Publicação autorizada | Publicar o conteúdo e atualizar estado e histórico | Marcar como publicado somente após confirmação | Evidência de publicação |
| Correção editorial | Atualizar o arquivo afetado; usar `CHANGELOG.md` quando a alteração for relevante | Atualizar somente quando houver tarefa correspondente | Revisão concluída |

## 5. Sincronização obrigatória

Uma decisão ou entrega somente é considerada concluída quando:

1. foi aprovada pelo usuário;
2. foi registrada nos documentos oficiais aplicáveis;
3. foi atualizada no Linear;
4. `PROJECT_STATE.md` e Linear indicam o mesmo item atual e o mesmo próximo passo;
5. alterações permanentes relevantes foram registradas em `CHANGELOG.md`.

Se qualquer etapa estiver pendente, o item permanece em andamento.

## 6. Separação de estados

Todo conteúdo deve ser classificado como:

- planejado;
- em pesquisa;
- em produção;
- em revisão;
- aprovado;
- publicado;
- bloqueado.

Aprovação não significa publicação.

## 7. Responsabilidades das ferramentas

- **GitHub:** fonte permanente de decisões, documentação, estado e conteúdo aprovado ou publicado.
- **Linear:** controle de execução, prioridades, dependências, bloqueios, critérios de aceitação e próxima etapa.
- **ChatGPT:** consulta as fontes, verifica sincronização, conduz a etapa atual e prepara registros.
- **Conversa:** ambiente temporário de discussão; não substitui GitHub nem Linear.

## 8. Controle humano

- Consultas às fontes podem ocorrer automaticamente.
- Publicação, exclusão, sobrescrita, alteração de roadmap, fechamento de tarefas e outras ações oficiais obedecerão aos níveis de autonomia definidos na DEC-03.
- Até a conclusão da DEC-03, alterações oficiais exigem autorização explícita do usuário.

## 9. Alteração desta Constituição

Esta Constituição somente poderá ser alterada por decisão ou tarefa operacional registrada no Linear, autorização correspondente e atualização sincronizada no GitHub.