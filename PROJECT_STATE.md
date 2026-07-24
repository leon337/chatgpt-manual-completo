# Estado do Projeto

## Situação

- **Projeto:** Manual Completo da Plataforma ChatGPT
- **Fase:** decisões estruturais da LEA-103
- **Status geral:** em produção
- **Conteúdo didático:** ainda não iniciado
- **Repositório:** identidade, licenciamento, estrutura pedagógica, níveis de autonomia, fluxo de aprovação, arquitetura documental, estrutura operacional do Linear, padrão editorial das Aulas e catálogo oficial de Skills registrados
- **Linear:** LEA-104 a LEA-111 concluídas; LEA-112 em andamento

## Estrutura pedagógica aprovada

```text
Manual
└── Formação
    └── Módulo
        └── Aula
```

## Estrutura operacional do Linear aprovada

```text
Manual = Project
Formação = Milestone
Módulo = Issue
Aula = Sub-issue
```

- GitHub mantém o conteúdo canônico e a memória permanente.
- Linear mantém execução, estados, prioridades, dependências, bloqueios, critérios de aceitação e evidências.
- A criação de Milestones, Issues e Sub-issues será progressiva e dependerá de necessidade concreta e autorização aplicável.

## Estado estrutural oficial

- **Último item concluído:** LEA-111 — DEC-08: Projetar catálogo de Skills do projeto
- **Item estrutural em andamento:** LEA-112 — DEC-09: Redigir instrução definitiva do Projeto ChatGPT
- **Status:** In Progress
- **Objetivo atual:** definir, redigir, revisar e aprovar a instrução definitiva do Projeto ChatGPT, consolidando as decisões estruturais já aprovadas sem conflitos
- **Próximo item após a conclusão:** LEA-113 — DEC-10: Revisar e aprovar a governança inicial

## Resultado da DEC-01

A identidade e a visão do projeto foram aprovadas com nome público, relação com a PredixAI Academy, públicos, idioma, posicionamento, licenciamento e atribuição definidos.

## Resultado da DEC-02

A estrutura pedagógica oficial foi aprovada como Manual → Formação → Módulo → Aula, com progressão sequencial, identificação hierárquica e estabilidade dos identificadores.

## Resultado da DEC-03

Os níveis de autonomia foram aprovados como Consulta Automática, Preparação em Rascunho e Execução Controlada, com classificação proporcional ao risco e autorizações específicas.

## Resultado da DEC-04

O fluxo e os comandos de aprovação foram aprovados, separando aprovação, correção, registro, publicação, conclusão e transição.

## Resultado da DEC-05

A arquitetura documental do GitHub foi aprovada com estrutura mínima, responsabilidades exclusivas, diretórios futuros reservados, ciclo de vida documental e matriz de fontes canônicas.

Nenhum diretório futuro, placeholder ou arquivo adicional foi criado durante o registro da DEC-05.

## Resultado da DEC-06

A estrutura operacional do Linear foi aprovada com as escolhas 1A a 9A:

- um único Project representa o Manual;
- cada Formação em planejamento ou produção poderá receber uma Milestone;
- cada Módulo será uma Issue;
- cada Aula será uma Sub-issue;
- tarefas operacionais pequenas permanecerão em checklists e somente terão Issue própria quando houver entrega independente e rastreabilidade necessária;
- os estados operacionais serão Backlog, Todo, In Progress e Done, com Canceled e Duplicate para usos excepcionais;
- situação pedagógica e estado operacional permanecerão separados;
- prioridades representarão urgência, impacto e bloqueio, não ordem pedagógica;
- relações distinguirão hierarquia, bloqueio obrigatório, vínculo contextual e duplicidade;
- critérios de conclusão serão próprios para Aula, Módulo, Formação, Manual e tarefa operacional;
- GitHub será a fonte canônica do conteúdo e Linear o controle de execução;
- a criação de registros será progressiva, precedida por verificação de duplicidade e acompanhada de revisão periódica.

Nenhuma Milestone de Formação, Issue de Módulo, Sub-issue de Aula, label ou estado novo foi criada durante o registro da DEC-06.

## Resultado da DEC-07

A DEC-07 foi aprovada, registrada, concluída e sincronizada com as escolhas 1A a 9A. O padrão editorial oficial das Aulas estabelece:

- núcleo obrigatório com identificação, objetivo, pré-requisitos, introdução, desenvolvimento, síntese, verificação e fontes;
- catálogo controlado de seções opcionais;
- ordem editorial principal com inserções contextuais justificadas;
- tamanho flexível orientado pelo objetivo e critérios pedagógicos de divisão;
- explicações progressivas, analogias limitadas e exemplos classificados;
- verificação obrigatória de aprendizagem com evidência observável, gabarito, checklist ou rubrica;
- rastreabilidade proporcional, hierarquia de fontes e seção “Fontes e atualização”;
- revisão obrigatória em camadas, com achados críticos, maiores, menores e sugestões;
- datas ISO 8601, versionamento `MAJOR.MINOR.PATCH`, revisões periódicas de 30, 90, 180 ou 365 dias e gatilhos extraordinários.

## Resultado concluído da DEC-08

A DEC-08 foi aprovada pelo usuário em 2026-07-24 com as escolhas 1A a 27A, registrada em `docs/DECISOES.md`, detalhada em `docs/SKILLS.md` e sincronizada com o Linear.

A decisão definiu:

- conceito oficial de Skill;
- diferenças entre Skill, decisão, memória, comando, ferramenta e autorização;
- limites de autoridade;
- estrutura obrigatória e campos condicionais;
- identificação global no padrão `SKILL-001`;
- ativação híbrida com validação de pré-condições;
- hierarquia geral e fontes específicas;
- procedimento sequencial e verificável;
- validação proporcional ao risco;
- tratamento controlado de erros e retomadas;
- ciclo de vida versionado;
- comandos gerais e específicos;
- critérios para criação de novas Skills;
- revisão individual do catálogo.

### Catálogo inicial aprovado

```text
SKILL-001 — Planejar Formação
SKILL-002 — Planejar Módulo
SKILL-003 — Produzir Aula
SKILL-004 — Revisar Aula
SKILL-005 — Publicar no GitHub
SKILL-006 — Atualizar Linear
SKILL-007 — Verificar Informações da OpenAI
SKILL-008 — Validar Conclusão de Módulo
SKILL-009 — Validar Conclusão de Formação
```

A antiga proposta `Aprovar Conteúdo` foi removida porque aprovação permanece decisão humana expressa pelos comandos oficiais.

A conclusão da DEC-08 não ativa automaticamente as Skills.

## Decisão atual — DEC-09

A LEA-112 / DEC-09 é o único item estrutural em andamento.

### Objetivo

Redigir e aprovar a instrução definitiva do Projeto ChatGPT, consolidando as decisões aprovadas em uma instrução curta, objetiva, aplicável e sem conflitos.

### Primeiro objetivo decisório

Definir a finalidade, o alcance e os requisitos obrigatórios da instrução definitiva antes de redigir sua versão consolidada.

### Fontes obrigatórias

1. `docs/CONSTITUICAO_DO_PROJETO.md`;
2. `PROJECT_STATE.md`;
3. `docs/DECISOES.md`;
4. `docs/SKILLS.md`;
5. `ROADMAP.md`;
6. LEA-112 e registros relacionados no Linear;
7. conversa atual.

Nenhuma escolha da DEC-09 foi aprovada pelo início da issue.

## Sequência obrigatória da LEA-103

```text
DEC-01 — concluída
    ↓
DEC-02 — concluída
    ↓
DEC-03 — concluída
    ↓
DEC-04 — concluída
    ↓
DEC-05 — concluída
    ↓
DEC-06 — concluída
    ↓
DEC-07 — concluída
    ↓
DEC-08 — concluída
    ↓
DEC-09 — em andamento
    ↓
DEC-10 — próxima após a conclusão da DEC-09
    ↓
Concluir LEA-103
    ↓
Retomar LEA-114 — Universo Didático
```

## Bloqueios

- **DEC-09:** sem bloqueio impeditivo conhecido.
- **DEC-10:** depende da conclusão da DEC-09.
- **LEA-114 / Universo Didático:** bloqueada pela conclusão da LEA-103.

## Regra de avanço

A DEC-10 não poderá ser iniciada apenas porque um texto da DEC-09 foi produzido ou aprovado na conversa. A LEA-112 deverá ser aprovada, registrada, sincronizada e formalmente concluída antes da transição.

## Última sincronização

- **Data:** 2026-07-24
- **GitHub:** Constituição, `PROJECT_STATE.md` e `ROADMAP.md` atualizados para o início da DEC-09.
- **Linear:** LEA-112 em `In Progress`; LEA-111 permanece concluída; LEA-113 permanece no Backlog.
- **Estado estrutural:** DEC-09 é o único item estrutural em andamento.
- **Integridade:** nenhum conteúdo pedagógico, diretório futuro, placeholder, Milestone, Issue pedagógica ou Sub-issue pedagógica foi criado; nenhuma publicação externa foi realizada.
