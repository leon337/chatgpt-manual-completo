# Constituição do Projeto

> **Status:** base operacional, identidade, estrutura pedagógica, níveis de autonomia, fluxo de aprovação, arquitetura documental, estrutura operacional do Linear, padrão editorial e catálogo de Skills aprovados. A DEC-09 está em andamento; a DEC-10 permanece pendente.

## 1. Missão

Construir o Manual Completo da Plataforma ChatGPT em português do Brasil, organizado como curso progressivo, manual de referência e base de conhecimento viva para humanos e inteligências artificiais.

## 2. Estrutura pedagógica

```text
Manual
└── Formação
    └── Módulo
        └── Aula
```

### 2.1 Formação

Formação é o programa educacional completo dentro do Manual.

Na comunicação pública, uma Formação poderá ser chamada de curso para facilitar o entendimento do público. Nos documentos oficiais, identificadores e sistemas do projeto, o termo utilizado será sempre **Formação**.

Cada Formação contém vários Módulos.

### 2.2 Módulo

Módulo é uma unidade temática e pedagógica dentro de uma Formação. Cada Módulo reúne Aulas relacionadas a um mesmo tema ou etapa de aprendizagem.

Todo Módulo deve possuir:

- objetivo próprio;
- sequência lógica de Aulas;
- conhecimentos ou habilidades esperados ao final;
- pré-requisitos, quando necessários.

O Módulo faz parte da progressão da Formação e não cria um novo nível estrutural.

### 2.3 Aula

Aula é a menor unidade pedagógica oficial da estrutura do Manual.

Cada Aula pertence a um único Módulo e desenvolve um objetivo de aprendizagem específico ou um conjunto pequeno e coerente de objetivos relacionados.

A Aula pode conter explicações, exemplos, demonstrações, atividades e verificações de aprendizagem. O padrão editorial detalhado foi aprovado na DEC-07 e está registrado em `docs/DECISOES.md`.

A conclusão das Aulas contribui para o cumprimento dos objetivos do Módulo.

### 2.4 Progressão pedagógica

A progressão oficial será sequencial. Cada Formação possuirá uma ordem definida de Módulos, e cada Módulo possuirá uma ordem definida de Aulas.

O estudante deverá seguir essa sequência para completar oficialmente a Formação, especialmente quando houver pré-requisitos.

Como o Manual também funciona como material de referência, uma Aula ou um Módulo poderá ser consultado isoladamente, mas essa consulta não equivale à conclusão da progressão pedagógica.

### 2.5 Identificação oficial

A identificação será numérica e hierárquica:

```text
Formação: F01, F02, F03...
Módulo:   M01, M02, M03... dentro de cada Formação
Aula:     A01, A02, A03... dentro de cada Módulo

Identificador completo:
F01-M02-A03
```

O título será separado do identificador.

Exemplo:

```text
F01-M02-A03 — Criando seu primeiro Projeto no ChatGPT
```

### 2.6 Expansão futura

Antes da aprovação, elementos em rascunho poderão ser reorganizados e renumerados.

Depois da aprovação ou publicação:

- o identificador não poderá ser reutilizado;
- o identificador não deverá ser alterado;
- novos elementos receberão o próximo número disponível dentro do elemento superior;
- a posição pedagógica será controlada separadamente pela ordem oficial.

Assim, um novo elemento poderá ser inserido na progressão sem renumerar identificadores existentes.

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

## 8. Níveis de autonomia das ferramentas

### 8.1 Nível 1 — Consulta Automática

A ferramenta pode consultar, pesquisar, ler, comparar, analisar e resumir fontes autorizadas sem solicitar confirmação, desde que não altere sistemas, arquivos, registros ou estados.

As consultas automáticas serão permitidas somente em fontes autorizadas e diretamente relacionadas à solicitação atual:

- documentos oficiais do repositório do projeto;
- issues, projetos e documentos correspondentes no Linear;
- documentação oficial da OpenAI;
- arquivos fornecidos pelo usuário ou vinculados ao projeto;
- outras fontes autorizadas pelas instruções ou pela solicitação atual.

A consulta deve usar somente o escopo necessário. E-mails, calendários, contatos, arquivos pessoais, outros repositórios e serviços não relacionados somente poderão ser consultados quando o usuário solicitar ou quando existir autorização específica aplicável.

Toda ação do Nível 1 permanece exclusivamente de leitura.
