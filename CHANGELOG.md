# Changelog

Todas as alterações permanentes relevantes do projeto devem ser registradas neste arquivo.

## 2026-07-24

### Adicionado

- Aprovação integral da DEC-08 — Catálogo de Skills do projeto, com escolhas 1A a 27A.
- Conceito oficial de Skill, limites de autoridade, estrutura obrigatória, ativação, fontes, procedimento, validação, ciclo de vida e critérios de criação.
- Catálogo inicial aprovado com nove Skills.
- Separação formal entre Skill, decisão, memória, comando, ferramenta e autorização.
- Regras de identificação global no padrão `SKILL-001`, versionamento `MAJOR.MINOR.PATCH`, suspensão, descontinuação e substituição.
- Regras de falha controlada, preservação de evidências e retomada segura.

### Alterado

- `docs/SKILLS.md` passou a registrar a definição oficial e o catálogo aprovado da DEC-08.
- `PROJECT_STATE.md` passou a indicar a DEC-08 como aprovada pelo usuário, com registro oficial e sincronização ainda em andamento.
- A proposta `Aprovar Conteúdo` foi removida do catálogo por representar decisão humana e comando, não autoridade autônoma de Skill.
- As propostas `Revisar Informações da OpenAI`, `Fechar Módulo` e `Fechar Formação` foram renomeadas para `Verificar Informações da OpenAI`, `Validar Conclusão de Módulo` e `Validar Conclusão de Formação`.
- O catálogo foi renumerado antes do registro definitivo, resultando em nove identificadores contínuos.

### Em andamento

- Registro integral da DEC-08 em `docs/DECISOES.md`.
- Atualização da LEA-111 com decisões, critérios e evidências.
- Verificação final da sincronização entre GitHub e Linear.

### Preservado

- A LEA-111 / DEC-08 permanece como único item estrutural em andamento.
- A LEA-112 / DEC-09 permanece no Backlog e não foi iniciada.
- As Skills aprovadas ainda não estão ativas até a conclusão do registro e da sincronização.
- Nenhum conteúdo pedagógico foi iniciado.
- Nenhuma Formação, Módulo, Aula, Milestone pedagógica, Issue pedagógica ou Sub-issue pedagógica foi criada.
- Nenhuma publicação externa de conteúdo pedagógico foi realizada.

## 2026-07-23

### Adicionado

- Registro oficial da aprovação da DEC-07 — Padrão editorial das aulas.
- Núcleo editorial obrigatório de oito seções para toda Aula.
- Catálogo controlado de seções opcionais e regras de inserção contextual.
- Regras de tamanho flexível e critérios pedagógicos para dividir uma Aula.
- Padrão de explicações progressivas, analogias limitadas e exemplos classificados.
- Verificação obrigatória de aprendizagem alinhada ao objetivo, com gabarito, checklist ou rubrica.
- Hierarquia de fontes, citações proporcionais e seção obrigatória `Fontes e atualização`.
- Revisão obrigatória em camadas, classificação de achados e bloqueios para falhas críticas ou maiores.
- Controle editorial com datas ISO 8601, versionamento `MAJOR.MINOR.PATCH`, periodicidade de revisão e gatilhos extraordinários.

### Alterado

- `docs/DECISOES.md` passou a registrar integralmente as escolhas 1A a 9A e a conclusão da DEC-07.
- `PROJECT_STATE.md` passou a indicar a LEA-111 / DEC-08 como único item estrutural em andamento e a LEA-112 / DEC-09 como próxima decisão.
- `ROADMAP.md` passou a marcar a DEC-08 como em andamento e a DEC-09 como próxima decisão.
- `README.md` passou a registrar a DEC-08 como decisão em andamento e a preservar o catálogo de Skills como provisório.
- `docs/SKILLS.md` passou a registrar o estado inicial da DEC-08 e a declarar explicitamente que nenhuma Skill foi aprovada pelo início da decisão.
- `docs/MANUAL_DO_PROJETO.md` passou a explicar a aplicação diária do padrão editorial das Aulas.
- A LEA-110 passou a registrar a aprovação, as evidências, a sincronização e a conclusão formal da DEC-07.
- A LEA-103 passou a indicar a DEC-08 como única decisão estrutural em andamento e a DEC-09 como próxima.

### Corrigido

- Referências residuais que ainda tratavam o padrão editorial da DEC-07 como definição futura foram identificadas para alinhamento com o estado concluído da decisão.

### Iniciado

- LEA-111 — DEC-08: Projetar catálogo de Skills do projeto.
- Sincronização do estado inicial da DEC-08 entre GitHub e Linear.
- Definição inicial do escopo da DEC-08: conceito, limites, estrutura mínima, gatilhos, pré-condições, fontes, procedimentos, restrições, resultados e catálogo de Skills.

### Concluído

- LEA-110 — DEC-07: Definir padrão editorial das aulas.
- Validação formal da conclusão da DEC-07 por `[CONCLUIR ETAPA]`.
- Sincronização final da DEC-07 entre GitHub e Linear.

### Preservado

- A LEA-111 / DEC-08 é o único item estrutural em andamento.
- A LEA-112 / DEC-09 permanece no Backlog como próxima decisão e não foi iniciada.
- Nenhuma Skill foi aprovada durante a transição.
- Nenhum conteúdo pedagógico foi iniciado.
- Nenhuma Formação, Módulo, Aula, Milestone pedagógica, Issue pedagógica ou Sub-issue pedagógica foi criada.
- Os diretórios `curriculum/`, `content/`, `research/` e `assets/` permanecem apenas planejados e não foram criados.
- Nenhum placeholder, arquivo vazio ou publicação externa foi criado.
- A sequência DEC-01 a DEC-10 permanece inalterada.
- A LEA-114 permanece no Backlog e bloqueada pela conclusão da LEA-103.

## 2026-07-22

### Adicionado

- Registro oficial da DEC-01 — Identidade e visão do projeto.
- Registro oficial da DEC-02 — Estrutura pedagógica oficial.
- Registro oficial da DEC-03 — Níveis de autonomia das ferramentas.
- Registro oficial da DEC-04 — Fluxo e comandos de aprovação.
- Registro oficial da DEC-05 — Estrutura e responsabilidades do GitHub.
- Registro oficial da DEC-06 — Estrutura operacional do Linear.
- Registro inicial da DEC-07 — Padrão editorial das aulas, como decisão em desenvolvimento e sem escolhas aprovadas.
- Aviso de licenciamento do conteúdo sob CC BY-SA 4.0.
- Aviso de licenciamento dos exemplos de código e componentes de software sob MIT License.
- Política oficial de atribuição do conteúdo e titularidade do código.
- Definições oficiais de Formação, Módulo e Aula.
- Regras oficiais de progressão pedagógica, identificação hierárquica e estabilidade dos identificadores.
- Três níveis oficiais de autonomia: Consulta Automática, Preparação em Rascunho e Execução Controlada.
- Categorias internas Padrão e Crítica para o Nível 3.
- Regras de validade, consumo e delimitação das autorizações.
- Regra de classificação pelo contexto e efeito real da execução.
- Confirmação proporcional ao risco para ações externas.
- Modelo híbrido entre linguagem natural e comandos canônicos.
- Catálogo oficial de comandos da DEC-04.
- Separação formal entre aprovação, registro, publicação, conclusão e avanço.
- Fluxos específicos para correção, reabertura de escolha, registro oficial, publicação, execução crítica, conclusão e transição.
- Estrutura documental mínima e progressiva do repositório.
- Matriz oficial de responsabilidades dos arquivos da raiz e de `docs/`.
- Reserva conceitual dos diretórios futuros `curriculum/`, `content/`, `research/` e `assets/`.
- Definição futura de `curriculum/CURRICULUM.md` como fonte da arquitetura pedagógica global.
- Critérios de necessidade, responsabilidade, localização, conteúdo mínimo útil e autorização para novos arquivos e diretórios.
- Regras de movimentação, renomeação, substituição, arquivamento e remoção com análise de impacto.
- Matriz de fontes canônicas, resumos referenciais e atualização coordenada.
- Correspondência operacional Manual = Project, Formação = Milestone, Módulo = Issue e Aula = Sub-issue.
- Regras de criação progressiva, estados, prioridades, relações, critérios de conclusão, evidências e controle de volume no Linear.
- Separação canônica entre conteúdo pedagógico no GitHub e execução operacional no Linear.

### Alterado

- `README.md` passou a registrar a LEA-110 / DEC-07 como único item estrutural em andamento e a DEC-08 como próxima decisão.
- `PROJECT_STATE.md` passou a registrar a LEA-110 / DEC-07 como único item estrutural em andamento.
- `docs/DECISOES.md` passou a registrar a DEC-07 como decisão em desenvolvimento, sem escolhas editoriais aprovadas.
- `ROADMAP.md` passou a marcar a DEC-07 como em andamento e a DEC-08 como próxima decisão após sua conclusão.
- A descrição da LEA-103 passou a indicar a DEC-07 como em andamento e a DEC-08 como próxima decisão.
- A descrição da LEA-110 passou a registrar objetivo, escopo, regras herdadas, critérios de aceitação e estado inicial da DEC-07.
- `docs/DECISOES.md` passou a registrar integralmente as escolhas 1A a 9A da DEC-06.
- `docs/MANUAL_DO_PROJETO.md` passou a explicar a aplicação diária da estrutura operacional do Linear.
- A descrição da LEA-109 passou a registrar o resultado aprovado e os critérios atendidos da DEC-06.

### Iniciado

- LEA-106 — DEC-03: Definir níveis de autonomia das ferramentas.
- Sincronização do estado inicial da DEC-03 entre GitHub e Linear.
- LEA-107 — DEC-04: Definir fluxo e comandos de aprovação.
- Sincronização do estado inicial da DEC-04 entre GitHub e Linear.
- LEA-108 — DEC-05: Definir estrutura e responsabilidades do GitHub.
- Sincronização do estado inicial da DEC-05 entre GitHub e Linear.
- LEA-109 — DEC-06: Definir estrutura operacional do Linear.
- Sincronização do estado inicial da DEC-06 entre GitHub e Linear.
- LEA-110 — DEC-07: Definir padrão editorial das aulas.
- Sincronização do estado inicial da DEC-07 entre GitHub e Linear.

### Concluído

- LEA-104 — DEC-01: Definir identidade e visão do projeto.
- LEA-105 — DEC-02: Confirmar estrutura pedagógica oficial.
- LEA-106 — DEC-03: Definir níveis de autonomia das ferramentas.
- LEA-107 — DEC-04: Definir fluxo e comandos de aprovação.
- LEA-108 — DEC-05: Definir estrutura e responsabilidades do GitHub.
- LEA-109 — DEC-06: Definir estrutura operacional do Linear.
- Sincronização da conclusão da DEC-01 entre GitHub e Linear.
- Sincronização da conclusão da DEC-02 entre GitHub e Linear.
- Sincronização da conclusão da DEC-03 entre GitHub e Linear.
- Sincronização da conclusão da DEC-04 entre GitHub e Linear.
- Sincronização da conclusão da DEC-05 entre GitHub e Linear.
- Sincronização da conclusão da DEC-06 entre GitHub e Linear.

### Preservado

- A LEA-103 permanece em andamento porque DEC-07 a DEC-10 continuam pendentes.
- A LEA-110 / DEC-07 é o único item estrutural em andamento.
- A LEA-111 / DEC-08 permanece no Backlog e não foi iniciada.
- Nenhuma escolha editorial da DEC-07 foi aprovada.
- Nenhum conteúdo pedagógico foi iniciado durante a transição.
- Nenhuma Milestone de Formação, Issue de Módulo, Sub-issue de Aula, label ou estado novo foi criado durante o registro da DEC-06.
- Os diretórios `curriculum/`, `content/`, `research/` e `assets/` permanecem apenas planejados e não foram criados.
- Nenhum diretório `published/`, placeholder ou arquivo vazio foi criado.
- A sequência DEC-01 a DEC-10 permanece inalterada.
- A LEA-114 permanece no Backlog e bloqueada pela conclusão da LEA-103.
- Nenhuma publicação externa foi realizada.

## 2026-07-21

### Adicionado

- LEA-115 — Implementar o Modelo Operacional do Projeto.
- Hierarquia oficial das fontes do projeto.
- Fluxo obrigatório dos chats.
- Regra de um único item estrutural em andamento.
- Eventos do projeto e seus fluxos de atualização.
- Processo obrigatório de sincronização entre GitHub e Linear.
- Critérios objetivos para avançar de etapa.
- `docs/DECISOES.md`.
- Mapa oficial entre DEC-01 a DEC-10 e LEA-104 a LEA-113.
- Regra permanente de caixas copiáveis para alternativas, autorizações, confirmações e comandos operacionais.

### Alterado

- `docs/CONSTITUICAO_DO_PROJETO.md` passou a conter o Modelo Operacional do Projeto e o padrão detalhado de caixas copiáveis.
- `docs/MANUAL_DO_PROJETO.md` passou a explicar o fluxo diário, eventos, critérios de conclusão e uso das caixas copiáveis.
- `docs/DECISOES.md` passou a registrar o mapa oficial da LEA-103.
- `PROJECT_STATE.md` foi sincronizado com a conclusão da LEA-115 e o início da DEC-01.
- A instrução definitiva foi aplicada nas configurações do Projeto ChatGPT.
- LEA-104 / DEC-01 foi liberada como único item estrutural em andamento.
- A descrição da LEA-103 foi reorganizada como índice mestre das decisões.
- A LEA-115 foi esclarecida como tarefa corretiva concluída, fora da numeração DEC-01 a DEC-10.
- O título da LEA-114 foi corrigido de `DEC-11 — Definir o Universo Didático Permanente` para `Definir o Universo Didático Permanente`.
- `ROADMAP.md` passou a registrar explicitamente a LEA-114 como etapa posterior à LEA-103 e anterior ao planejamento da Formação Iniciante.
- A nomenclatura da Fase 0 no roadmap foi ajustada para `Decisões estruturais`.
- `PROJECT_STATE.md` passou a registrar a sincronização posterior à terceira auditoria independente.
- A referência interna da LEA-114 na descrição da LEA-103 foi atualizada para o endereço atual da issue.

### Concluído

- LEA-115 — Modelo Operacional do Projeto implantado e sincronizado entre GitHub, Linear e instruções do Projeto ChatGPT.
- Correção das inconsistências residuais identificadas no segundo teste de reconstrução do contexto.
- Correção das inconsistências residuais identificadas no terceiro teste independente.

### Preservado

- A sequência DEC-01 a DEC-10 não foi renumerada.
- A correspondência oficial permanece DEC-01/LEA-104 até DEC-10/LEA-113.
- A LEA-114 — Universo Didático permanece no Backlog e será retomada somente após a conclusão da LEA-103.