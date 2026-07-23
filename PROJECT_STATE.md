# Estado do Projeto

## Situação

- **Projeto:** Manual Completo da Plataforma ChatGPT
- **Fase:** decisões estruturais da LEA-103
- **Status geral:** em produção
- **Conteúdo didático:** ainda não iniciado
- **Repositório:** identidade, licenciamento, estrutura pedagógica, níveis de autonomia, fluxo de aprovação, arquitetura documental, estrutura operacional do Linear e padrão editorial das Aulas registrados
- **Linear:** LEA-104 a LEA-110 concluídas; LEA-111 em andamento

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

- **Último item concluído:** LEA-110 — DEC-07: Definir padrão editorial das aulas
- **Item estrutural em andamento:** LEA-111 — DEC-08: Projetar catálogo de Skills do projeto
- **Status:** DEC-08 iniciada e sincronizada; nenhuma escolha de Skill aprovada
- **Objetivo atual:** definir o conceito oficial, os limites, a estrutura mínima, os gatilhos, as pré-condições, as fontes, os procedimentos, as restrições e os resultados esperados das Skills do projeto
- **Próximo item após a conclusão:** LEA-112 — DEC-09: Redigir instrução definitiva do Projeto ChatGPT

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

A conclusão da DEC-07 não significa publicação e não inicia automaticamente a DEC-08.

## DEC-08 em desenvolvimento

A LEA-111 foi iniciada em 2026-07-23 como único item estrutural em andamento.

A DEC-08 deverá definir:

- conceito oficial de Skill;
- diferenças entre Skill, decisão, memória, comando e ferramenta;
- estrutura mínima obrigatória;
- gatilhos e pré-condições;
- fontes obrigatórias;
- procedimento e restrições;
- resultado esperado;
- comandos disponíveis ao usuário;
- critérios de criação, aprovação, revisão, atualização e descontinuação;
- catálogo oficial de Skills do projeto.

O esqueleto e as dez Skills já listadas em `docs/SKILLS.md` permanecem propostas. Nenhuma Skill foi aprovada pelo início da decisão.

## Decisão atual

**LEA-111 — DEC-08** é o único item estrutural em andamento.

O trabalho inicial deve definir primeiro o conceito, os limites e a estrutura mínima de uma Skill. Somente depois será permitido avaliar individualmente as Skills propostas.

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
DEC-08 — em andamento
    ↓
DEC-09 — próxima após a conclusão da DEC-08
    ↓
DEC-10
    ↓
Concluir LEA-103
    ↓
Retomar LEA-114 — Universo Didático
```

## Bloqueios

- **DEC-09 e DEC-10:** bloqueadas pela execução sequencial das decisões anteriores.
- **LEA-114 / Universo Didático:** bloqueada pela conclusão da LEA-103.
- **DEC-08:** sem bloqueio impeditivo conhecido.

## Regra de avanço

A DEC-09 não poderá ser iniciada apenas porque a DEC-08 começou ou teve escolhas discutidas. A LEA-111 deverá ser aprovada, registrada, sincronizada e formalmente concluída antes da transição.

## Última sincronização

- **Data:** 2026-07-23
- **GitHub:** DEC-08 registrada como decisão em desenvolvimento; `docs/SKILLS.md` mantém todas as Skills como propostas.
- **Linear:** LEA-111 em `In Progress`; LEA-103 permanece em andamento; LEA-112 permanece em `Backlog`.
- **Estado estrutural:** DEC-08 é o único item em andamento; DEC-09 é a próxima decisão.
- **Integridade:** nenhuma Skill foi aprovada; nenhum conteúdo pedagógico, diretório futuro, placeholder, Milestone, Issue pedagógica ou Sub-issue pedagógica foi criado.
