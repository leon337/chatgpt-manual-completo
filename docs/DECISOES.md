# Decisões do Projeto

Este documento registra somente decisões aprovadas. Discussões, alternativas e ideias ainda não aprovadas não devem ser tratadas como decisões oficiais.

## Registro OP-001 — Modelo Operacional do Projeto

- **Status:** aprovado e implantado
- **Data de aprovação:** 2026-07-21
- **Data de conclusão da implantação:** 2026-07-21
- **Linear:** LEA-115 — concluída

### Decisão

O projeto será conduzido pelo estado oficial sincronizado entre GitHub e Linear, e não apenas pela memória da conversa.

### Regras aprovadas

1. Antes de responder solicitações relacionadas ao projeto, o ChatGPT deve consultar a documentação oficial relevante e o Linear.
2. Apenas um item estrutural pode permanecer em andamento.
3. Nenhuma decisão posterior pode iniciar antes da conclusão e do registro da decisão atual.
4. As decisões da LEA-103 permanecem na sequência original: DEC-01 a DEC-10.
5. A LEA-115 foi uma tarefa corretiva de implementação e não criou uma nova DEC nem alterou a numeração existente.
6. Toda decisão aprovada deve atualizar os documentos aplicáveis no GitHub e o estado correspondente no Linear.
7. Uma etapa somente é concluída quando GitHub e Linear estiverem sincronizados.
8. Ideias fora da etapa atual devem permanecer no Backlog sem mudar o foco.
9. O ChatGPT não deve criar novas decisões, documentos ou alterações estruturais por iniciativa própria durante a execução de uma etapa.
10. Perguntas decisórias devem usar numeração e alternativas de `A` a `E`.
11. Cada alternativa utilizável como resposta direta deve aparecer em uma caixa copiável separada.
12. Autorizações, confirmações e comandos operacionais devem ser apresentados em caixas copiáveis.
13. Ao final das escolhas, deve existir uma caixa com a resposta compacta, como `1A 2C 3B`.

### Implantação concluída

- Constituição atualizada.
- Manual do Projeto atualizado.
- Eventos do projeto documentados.
- Processo de sincronização documentado.
- Instrução definitiva aplicada nas configurações do Projeto ChatGPT.
- Verificação funcional realizada em um novo chat.
- LEA-115 concluída no Linear.
- LEA-104 / DEC-01 liberada como primeiro item estrutural.

## DEC-01 — Identidade e visão do projeto

- **Status:** aprovada
- **Data de aprovação:** 2026-07-22
- **Linear:** LEA-104 — concluída

### Nome público

**Manual Completo da Plataforma ChatGPT**

### Relação com a PredixAI Academy

- **Manual Completo da Plataforma ChatGPT:** produto educacional e fonte de conteúdo.
- **PredixAI Academy:** plataforma onde o conteúdo será estudado, organizado e distribuído.

### Públicos

- **Público principal:** pessoas iniciantes, inclusive sem conhecimento técnico.
- **Públicos secundários:** estudantes, profissionais, empreendedores, educadores, criadores de conteúdo, desenvolvedores, empresas e sistemas de inteligência artificial.

### Idioma

- Português do Brasil como idioma principal.
- Termos técnicos originalmente em inglês serão preservados quando necessário, sempre acompanhados de explicação em português.
- Traduções para outros idiomas poderão ser produzidas futuramente.

### Posicionamento

Projeto educacional independente e não oficial, dedicado a estudar, organizar e explicar a Plataforma ChatGPT do nível iniciante ao especialista.

O projeto funciona como curso progressivo, manual de referência, documentação complementar e base de conhecimento, sem representar a OpenAI.

### Licenciamento

- **Conteúdo educacional e documentação:** Creative Commons Attribution-ShareAlike 4.0 International — CC BY-SA 4.0.
- **Exemplos de código e componentes de software:** MIT License.
- Atribuição obrigatória.
- Adaptações do conteúdo devem permanecer sob a mesma licença.
- Uso comercial permitido.

As licenças abrangem somente materiais originais do projeto ou materiais que possam legalmente ser licenciados por ele. Marcas, logos, capturas de tela, trechos e outros materiais pertencentes à OpenAI ou a terceiros não são automaticamente incluídos.

### Atribuição e titularidade

- **Conteúdo:** “Manual Completo da Plataforma ChatGPT — produto educacional da PredixAI Academy, coordenado por Leandro Carlos”.
- **Código:** Copyright © 2026 Leandro Carlos.

## DEC-02 — Estrutura pedagógica oficial

- **Status:** aprovada
- **Data de aprovação:** 2026-07-22
- **Linear:** LEA-105 — concluída

### Hierarquia oficial

```text
Manual
└── Formação
    └── Módulo
        └── Aula
```

Nenhum nível adicional integra a estrutura pedagógica oficial neste momento.

### Formação

Formação é o programa educacional completo dentro do Manual.

Na comunicação pública, uma Formação poderá ser chamada de curso para facilitar o entendimento do público. Nos documentos oficiais, identificadores e sistemas do projeto, o termo utilizado será sempre **Formação**.

Cada Formação contém vários Módulos.

### Módulo

Módulo é uma unidade temática e pedagógica dentro de uma Formação. Cada Módulo reúne Aulas relacionadas a um mesmo tema ou etapa de aprendizagem.

Todo Módulo deve possuir:

- objetivo próprio;
- sequência lógica de Aulas;
- conhecimentos ou habilidades esperados ao final;
- pré-requisitos, quando necessários.

O Módulo faz parte da progressão da Formação e não cria um novo nível estrutural.

### Aula

Aula é a menor unidade pedagógica oficial da estrutura do Manual.

Cada Aula pertence a um único Módulo e desenvolve um objetivo de aprendizagem específico ou um conjunto pequeno e coerente de objetivos relacionados.

A Aula pode conter explicações, exemplos, demonstrações, atividades e verificações de aprendizagem. O padrão editorial detalhado será definido na DEC-07.

A conclusão das Aulas contribui para o cumprimento dos objetivos do Módulo.

### Progressão pedagógica

A progressão oficial será sequencial. Cada Formação possuirá uma ordem definida de Módulos, e cada Módulo possuirá uma ordem definida de Aulas.

O estudante deverá seguir essa sequência para completar oficialmente a Formação, especialmente quando houver pré-requisitos.

Uma Aula ou um Módulo poderá ser consultado isoladamente como material de referência, mas essa consulta não equivale à conclusão da progressão pedagógica.

### Identificação oficial

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

### Expansão futura e estabilidade

Antes da aprovação, elementos em rascunho poderão ser reorganizados e renumerados.

Depois da aprovação ou publicação:

- o identificador não poderá ser reutilizado;
- o identificador não deverá ser alterado;
- novos elementos receberão o próximo número disponível dentro do elemento superior;
- a posição pedagógica será controlada separadamente pela ordem oficial.

Um novo elemento poderá ser inserido na progressão sem renumerar identificadores existentes.

## DEC-03 — Níveis de autonomia das ferramentas

- **Status:** aprovada
- **Data de aprovação:** 2026-07-22
- **Linear:** LEA-106 — concluída

### Três níveis oficiais

#### Nível 1 — Consulta Automática

A ferramenta pode consultar, pesquisar, ler, comparar, analisar e resumir fontes autorizadas sem solicitar confirmação, desde que não altere sistemas, arquivos, registros ou estados.

As consultas automáticas serão permitidas somente em fontes autorizadas e diretamente relacionadas à solicitação atual:

- documentos oficiais do repositório do projeto;
- issues, projetos e documentos correspondentes no Linear;
- documentação oficial da OpenAI;
- arquivos fornecidos pelo usuário ou vinculados ao projeto;
- outras fontes autorizadas pelas instruções ou pela solicitação atual.

A consulta deve utilizar somente o escopo necessário e permanecer exclusivamente em modo de leitura.

E-mails, calendários, contatos, arquivos pessoais, outros repositórios e serviços não relacionados somente poderão ser consultados quando o usuário solicitar ou quando existir autorização específica aplicável.

#### Nível 2 — Preparação em Rascunho

A ferramenta pode preparar automaticamente, na conversa ou em arquivos temporários de revisão:

- textos;
- documentos;
- código;
- análises;
- planos;
- propostas de alteração;
- descrições de issues;
- mensagens;
- e-mails ainda não criados no Gmail;
- comandos, diffs e mensagens de commit;
- versões completas de arquivos para revisão.

O material deve ser identificado como **RASCUNHO** quando houver risco de ser confundido com conteúdo aprovado ou publicado.

Sem autorização explícita, a ferramenta não poderá salvar o rascunho em sistemas externos, criar ou alterar issues, criar comentários, branches, commits ou pull requests, criar rascunhos no Gmail, enviar mensagens, criar eventos, substituir arquivos oficiais ou registrar o conteúdo como decisão ou estado do projeto.

Qualquer criação ou gravação em sistema externo pertence ao Nível 3.

#### Nível 3 — Execução Controlada

Qualquer ação que altere um sistema externo ou o estado oficial do projeto exige autorização do usuário.

O Nível 3 possui duas categorias internas, sem criar novos níveis oficiais.

### Execução Controlada Padrão

Abrange alterações externas normalmente reversíveis, internas ou privadas, de alcance limitado, sem dados sensíveis, sem comunicação externa e sem alteração relevante do estado oficial.

Uma solicitação direta, específica e suficientemente clara do usuário já poderá funcionar como autorização, desde que o sistema, o alvo, a ação e o resultado estejam claros.

### Execução Controlada Crítica

Abrange ações destrutivas, irreversíveis, públicas, comunicacionais, sensíveis ou com impacto relevante sobre o estado oficial.

Exemplos, conforme o contexto:

- enviar e-mail ou mensagem;
- publicar conteúdo;
- realizar commit ou merge;
- sobrescrever arquivo oficial;
- excluir arquivos ou registros;
- fechar ou cancelar tarefas;
- alterar roadmap;
- mudar permissões;
- modificar dados sensíveis;
- executar ações em massa.

Antes da execução, a ferramenta deverá apresentar uma confirmação prévia contendo:

- sistema afetado;
- alvo;
- ação;
- efeito esperado;
- alcance;
- possibilidade de reversão;
- riscos relevantes.

A execução somente poderá ocorrer depois de confirmação explícita do usuário sobre esse resumo.

### Alcance e validade das autorizações

A autorização será específica, delimitada e consumível. Ela será válida somente para a ação ou para o conjunto de ações claramente descrito e diretamente relacionado ao objetivo atual.

Uma única autorização poderá abranger várias ações quando estiverem claramente definidos:

- o sistema afetado;
- os alvos;
- as ações;
- o resultado esperado;
- os limites da execução.

A autorização será considerada encerrada quando:

- as ações autorizadas forem concluídas;
- o usuário cancelar a execução;
- houver mudança relevante de alvo, conteúdo, quantidade ou efeito;
- surgir uma condição diferente da apresentada ao usuário.

A autorização não se estende automaticamente a ações futuras semelhantes. Para execuções críticas, qualquer mudança relevante de escopo exigirá nova autorização.

Autorizações permanentes somente poderão existir quando forem aprovadas como regra oficial do projeto.

### Classificação pelo contexto e efeito real

A classificação dependerá do contexto e do efeito real, e não apenas do nome da ação ou da ferramenta utilizada.

Uma ação normalmente padrão será elevada para crítica quando envolver:

- publicação ou exposição pública;
- comunicação com destinatários externos;
- repositório, branch, documento ou ambiente oficial;
- dados pessoais, confidenciais ou sensíveis;
- produção, segurança, permissões ou credenciais;
- impacto jurídico, financeiro ou reputacional;
- execução em massa;
- efeito irreversível ou de difícil reversão;
- alteração relevante do estado oficial do projeto.

Quando houver dúvida razoável sobre a classificação, a ação será tratada como crítica até que o escopo seja esclarecido.

### Relação com a DEC-04

A DEC-03 define os níveis de autonomia, a classificação de risco, o alcance das autorizações e a necessidade de confirmação. A forma exata dos comandos e fluxos de aprovação será definida na DEC-04.

## Mapa oficial da LEA-103

| Ordem | Decisão | Issue |
|---|---|---|
| 1 | DEC-01 — Identidade e visão do projeto | LEA-104 |
| 2 | DEC-02 — Estrutura pedagógica oficial | LEA-105 |
| 3 | DEC-03 — Níveis de autonomia das ferramentas | LEA-106 |
| 4 | DEC-04 — Fluxo e comandos de aprovação | LEA-107 |
| 5 | DEC-05 — Estrutura e responsabilidades do GitHub | LEA-108 |
| 6 | DEC-06 — Estrutura operacional do Linear | LEA-109 |
| 7 | DEC-07 — Padrão editorial das aulas | LEA-110 |
| 8 | DEC-08 — Catálogo de Skills do projeto | LEA-111 |
| 9 | DEC-09 — Instrução definitiva do Projeto ChatGPT | LEA-112 |
| 10 | DEC-10 — Revisão e aprovação final | LEA-113 |

A LEA-115 permanece como tarefa corretiva concluída e não faz parte da numeração DEC-01 a DEC-10.

## Estado estrutural atual

- **Último item concluído:** LEA-106 — DEC-03: Níveis de autonomia das ferramentas.
- **Item em andamento:** nenhum.
- **Próximo item:** LEA-107 — DEC-04, no Backlog e ainda não iniciado.

## Decisões ainda não concluídas

As decisões DEC-04 a DEC-10 permanecem pendentes e devem ser executadas sequencialmente.

## Universo Didático

A LEA-114 permanece no Backlog e bloqueada pela conclusão da LEA-103. As ideias já discutidas sobre o universo são rascunhos não canônicos e não alteram a sequência atual.
