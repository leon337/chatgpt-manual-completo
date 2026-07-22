# Manual Completo da Plataforma ChatGPT

Projeto educacional independente e não oficial, dedicado a estudar, organizar e explicar a Plataforma ChatGPT do nível iniciante ao especialista.

O Manual funciona como curso progressivo, manual de referência, documentação complementar e base de conhecimento para humanos e sistemas de inteligência artificial. O projeto não representa a OpenAI.

## Relação com a PredixAI Academy

- **Manual Completo da Plataforma ChatGPT:** produto educacional e fonte de conteúdo.
- **PredixAI Academy:** plataforma onde o conteúdo será estudado, organizado e distribuído.

## Públicos

- **Público principal:** pessoas iniciantes, inclusive sem conhecimento técnico.
- **Públicos secundários:** estudantes, profissionais, empreendedores, educadores, criadores de conteúdo, desenvolvedores, empresas e sistemas de inteligência artificial.

## Idioma

O idioma principal é o português do Brasil. Termos técnicos originalmente em inglês serão preservados quando necessário e acompanhados de explicação em português. Traduções para outros idiomas poderão ser produzidas futuramente.

## Estrutura pedagógica

```text
Manual
└── Formação
    └── Módulo
        └── Aula
```

- **Formação:** programa educacional completo dentro do Manual. Na comunicação pública, também poderá ser chamada de curso.
- **Módulo:** unidade temática e pedagógica que reúne Aulas relacionadas.
- **Aula:** menor unidade pedagógica oficial da estrutura.

A progressão oficial será sequencial, embora Aulas e Módulos possam ser consultados isoladamente como material de referência.

### Identificação

```text
Formação: F01, F02, F03...
Módulo:   M01, M02, M03...
Aula:     A01, A02, A03...

Identificador completo:
F01-M02-A03
```

Os identificadores tornam-se permanentes após a aprovação ou publicação. A ordem pedagógica será controlada separadamente para permitir futuras inserções sem renumerar referências existentes.

## Níveis de autonomia

As ferramentas do projeto utilizam três níveis oficiais:

- **Nível 1 — Consulta Automática:** leitura, pesquisa, comparação, análise e resumo em fontes autorizadas, relacionadas ao trabalho atual e no menor escopo necessário.
- **Nível 2 — Preparação em Rascunho:** produção de materiais para revisão sem gravação em sistemas externos.
- **Nível 3 — Execução Controlada:** qualquer ação que altere sistemas, registros ou o estado oficial exige autorização proporcional ao risco.

O Nível 3 distingue ações padrão, normalmente reversíveis e limitadas, de ações críticas, como publicações, envios, commits, sobrescritas, exclusões, alterações de roadmap e operações sensíveis. A classificação considera o contexto e o efeito real da execução.

## Fluxo e comandos de aprovação

O projeto utiliza linguagem natural clara e comandos canônicos. Os comandos são escritos em português do Brasil, entre colchetes, em letras maiúsculas e no formato `AÇÃO + OBJETO`.

```text
[APROVAR CONTEÚDO]
[APROVAR DECISÃO]
[APROVAR ENTREGA]
[SOLICITAR CORREÇÕES]
[REABRIR ESCOLHA]
[AUTORIZAR REGISTRO OFICIAL]
[AUTORIZAR PUBLICAÇÃO]
[AUTORIZAR EXECUÇÃO CRÍTICA]
[CONCLUIR ETAPA]
[INICIAR PRÓXIMA DECISÃO]
```

Aprovação não significa registro, publicação, conclusão ou avanço. Ações críticas continuam exigindo resumo prévio e autorização específica.

## Arquitetura documental

A DEC-05 definiu uma estrutura mínima, progressiva e separada por responsabilidade.

### Estrutura ativa

```text
/
├── README.md
├── PROJECT_STATE.md
├── ROADMAP.md
├── CHANGELOG.md
├── LICENSE-CONTENT.md
├── LICENSE-CODE.md
└── docs/
    ├── CONSTITUICAO_DO_PROJETO.md
    ├── DECISOES.md
    ├── SKILLS.md
    └── MANUAL_DO_PROJETO.md
```

### Estruturas futuras reservadas

Os diretórios abaixo permanecem apenas planejados e somente serão criados quando houver necessidade concreta, conteúdo mínimo útil e autorização aplicável:

```text
curriculum/
content/
research/
assets/
```

- `curriculum/`: arquitetura pedagógica global e mapas curriculares.
- `content/`: conteúdo pedagógico canônico de Formações, Módulos e Aulas.
- `research/`: pesquisas, fontes, evidências e notas técnicas de apoio.
- `assets/`: imagens, diagramas, ilustrações e recursos reutilizáveis.

A versão canônica do conteúdo permanecerá em `content/`. Não será criado um diretório `published/` apenas para duplicar materiais publicados.

### Responsabilidade dos documentos centrais

- [`README.md`](README.md): apresentação pública e navegação.
- [`PROJECT_STATE.md`](PROJECT_STATE.md): estado operacional oficial atual.
- [`ROADMAP.md`](ROADMAP.md): sequência e planejamento estrutural.
- [`CHANGELOG.md`](CHANGELOG.md): histórico de alterações permanentes.
- [`docs/CONSTITUICAO_DO_PROJETO.md`](docs/CONSTITUICAO_DO_PROJETO.md): regras superiores de governança.
- [`docs/DECISOES.md`](docs/DECISOES.md): decisões aprovadas.
- [`docs/SKILLS.md`](docs/SKILLS.md): procedimentos repetíveis aprovados.
- [`docs/MANUAL_DO_PROJETO.md`](docs/MANUAL_DO_PROJETO.md): aplicação prática das regras.

Cada tipo de informação possui uma única fonte canônica. Documentos secundários podem apresentar resumos e links, mas não versões completas concorrentes.

## Estado atual

**Fase:** decisões estruturais da LEA-103.

As decisões DEC-01 a DEC-05 foram aprovadas, registradas e sincronizadas. A LEA-109 / DEC-06 está em andamento para definir a estrutura operacional do Linear. A LEA-110 / DEC-07 permanece no Backlog como próxima etapa após a conclusão da DEC-06.

O conteúdo didático ainda não foi iniciado. Documentos marcados como rascunho não representam decisões finais nem material publicado do curso.

## Fontes operacionais

- **Linear:** planejamento, decisões, progresso e critérios de conclusão.
- **GitHub:** documentação oficial, histórico e conteúdo aprovado ou publicado.
- **Documentação oficial da OpenAI:** fonte primária para informações atuais sobre ChatGPT e produtos OpenAI.

## Licenciamento

- **Conteúdo educacional e documentação:** [CC BY-SA 4.0](LICENSE-CONTENT.md).
- **Exemplos de código e componentes de software:** [MIT License](LICENSE-CODE.md).

Atribuição do conteúdo:

> Manual Completo da Plataforma ChatGPT — produto educacional da PredixAI Academy, coordenado por Leandro Carlos.

As licenças aplicam-se somente aos materiais originais do projeto ou que possam legalmente ser licenciados por ele. Marcas, logos, capturas de tela e outros materiais pertencentes à OpenAI ou a terceiros permanecem sujeitos aos direitos de seus respectivos titulares.

## Documentos centrais

- [`PROJECT_STATE.md`](PROJECT_STATE.md)
- [`ROADMAP.md`](ROADMAP.md)
- [`CHANGELOG.md`](CHANGELOG.md)
- [`docs/CONSTITUICAO_DO_PROJETO.md`](docs/CONSTITUICAO_DO_PROJETO.md)
- [`docs/DECISOES.md`](docs/DECISOES.md)
- [`docs/MANUAL_DO_PROJETO.md`](docs/MANUAL_DO_PROJETO.md)
- [`docs/SKILLS.md`](docs/SKILLS.md)
