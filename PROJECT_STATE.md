# Estado do Projeto

## Situação

- **Projeto:** Manual Completo da Plataforma ChatGPT
- **Fase:** decisões estruturais da LEA-103
- **Status geral:** em produção
- **Conteúdo didático:** ainda não iniciado
- **Repositório:** identidade, licenciamento, estrutura pedagógica, níveis de autonomia, fluxo de aprovação, arquitetura documental, estrutura operacional do Linear e padrão editorial das Aulas registrados
- **Linear:** LEA-104, LEA-105, LEA-106, LEA-107, LEA-108 e LEA-109 concluídas; LEA-110 em andamento

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

- **Último item concluído:** LEA-109 — DEC-06: Definir estrutura operacional do Linear
- **Item estrutural em andamento:** LEA-110 — DEC-07: Definir padrão editorial das aulas
- **Status:** decisão aprovada e registrada; conclusão formal pendente
- **Objetivo atual:** validar o registro oficial, confirmar o atendimento dos critérios de aceitação e concluir formalmente a DEC-07 sem iniciar a DEC-08
- **Próximo item após a conclusão:** LEA-111 — DEC-08: Projetar catálogo de Skills do projeto

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

A DEC-07 foi aprovada e registrada com as escolhas 1A a 9A. O padrão editorial oficial das Aulas estabelece:

- núcleo obrigatório com identificação, objetivo, pré-requisitos, introdução, desenvolvimento, síntese, verificação e fontes;
- catálogo controlado de seções opcionais;
- ordem editorial principal com inserções contextuais justificadas;
- tamanho flexível orientado pelo objetivo e critérios pedagógicos de divisão;
- explicações progressivas, analogias limitadas e exemplos classificados;
- verificação obrigatória de aprendizagem com evidência observável, gabarito, checklist ou rubrica;
- rastreabilidade proporcional, hierarquia de fontes e seção “Fontes e atualização”;
- revisão obrigatória em camadas, com achados críticos, maiores, menores e sugestões;
- datas ISO 8601, versionamento `MAJOR.MINOR.PATCH`, revisões periódicas de 30, 90, 180 ou 365 dias e gatilhos extraordinários.

A aprovação e o registro não significam publicação nem conclusão automática da LEA-110.

## Decisão atual

**LEA-110 — DEC-07** permanece como único item estrutural em andamento.

A versão aprovada foi registrada em `docs/DECISOES.md`, resumida neste estado e incorporada ao funcionamento diário em `docs/MANUAL_DO_PROJETO.md`.

A conclusão formal ainda depende de:

- verificar os registros e evidências produzidos;
- confirmar que GitHub e Linear indicam o mesmo estado;
- confirmar que os critérios de aceitação foram atendidos;
- validar a LEA-111 como próxima decisão sem iniciá-la;
- executar o fluxo de `[CONCLUIR ETAPA]`.

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
DEC-07 — aprovada e registrada; conclusão pendente
    ↓
DEC-08 — próxima após a conclusão da DEC-07
    ↓
DEC-09
    ↓
DEC-10
    ↓
Concluir LEA-103
    ↓
Retomar LEA-114 — Universo Didático
```

## Bloqueios

- **DEC-08 a DEC-10:** bloqueadas pela conclusão sequencial das decisões anteriores.
- **LEA-114 / Universo Didático:** bloqueada pela conclusão da LEA-103.
- **DEC-07:** sem bloqueio impeditivo; conclusão formal pendente.

## Regra de avanço

A DEC-08 não poderá ser iniciada apenas porque a DEC-07 foi aprovada e registrada. A LEA-110 deverá ter os critérios validados, GitHub e Linear sincronizados e a etapa formalmente concluída antes da transição.

## Última sincronização

- **Data:** 2026-07-23
- **GitHub:** DEC-07 aprovada e registrada com as escolhas 1A a 9A; LEA-110 mantida como item em andamento.
- **Linear:** LEA-110 mantida em `In Progress`, com aprovação e registro oficial documentados; LEA-103 permanece em andamento.
- **Estado estrutural:** DEC-07 aprovada e registrada, aguardando conclusão formal; DEC-08 ainda não iniciada.
- **Integridade:** nenhum conteúdo pedagógico, diretório futuro, placeholder, Milestone, Issue pedagógica ou Sub-issue pedagógica foi criado.