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

A Aula pode conter explicações, exemplos, demonstrações, atividades e verificações de aprendizagem. O padrão editorial detalhado será definido posteriormente na DEC-07.

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

## DEC-04 — Fluxo e comandos de aprovação

- **Status:** aprovada
- **Data de aprovação:** 2026-07-22
- **Linear:** LEA-107 — concluída

### 1. Modelo híbrido de interação

O projeto aceita solicitações em linguagem natural direta, específica e inequívoca e também comandos canônicos padronizados.

As duas formas poderão representar a mesma intenção. Mensagens ambíguas não serão interpretadas como aprovação ou autorização. O ChatGPT deverá informar qual intenção reconheceu quando isso for relevante para a execução.

### 2. Formato canônico dos comandos

Os comandos oficiais utilizam:

- colchetes;
- letras maiúsculas;
- português do Brasil;
- estrutura `AÇÃO + OBJETO`;
- uma intenção principal por comando.

O alvo poderá ser informado depois do comando ou estar claramente determinado pelo contexto.

### 3. Aprovação separada de execução

Comandos:

```text
[APROVAR CONTEÚDO]
[APROVAR DECISÃO]
[APROVAR ENTREGA]
```

A aprovação confirma a versão aceita, encerra a revisão e permite preparar os registros finais.

A aprovação isoladamente não poderá:

- criar commits;
- alterar documentos oficiais no GitHub;
- atualizar ou concluir issues no Linear;
- publicar conteúdo;
- enviar mensagens;
- iniciar a próxima decisão.

Aprovação não significa publicação, registro, conclusão ou avanço.

### 4. Correções e reabertura de escolhas

```text
[SOLICITAR CORREÇÕES]
[REABRIR ESCOLHA]
```

`[SOLICITAR CORREÇÕES]` é usado para pedir alterações em textos, documentos, planos, código, propostas ou entregas em preparação ou revisão. A solicitação deve identificar, quando aplicável, alvo, trecho ou aspecto afetado, mudança desejada e condições que devem ser preservadas.

O comando autoriza somente a preparação de uma nova versão. Não aprova, registra, publica nem substitui registros oficiais.

`[REABRIR ESCOLHA]` é usado para reconsiderar uma escolha dentro da decisão atual antes da conclusão e do registro definitivo. O comando suspende provisoriamente apenas o ponto identificado, preserva as demais escolhas e exige nova resposta.

Decisões já concluídas e registradas não podem ser sobrescritas apenas com esse comando. Correções oficiais posteriores exigem análise de impacto, proposta corretiva, autorização específica e histórico preservado.

### 5. Registro oficial

```text
[AUTORIZAR REGISTRO OFICIAL]
```

Antes de solicitar esse comando, o ChatGPT deve apresentar resumo contendo:

- sistemas afetados;
- arquivos, documentos, issues ou registros atingidos;
- ações previstas;
- conteúdo ou versão que será registrada;
- mudanças de status;
- resultado esperado;
- possibilidade de reversão;
- riscos relevantes;
- estado esperado após a sincronização.

A autorização poderá abranger GitHub e Linear conjuntamente quando os alvos e ações estiverem enumerados. Ela será válida somente para o resumo imediatamente anterior ou explicitamente identificado.

Depois da execução, o ChatGPT deverá informar alterações, commits ou evidências, estados das issues, sincronização e qualquer falha ou divergência.

O comando não autoriza publicação externa, exclusões não descritas, ampliação de escopo, início da próxima decisão ou reutilização futura.

### 6. Publicação e demais execuções críticas

```text
[AUTORIZAR PUBLICAÇÃO]
[AUTORIZAR EXECUÇÃO CRÍTICA]
```

`[AUTORIZAR PUBLICAÇÃO]` é usado para tornar pública uma versão já aprovada. Antes da autorização, devem ser informados conteúdo e versão, canal ou plataforma, público ou destinatários, ação exata, alcance, momento quando aplicável, reversibilidade, riscos e evidência esperada.

A autorização não se estende a alterações adicionais, outros canais, mensagens não descritas, campanhas, gastos ou republicações futuras.

`[AUTORIZAR EXECUÇÃO CRÍTICA]` é usado para ações críticas diferentes de publicação, incluindo exclusão, sobrescrita, merge, envio, alteração de permissões, tratamento de dados sensíveis e operações em massa.

Sem resumo válido, esses comandos iniciam somente a preparação da confirmação. Ações críticas não relacionadas não serão agrupadas implicitamente. Mudanças de escopo exigem novo resumo e nova autorização.

### 7. Conclusão formal da etapa

```text
[CONCLUIR ETAPA]
```

O comando solicita validação final e não produz conclusão automática.

Ao reconhecê-lo, o ChatGPT deve verificar:

- aprovação da versão final;
- conclusão de todas as escolhas necessárias;
- ausência de correções ou escolhas reabertas;
- atendimento dos critérios de aceitação;
- identificação dos registros oficiais necessários;
- bloqueios ou divergências;
- próximo item previsto.

Quando o registro oficial estiver pendente, o ChatGPT deve informar a pendência, apresentar o checklist, preparar o resumo e solicitar `[AUTORIZAR REGISTRO OFICIAL]`.

Somente depois de verificar documentos, commits ou evidências, estado no Linear, sincronização, histórico e próximo item confirmado poderá declarar `ETAPA CONCLUÍDA`.

O comando não autoriza publicação, exclusões, mudanças não descritas ou início da próxima decisão.

### 8. Início da próxima decisão

```text
[INICIAR PRÓXIMA DECISÃO]
```

O comando solicita a preparação e a validação da transição. Somente poderá ser reconhecido quando a etapa anterior já tiver sido declarada `ETAPA CONCLUÍDA`.

O ChatGPT deverá:

- reconstruir o contexto oficial;
- confirmar a sincronização entre GitHub e Linear;
- confirmar que nenhum item estrutural permanece em andamento;
- identificar a próxima decisão obrigatória;
- verificar dependências e bloqueios;
- apresentar resumo da transição.

O resumo deve informar item concluído, próximo item, sistemas afetados, issue que será iniciada, mudanças previstas, resultado esperado, reversibilidade, riscos de sincronização e primeiro objetivo decisório.

A alteração do estado oficial dependerá de nova autorização por `[AUTORIZAR REGISTRO OFICIAL]`.

Somente após essa autorização será permitido mover a próxima issue para `In Progress`, atualizar os documentos oficiais, confirmar que existe apenas um item estrutural em andamento, verificar a sincronização e apresentar a primeira pergunta da nova decisão.

O comando não poderá ignorar decisões intermediárias, iniciar uma issue fora da sequência, reutilizar uma autorização anterior ou iniciar duas decisões simultaneamente.

### Catálogo consolidado

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

## DEC-05 — Estrutura e responsabilidades do GitHub

- **Status:** aprovada e concluída
- **Data de aprovação:** 2026-07-22
- **Linear:** LEA-108 — concluída

### 1. Estrutura mínima e progressiva

A estrutura ativa do repositório será:

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

As estruturas futuras reservadas serão:

```text
curriculum/
content/
research/
assets/
```

Esses diretórios poderão ser registrados conceitualmente, mas não serão criados antes da etapa correspondente. Nenhum arquivo vazio será criado apenas para representar uma ideia futura.

### 2. Responsabilidade dos arquivos da raiz

- `README.md`: apresentação pública, identidade, finalidade, navegação, resumo breve do estado e links para documentos oficiais.
- `PROJECT_STATE.md`: estado operacional oficial atual, item em andamento, último item concluído, próximo item, objetivo, bloqueios e última sincronização.
- `ROADMAP.md`: fases, sequência planejada, dependências e itens concluídos, atuais e futuros.
- `CHANGELOG.md`: histórico cronológico de alterações permanentes relevantes.
- `LICENSE-CONTENT.md`: termos aplicáveis ao conteúdo educacional e à documentação.
- `LICENSE-CODE.md`: termos aplicáveis aos exemplos de código e componentes de software.

Cada informação deve possuir uma fonte oficial principal. Os demais documentos podem manter resumos e links, mas não cópias completas concorrentes.

### 3. Responsabilidade dos documentos em `docs/`

A hierarquia interna será:

1. `docs/CONSTITUICAO_DO_PROJETO.md` — regras permanentes, missão, princípios, hierarquia, autonomia e governança;
2. `docs/DECISOES.md` — decisões aprovadas, identificadores, datas, status, issues e resultados oficiais;
3. `docs/SKILLS.md` — procedimentos repetíveis aprovados, gatilhos, pré-condições, fontes, restrições e resultados esperados;
4. `docs/MANUAL_DO_PROJETO.md` — aplicação prática da Constituição e das decisões no trabalho diário.

Em caso de divergência, o documento inferior deve ser corrigido para respeitar o documento superior.

### 4. Documento curricular futuro

O futuro `curriculum/CURRICULUM.md` será a fonte oficial da arquitetura pedagógica global.

Ele somente será criado quando:

- a etapa de definição curricular estiver oficialmente iniciada;
- existir conteúdo pedagógico suficiente;
- sua primeira versão estiver preparada;
- houver autorização específica para registro.

Sua função será apresentar o mapa das Formações, objetivos, sequência, pré-requisitos, Módulos, identificadores e ligações com o conteúdo armazenado em `content/`.

O arquivo não conterá Aulas completas, pesquisas, estado operacional, regras editoriais ou decisões de governança.

### 5. Separação funcional

- `curriculum/`: arquitetura pedagógica global.
- `content/`: conteúdo pedagógico canônico de Formações, Módulos e Aulas.
- `research/`: pesquisas, fontes, evidências, comparações e notas técnicas de apoio.
- `assets/`: imagens, diagramas, ilustrações, capturas autorizadas e recursos reutilizáveis.

Não será criado um diretório `published/` apenas para duplicar conteúdo. A publicação distribui uma versão aprovada, mas a fonte canônica permanece em `content/`. Saídas técnicas exigidas por plataformas não substituem a fonte canônica.

### 6. Criação e ciclo de vida

Um novo arquivo ou diretório somente poderá ser criado quando:

1. existir necessidade concreta e atual;
2. a informação não couber adequadamente em uma fonte oficial existente;
3. a responsabilidade estiver claramente definida;
4. a localização correta estiver identificada;
5. existir conteúdo mínimo útil;
6. não for apenas arquivo vazio ou marcador de intenção;
7. a criação pertencer à etapa aplicável;
8. houver aprovação e autorização exigidas.

O resumo prévio deve informar caminho, nome, finalidade, tipo de informação, fonte oficial, relação com documentos existentes, motivo da insuficiência das fontes atuais, momento de atualização, riscos de duplicidade, impacto na navegação e reversibilidade.

Movimentações e renomeações exigem justificativa, análise das referências, novo caminho, plano de atualização de links, eliminação de cópias concorrentes e autorização específica.

Substituições exigem responsabilidade equivalente ou superior, destino para o conteúdo válido, atualização de referências e preservação do histórico.

O histórico do Git será o mecanismo padrão de recuperação de versões. Exclusões exigem análise de impacto, resumo prévio e autorização de execução crítica.

É proibido criar arquivos vazios, diretórios decorativos, cópias por estado, documentos com responsabilidade indefinida, arquivos que repitam integralmente uma fonte oficial e estruturas de decisões futuras ainda não iniciadas.

### 7. Fontes canônicas e atualização coordenada

Cada tipo de informação terá uma única fonte oficial principal:

- apresentação pública e navegação: `README.md`;
- estado operacional atual: `PROJECT_STATE.md`;
- sequência e planejamento estrutural: `ROADMAP.md`;
- histórico de alterações permanentes: `CHANGELOG.md`;
- regras superiores: `docs/CONSTITUICAO_DO_PROJETO.md`;
- decisões aprovadas: `docs/DECISOES.md`;
- procedimentos repetíveis: `docs/SKILLS.md`;
- explicações operacionais: `docs/MANUAL_DO_PROJETO.md`;
- arquitetura pedagógica global: `curriculum/CURRICULUM.md`, quando criado;
- conteúdo pedagógico canônico: `content/`;
- pesquisas e evidências: `research/`;
- recursos reutilizáveis: `assets/`.

Documentos secundários podem apresentar resumo breve, identificadores, títulos, comandos necessários e links. Não podem manter versão integral concorrente, alterar o significado da fonte canônica ou conservar informação desatualizada.

Antes de alterar uma informação oficial, devem ser identificados a fonte canônica, documentos com resumos ou referências, links e índices afetados, mudanças coordenadas e verificações necessárias.

Quando duas fontes forem incompatíveis:

1. interromper o avanço;
2. identificar a fonte canônica;
3. verificar a hierarquia documental;
4. preparar a correção dos documentos secundários;
5. solicitar autorização quando houver alteração externa;
6. confirmar novamente a sincronização.

Links relativos serão preferidos dentro do repositório e deverão ser atualizados após movimentações ou renomeações.

Duplicação de responsabilidade é proibida. Resumo referencial é permitido. A fonte canônica preserva a autoridade.

### 8. Resultado da implementação

- A arquitetura documental foi registrada nos documentos oficiais aplicáveis.
- Nenhum diretório futuro foi criado.
- Nenhum arquivo vazio, placeholder ou diretório `published/` foi criado.
- A LEA-108 foi concluída.
- A LEA-109 permaneceu no Backlog como próxima decisão não iniciada.

## DEC-06 — Estrutura operacional do Linear

- **Status:** aprovada, registrada e concluída
- **Data de aprovação:** 2026-07-22
- **Data de registro:** 2026-07-22
- **Linear:** LEA-109 — concluída

### 1. Correspondência hierárquica

A correspondência oficial será:

```text
Manual
└── Project do Linear
    └── Formação
        └── Milestone
            └── Módulo
                └── Issue
                    └── Aula
                        └── Sub-issue
```

Existirá um único Project principal para o Manual. Nenhuma entidade pedagógica real será criada antes da etapa aplicável e da autorização exigida.

### 2. Milestones de Formação

Cada Formação que entrar efetivamente em planejamento ou produção poderá receber uma Milestone identificada pelo código e pelo título da Formação, como `F01 — Formação Inicial sobre ChatGPT`.

A Milestone somente será criada quando:

- a Formação estiver oficialmente aprovada para planejamento;
- existir objetivo educacional definido;
- houver conteúdo mínimo para iniciar sua decomposição em Módulos;
- pelo menos uma Issue de Módulo estiver pronta para criação;
- existir autorização aplicável para alterar o Linear.

Não serão criadas Milestones vazias para Formações apenas previstas.

A Milestone agrupará Issues dos Módulos, Sub-issues das Aulas e tarefas exclusivamente relacionadas àquela Formação. Tarefas gerais do Manual permanecerão diretamente no Project.

A Milestone controlará execução, progresso e conclusão, mas não armazenará o conteúdo pedagógico canônico.

Uma Milestone somente poderá ser concluída quando todos os Módulos e Aulas obrigatórios estiverem concluídos, os objetivos da Formação forem atendidos, os registros aplicáveis estiverem atualizados e GitHub e Linear estiverem sincronizados. Concluir a Milestone não significará publicar a Formação.

### 3. Issues de Módulo, Sub-issues de Aula e tarefas operacionais

Cada Módulo será uma Issue vinculada ao Project e à Milestone da Formação. O título seguirá o padrão `F01-M01 — Título do Módulo`.

A descrição da Issue de Módulo deverá conter, conforme aplicável:

- identificador e título;
- Formação;
- objetivo pedagógico;
- escopo resumido;
- pré-requisitos;
- relação prevista de Aulas;
- critérios objetivos de conclusão;
- link para a fonte canônica no GitHub;
- bloqueios e relações operacionais.

Cada Aula será uma Sub-issue da Issue do Módulo. O título seguirá o padrão `F01-M01-A01 — Título da Aula`.

A descrição da Sub-issue deverá conter, conforme aplicável:

- identificador e título;
- objetivo de aprendizagem;
- escopo resumido;
- critérios objetivos de conclusão;
- link para o conteúdo canônico;
- evidências e referências operacionais;
- bloqueios e relações.

A criação será progressiva. Não serão criadas antecipadamente todas as Issues e Sub-issues de Formações futuras.

Atividades pequenas e inseparáveis permanecerão como checklist. Uma tarefa operacional receberá Issue própria somente quando possuir entrega independente, responsável, prazo, bloqueio, critérios de aceitação ou rastreabilidade próprios, ou quando afetar vários Módulos ou Aulas.

Cada Módulo e cada Aula terão um único registro operacional principal. Planejamento, pesquisa, produção, revisão e publicação não gerarão registros paralelos para o mesmo elemento.

### 4. Estados e transições

Os estados operacionais serão:

- `Backlog`: trabalho futuro ainda não liberado ou sem condições de início;
- `Todo`: item definido, priorizado e liberado, mas ainda sem trabalho ativo;
- `In Progress`: trabalho efetivamente iniciado e verificável;
- `Done`: entrega concluída com critérios, aprovações, registros e sincronização atendidos;
- `Canceled`: uso excepcional mediante decisão explícita, justificativa e autorização aplicável;
- `Duplicate`: uso excepcional quando outro registro canônico representar o mesmo trabalho.

`Blocked` não será um estado principal. O bloqueio será registrado por relação `blockedBy`, motivo, condição de desbloqueio e identificação visual quando aplicável.

Os estados pedagógicos, como planejado, em pesquisa, em produção, em revisão, aprovado, publicado e bloqueado, não substituirão os estados operacionais do Linear. A situação pedagógica permanecerá canônica nos registros aplicáveis do GitHub.

Transições principais:

- `Backlog → Todo`: escopo, critérios, dependências e autorização atendidos;
- `Todo → In Progress`: trabalho efetivamente iniciado e sem bloqueio impeditivo desconhecido;
- `In Progress → Done`: entrega, critérios, revisões, aprovações, registros oficiais e sincronização concluídos;
- `Done → Todo` ou `In Progress`: somente com erro ou trabalho adicional concreto, justificativa, novo escopo, autorização e histórico preservado.

Não se utilizará `In Progress` apenas para indicar prioridade, nem `Done` apenas porque um texto foi produzido.

### 5. Prioridades

As prioridades representarão urgência, impacto operacional e bloqueio, sem substituir estado ou ordem pedagógica:

- `Urgent`: risco ou incidente imediato, divergência crítica, segurança, perda de dados, publicação incorreta ou bloqueio que não possa aguardar;
- `High`: bloqueio da etapa atual, impacto amplo, prazo externo relevante ou falha que impeça critérios de aceitação;
- `Medium`: prioridade padrão para decisões, Módulos, Aulas, pesquisas, revisões e tarefas operacionais normais;
- `Low`: melhoria opcional, pesquisa futura ou trabalho adiável sem perda estrutural;
- `No Priority`: uso temporário para entrada ainda não triada ou sem escopo suficiente.

Um item não avançará para `Todo` ou `In Progress` sem avaliação de prioridade.

A prioridade não autoriza iniciar trabalho, não remove dependências, não altera a sequência pedagógica e não permite ignorar a ordem DEC-01 a DEC-10.

### 6. Dependências, bloqueios e relações

As relações serão objetivas e mínimas:

- `parent` e `sub-issue`: hierarquia pedagógica;
- `blockedBy` e `blocks`: dependência obrigatória real;
- `relatedTo`: vínculo contextual sem impedir avanço independente;
- `duplicateOf`: identificação do registro canônico quando dois registros representarem o mesmo trabalho.

A sequência pedagógica normal não produzirá automaticamente bloqueios entre todas as Aulas e Módulos. `blockedBy` será usado somente quando existir pré-requisito pedagógico ou dependência operacional real.

Uma Issue bloqueada deverá identificar a Issue bloqueadora, o motivo, a condição de desbloqueio, o impacto e a origem da resolução quando aplicável.

Não será criada Issue apenas para condição vaga, espera informal ou observação. A condição deverá possuir trabalho concreto, entrega verificável, origem identificável e critérios próprios para justificar um registro separado.

Dependências circulares são proibidas. Ao identificá-las, o avanço deverá parar até revisão do escopo e correção das relações.

Não será permitido concluir item com bloqueio obrigatório pendente.

### 7. Critérios objetivos de conclusão

Nenhuma Issue, Sub-issue ou Milestone será concluída apenas porque o texto foi produzido ou porque não existe trabalho ativo.

A conclusão exigirá critérios previamente definidos, entrega verificável, revisão aplicável, aprovações obrigatórias, bloqueios resolvidos, fonte canônica atualizada, evidência registrada e sincronização entre GitHub e Linear.

#### Aula — Sub-issue

Uma Aula poderá ser movida para `Done` quando seu objetivo de aprendizagem e critérios estiverem atendidos, o conteúdo canônico estiver no local correto, recursos obrigatórios tiverem sido incluídos, revisões e fontes estiverem validadas, a aprovação exigida estiver registrada e não houver bloqueio obrigatório.

`Done` não significa automaticamente publicação.

#### Módulo — Issue

Um Módulo poderá ser concluído quando todas as Aulas obrigatórias estiverem em `Done`, os critérios próprios do Módulo forem atendidos, sequência, pré-requisitos, resultados e índice aplicável estiverem atualizados, e não houver bloqueios.

A conclusão das Sub-issues não concluirá automaticamente a Issue do Módulo.

#### Formação — Milestone

Uma Formação poderá ser concluída quando Módulos e Aulas obrigatórios estiverem em `Done`, objetivos, progressão, resultados, currículo e índices estiverem validados, pendências resolvidas, revisão global e aprovação concluídas, e GitHub e Linear sincronizados.

A conclusão da Milestone não significará publicação.

#### Manual — Project

O Project principal não será concluído por uma única Formação. Seu encerramento dependerá do escopo oficial da versão, das Formações previstas, da publicação aplicável e de decisão específica de encerramento.

#### Tarefa operacional

Uma tarefa operacional será concluída quando sua entrega independente, critérios, evidências, bloqueios, registros afetados e aprovações aplicáveis estiverem atendidos.

A conclusão de um nível inferior não concluirá automaticamente o nível superior. Reabertura exigirá erro ou trabalho adicional concreto, justificativa, novo escopo, autorização e histórico preservado.

### 8. Separação entre GitHub e Linear

O GitHub armazenará o conteúdo canônico e a memória permanente, incluindo currículo, objetivos completos, conteúdos, explicações, exemplos, exercícios, fontes, recursos, histórico e versões aprovadas.

O Linear armazenará controle operacional: identificador, título, resumo, estado, prioridade, responsável, Milestone, hierarquia, dependências, bloqueios, critérios, checklist, prazo, evidências, aprovações e links para a fonte canônica.

A descrição da Issue deverá ser suficiente para executar e verificar o trabalho, mas não substituirá o documento pedagógico.

Quando o arquivo canônico ainda não existir, a Issue poderá registrar `Fonte canônica ainda não criada — conteúdo em planejamento.` Isso não autoriza arquivos vazios ou placeholders.

Comentários servirão para evidências, revisões, justificativas, bloqueios e aprovações operacionais. Não armazenarão conteúdo pedagógico completo nem decisões permanentes isoladas.

Checklists representarão passos de execução e não substituirão a estrutura pedagógica ou os critérios de aceitação.

Quando houver divergência entre GitHub e Linear, o avanço será interrompido até identificação da fonte canônica, preparação da correção, autorização aplicável e nova verificação de sincronização.

### 9. Controle de volume, duplicidade e rastreabilidade

Uma Issue operacional somente será criada quando existir trabalho concreto, entrega independente, necessidade de estado e critérios próprios, origem identificável e necessidade real de rastreabilidade separada.

Antes de criar Issue ou Sub-issue será obrigatório:

1. pesquisar o identificador;
2. pesquisar título e termos equivalentes;
3. verificar Milestone e Issue pai;
4. consultar registros concluídos, cancelados e duplicados;
5. confirmar que não existe registro canônico;
6. definir onde ficará o resultado permanente;
7. confirmar a autorização aplicável.

Serão criados apenas registros necessários para o trabalho atual ou para o próximo trabalho já liberado. Não serão criados registros vazios, todas as estruturas futuras antecipadamente, Issues por fase ou tarefas genéricas sem entrega.

Cada elemento terá uma unidade operacional canônica: uma Issue por Módulo, uma Sub-issue por Aula e uma Issue por tarefa operacional independente.

Toda Issue deverá permitir identificar entrega, elemento pedagógico, fonte canônica, estado, prioridade, critérios, dependências, evidência e elemento superior afetado.

Labels somente serão usadas para classificações transversais recorrentes não cobertas por estado, prioridade, Milestone, hierarquia, dependência ou identificador. Não duplicarão estados, prioridades, níveis pedagógicos, Milestones ou responsáveis.

A estrutura será revisada antes de nova Formação, antes da conclusão de Milestone, diante de duplicidade, falta de avanço, divergência ou dificuldade de localizar o item atual.

A revisão identificará duplicidades, ausência de critérios, vínculos incorretos, itens em `In Progress` sem trabalho ativo, bloqueios sem causa, links inválidos e registros futuros prematuros.

Registros inadequados poderão ser corrigidos, vinculados, devolvidos ao Backlog, marcados como Duplicate, cancelados mediante autorização, incorporados ao registro canônico ou preservados como histórico. Não haverá exclusão silenciosa.

### 10. Resultado do registro

- As escolhas 1A a 9A foram aprovadas e registradas.
- Nenhuma Milestone de Formação, Issue de Módulo, Sub-issue de Aula, label ou estado novo foi criado.
- Nenhum diretório pedagógico, placeholder ou arquivo vazio foi criado.
- A LEA-109 foi concluída.
- A LEA-110 permaneceu no Backlog e não foi iniciada durante o registro da DEC-06.
- GitHub e Linear foram sincronizados.

## DEC-07 — Padrão editorial das aulas

- **Status:** aprovada, registrada e concluída
- **Data de início:** 2026-07-22
- **Data de aprovação:** 2026-07-23
- **Data de registro:** 2026-07-23
- **Data de conclusão:** 2026-07-23
- **Linear:** LEA-110 — concluída
- **Escolhas aprovadas:** 1A, 2A, 3A, 4A, 5A, 6A, 7A, 8A e 9A

### 1. Núcleo editorial obrigatório — escolha 1A

Toda Aula deverá possuir oito seções obrigatórias:

1. **Identificação da Aula**;
2. **Objetivo de aprendizagem**;
3. **Pré-requisitos**;
4. **Introdução e contextualização**;
5. **Desenvolvimento**;
6. **Síntese**;
7. **Verificação de aprendizagem**;
8. **Fontes e atualização**.

A identificação deverá registrar, conforme o estado da Aula, identificador, título, Formação, Módulo, versão, estado pedagógico e metadados editoriais aplicáveis.

O objetivo deverá declarar resultado observável e verificável, com verbo adequado à competência esperada. A Aula desenvolverá um objetivo específico ou um conjunto pequeno e coerente de objetivos relacionados.

Os pré-requisitos deverão ser informados de maneira explícita. Quando não houver pré-requisito, isso deverá ser declarado. Não serão cobrados conhecimentos ocultos.

A introdução deverá situar o tema, explicar sua utilidade e relacioná-lo à progressão da Formação, sem antecipar desnecessariamente conteúdos futuros.

O desenvolvimento conterá a explicação principal, exemplos, procedimentos, limitações e demais recursos necessários para atingir o objetivo.

A síntese consolidará os pontos essenciais sem substituir o desenvolvimento nem fornecer resposta pronta para todas as atividades.

A verificação exigirá evidência observável de que o objetivo foi atingido.

A seção “Fontes e atualização” manterá referências, contexto, datas de verificação, informações sujeitas a mudança, limitações e pontos de revisão.

Nenhuma seção obrigatória poderá permanecer vazia, ser substituída apenas por marcador provisório ou ser removida sem nova decisão aplicável.

### 2. Catálogo controlado de seções opcionais — escolha 2A

Seções opcionais somente serão incluídas quando possuírem função pedagógica ou operacional identificável. Não serão usadas para preencher espaço, repetir conteúdo ou criar um modelo rígido maior que o necessário.

O catálogo autorizado inclui, conforme o objetivo e o conteúdo:

- visão geral ou mapa da Aula;
- conceitos-chave;
- glossário;
- analogia identificada;
- exemplo guiado;
- demonstração;
- cenário real, adaptado, simulado, hipotético ou fictício;
- passo a passo;
- checklist;
- tabela comparativa;
- diagrama ou recurso visual;
- aviso, cuidado, limitação ou risco;
- erro comum e correção;
- prática orientada;
- atividade complementar;
- aprofundamento;
- perguntas frequentes;
- recursos complementares;
- histórico resumido de alterações relevante ao estudante.

A seção opcional deverá:

- estar relacionada ao objetivo;
- possuir título descritivo;
- aparecer no ponto em que produza melhor compreensão;
- informar contexto e limitações quando necessários;
- ser removida quando não acrescentar valor verificável.

Uma seção opcional não poderá substituir objetivo, pré-requisitos, síntese, verificação ou fontes. Também não poderá introduzir conteúdo que exija uma nova Aula sem aplicar os critérios de divisão.

### 3. Ordem editorial — escolha 3A

A ordem principal será:

```text
Identificação
→ Objetivo de aprendizagem
→ Pré-requisitos
→ Introdução e contextualização
→ Desenvolvimento
→ Síntese
→ Verificação de aprendizagem
→ Fontes e atualização
```

Essa ordem preservará a previsibilidade do Manual. Seções opcionais poderão ser inseridas no ponto de maior utilidade, sem alterar a função das oito seções obrigatórias.

Regras de inserção contextual:

- conceitos-chave e glossário aparecerão antes ou junto do primeiro uso relevante;
- analogias e exemplos aparecerão após a definição que ajudam a compreender;
- demonstrações, passos e checklists ficarão próximos do procedimento correspondente;
- avisos de risco ou pré-condições aparecerão antes da ação afetada;
- erros comuns e correções aparecerão depois da explicação ou do procedimento relacionado;
- aprofundamentos serão apresentados depois da compreensão básica;
- perguntas frequentes e recursos complementares não interromperão a sequência principal;
- o gabarito ou a rubrica ficará visualmente separado da atividade.

Alterações excepcionais da ordem deverão ser justificadas pela necessidade pedagógica e verificadas na revisão.

### 4. Tamanho e critérios de divisão — escolha 4A

O tamanho será flexível e orientado pelo objetivo, pela complexidade e pela carga cognitiva. Não haverá limite universal de palavras, páginas ou minutos que, isoladamente, determine a qualidade ou a necessidade de divisão.

Faixas de tamanho poderão ser usadas como referência editorial, nunca como obrigação automática. A Aula deverá ser tão curta quanto possível e tão completa quanto necessário para cumprir seu objetivo, seus exemplos, sua prática e sua verificação.

Uma Aula deverá ser dividida quando ocorrer uma ou mais destas condições:

- existência de objetivos independentes ou pouco coerentes entre si;
- mudança relevante de tema, competência ou tipo de tarefa;
- quantidade excessiva de conceitos novos;
- necessidade de pré-requisito que ainda não foi desenvolvido;
- procedimento extenso com etapas que formam competências autônomas;
- impossibilidade de verificar adequadamente todo o objetivo em uma única Aula;
- síntese excessivamente ampla ou incapaz de representar o conteúdo;
- exemplos, práticas ou fontes com contextos e ciclos de atualização muito diferentes;
- possibilidade de uma parte funcionar como unidade pedagógica independente;
- dificuldade de consulta, manutenção, revisão ou atualização causada pelo volume.

A divisão não deverá fragmentar artificialmente um procedimento curto, separar explicação de prática indispensável ou criar Aulas sem objetivo próprio.

### 5. Explicações, analogias e exemplos — escolha 5A

As explicações seguirão progressão em camadas:

1. definição direta;
2. desenvolvimento conceitual;
3. aplicação.

O texto deverá ser compreensível ao público definido na DEC-01, avançar do simples para o complexo, evitar pré-requisitos não declarados e preservar a precisão técnica.

A linguagem será em português do Brasil, com palavras comuns e precisas. Termos técnicos, abreviações e expressões em inglês serão definidos na primeira ocorrência relevante. Termos oficiais ou de uso consolidado poderão ser preservados em inglês com explicação em português.

Analogia será opcional. Quando utilizada, deverá ser identificada como comparação, preservar a relação essencial, declarar seus limites e ser seguida da explicação técnica. Não poderá substituir fatos, funcionar como prova, criar equivalência falsa, ocultar exceções, infantilizar o público ou confundir o conceito.

Todo exemplo deverá possuir finalidade identificável e, conforme aplicável, informar conceito, contexto, dados, ação, resultado e limitações. Será classificado como:

- real e verificável;
- real adaptado;
- simulado;
- hipotético;
- fictício.

Exemplos simulados ou fictícios não serão apresentados como comportamento real do ChatGPT.

Exemplos dependentes de plano, recurso, interface, região, dispositivo, modelo, limite, configuração, política ou comportamento atual deverão ser verificados em fonte oficial vigente. Variações relevantes deverão indicar contexto, data e possibilidade de mudança.

Prompts serão identificados como demonstração, reutilizáveis ou completos. Não deverão prometer resultados determinísticos.

Procedimentos deverão informar ponto de partida, pré-condições, passos numerados, resultado esperado, forma de verificação, variações, limitações e erros previsíveis. Não serão inventados botões, menus, mensagens, limites ou comportamentos.

### 6. Verificação de aprendizagem — escolha 6A

Toda Aula possuirá pelo menos um mecanismo de verificação alinhado ao objetivo declarado. Não bastará perguntar se o estudante entendeu; será exigida resposta, decisão, classificação, explicação, configuração, execução, avaliação ou produção observável.

O formato acompanhará o verbo do objetivo. Poderão ser usadas perguntas objetivas ou abertas, análise de cenário, exercício de aplicação, atividade prática, produção de artefato e checklist de domínio.

Toda verificação deverá possuir:

- instrução clara;
- cobertura suficiente do objetivo;
- resposta esperada, gabarito, checklist ou rubrica;
- critérios de conclusão;
- feedback ou explicação da solução.

Uma única pergunta somente será suficiente quando produzir evidência de todo o objetivo. Objetivos com vários componentes deverão ter todos os componentes verificados.

Objetivos práticos, como configurar, criar, produzir, executar, testar, comparar resultados ou corrigir, exigirão evidência prática. Uma questão teórica isolada não comprovará competência prática.

Questões objetivas terão alternativa correta e justificativa; alternativas incorretas representarão erros plausíveis. Questões abertas indicarão profundidade, conceitos obrigatórios e critérios. Cenários informarão contexto, problema, dados, restrições, solicitação e classificação do cenário. Atividades práticas informarão recursos, ponto de partida, resultado esperado, evidência e conferência.

O gabarito ficará visualmente separado da atividade. O estudante poderá comparar, revisar, corrigir e repetir quando aplicável. Não haverá porcentagem universal obrigatória; o critério dependerá da natureza do objetivo.

Avaliações auxiliadas por IA terão critérios explícitos, admitirão revisão e não tratarão a IA como infalível. A participação da IA será informada quando relevante.

São proibidas pegadinhas, conteúdo não ensinado, ambiguidade, exposição da resposta na pergunta, avaliação apenas por quantidade de texto, exigência de ferramenta não informada, inferência de competência prática apenas por teoria e atividade sem gabarito, rubrica ou critério.

### 7. Fontes, referências e rastreabilidade — escolha 7A

Toda informação factual relevante deverá possuir origem identificável e verificável. A intensidade da citação será proporcional à possibilidade de mudança, importância, risco, impacto de erro, divergência, necessidade de auditoria e sensibilidade.

A hierarquia será:

1. fontes canônicas do projeto;
2. fontes oficiais da OpenAI;
3. fontes primárias externas;
4. fontes secundárias qualificadas;
5. fontes comunitárias e relatos, apenas como apoio e não como prova oficial isolada.

Afirmações críticas, variáveis ou controversas terão referência próxima e data de verificação. Conceitos estáveis poderão usar referência por parágrafo, subseção ou conjunto coerente, desde que a relação permaneça clara.

A produção distinguirá informação estável, variável, incerta e contextual. Quando o comportamento variar, serão registrados, conforme aplicável, plano, região, dispositivo, sistema operacional, versão, modelo, tipo de conta, configuração e data.

A Aula utilizará notas ou referências em Markdown próximas das afirmações relevantes e manterá registro completo na seção “Fontes e atualização”, incluindo autor ou organização, título, endereço ou identificador, datas, versão, seção relevante, idioma e contexto.

Procedimentos serão fundamentados em documentação oficial, teste controlado identificado ou combinação dos dois. Testes registrarão data, ambiente, plano, dispositivo, versão, configuração, resultado e limitações, sem generalização automática.

Conflitos entre fontes serão declarados. Deverão ser comparados data, escopo, versão e contexto, priorizando a fonte primária mais específica e atual sem ocultar incerteza.

Uma resposta de IA não será fonte primária nem prova factual. Citações respeitarão direitos autorais, licenças e limites de reprodução. Código, prompts e exemplos externos indicarão reprodução ou adaptação, fonte, licença e modificações.

A seção “Fontes e atualização” apresentará referências utilizadas, data da última verificação factual, informações sujeitas a mudança, contexto, limitações, divergências e pontos de revisão futura. Não será apenas uma lista de links.

É proibido inventar referência, citar fonte não consultada, atribuir à fonte afirmação inexistente, ocultar conflito, usar fonte comunitária como prova oficial, tratar IA como comprovação, preencher bibliografia artificialmente ou conservar informação variável como permanentemente válida sem nova verificação.

### 8. Revisão em camadas — escolha 8A

Nenhuma Aula será considerada pronta apenas porque o texto foi concluído. A revisão será obrigatória e proporcional ao risco, à variabilidade, à complexidade e ao impacto do conteúdo.

As camadas serão:

1. revisão de autoria;
2. revisão pedagógica;
3. revisão factual;
4. revisão técnica e funcional;
5. revisão editorial e linguística;
6. revisão de acessibilidade e apresentação;
7. revisão de segurança, privacidade e conformidade;
8. revisão final de integridade.

A revisão de autoria verificará seções obrigatórias, objetivo, pré-requisitos, conclusão do texto e ausência de marcadores provisórios.

A revisão pedagógica verificará alinhamento entre objetivo, explicação e atividade, progressão, adequação ao público, carga cognitiva, necessidade de divisão, exemplos, práticas, gabaritos e pré-requisitos.

A revisão factual confirmará fidelidade e atualidade das fontes, datas, versões, planos, regiões, modelos, limites, políticas, nomes de recursos, exemplos reais e distinção entre fato, observação e inferência.

A revisão técnica será obrigatória para procedimentos, configurações, código, comandos, prompts, ferramentas, integrações e interfaces. Testes registrarão ambiente e limitações.

A revisão editorial verificará português do Brasil, clareza, consistência terminológica, títulos, parágrafos, abreviações, termos técnicos, nomes oficiais e separação entre definição, regra, exemplo e exceção.

A revisão de acessibilidade verificará títulos, listas, tabelas, texto alternativo, descrição de diagramas, contraste, ordem de leitura e copiabilidade de código e prompts.

A revisão de segurança, privacidade e conformidade será proporcional e observará dados, credenciais, permissões, ações irreversíveis, saúde, finanças, aspectos jurídicos, direitos autorais, menores e conteúdos perigosos.

Achados serão classificados como:

- **crítico:** bloqueia aprovação e publicação;
- **maior:** bloqueia aprovação até correção;
- **menor:** deverá ser corrigido ou justificadamente registrado;
- **sugestão:** melhoria não bloqueante.

Cada achado informará seção, descrição, classificação, evidência, correção esperada, resultado da nova verificação e situação final.

A Aula somente seguirá para aprovação sem achado crítico ou maior aberto, com fatos atuais, procedimentos validados, objetivo coberto, verificação utilizável, fontes completas e evidências registradas.

Quando possível, haverá revisão independente, especialmente em conteúdo de alto risco ou tecnicamente complexo. A IA poderá auxiliar, mas não inventará evidência, declarará teste não executado ou substituirá aprovação humana.

Alterações posteriores receberão nova revisão proporcional: editorial localizada, factual, pedagógica, técnica ou completa, conforme o impacto. Não será publicada versão materialmente diferente da revisada.

### 9. Datas, versionamento e atualização — escolha 9A

Toda Aula aprovada deverá permitir identificar criação, aprovação, publicação, alterações, verificações, versão, próxima revisão e mudanças entre versões.

As datas editoriais usarão ISO 8601 no formato `AAAA-MM-DD`. Evidências que exigirem horário usarão data e hora com fuso ou UTC.

Serão registrados, conforme aplicável:

- data de criação;
- data de aprovação;
- data de primeira publicação;
- data da última publicação;
- data da última alteração de conteúdo;
- data da última verificação factual;
- data da última revisão pedagógica;
- data da última revisão editorial;
- data da última validação técnica;
- próxima revisão prevista.

Uma data somente será atualizada quando a atividade correspondente tiver sido executada. Correção editorial não atualizará a verificação factual; validação técnica não será registrada sem teste.

Toda Aula aprovada possuirá versão `MAJOR.MINOR.PATCH`:

- **MAJOR:** mudança incompatível ou estrutural, como objetivo, escopo, procedimento ou competência essencial;
- **MINOR:** expansão substancial compatível com o objetivo existente;
- **PATCH:** correção localizada factual, editorial, de referência, exemplo, formatação ou acessibilidade.

Rascunhos poderão usar versões `0.x.x`. A primeira versão aprovada será normalmente `1.0.0`. Nem todo commit exigirá nova versão pedagógica; vários commits poderão compor uma única versão.

A periodicidade máxima será:

- até 30 dias para conteúdo altamente variável ou de risco elevado;
- até 90 dias para conteúdo variável, ferramentas, interfaces, APIs, SDKs e configurações;
- até 180 dias para conteúdo relativamente estável;
- até 365 dias para fundamentos e conteúdo estável.

O prazo poderá ser reduzido por risco, fonte instável, mudança anunciada ou histórico de correções.

Haverá revisão extraordinária diante de anúncio relevante, lançamento ou remoção, mudança de preço, plano, limite, interface, política, versão, erro factual, link essencial removido, procedimento quebrado, mudança em pré-requisito, risco, divergência ou atualização estrutural.

Conteúdo com revisão vencida será marcado para revisão; não será automaticamente considerado falso. Informações variáveis terão prioridade, nova publicação exigirá conferência e conteúdo de alto risco poderá ser bloqueado.

Cada versão aprovada manterá versão anterior, nova versão, data, tipo de incremento, resumo, motivo, partes afetadas, impacto, responsável ou processo e evidência de aprovação. O Git será o histórico técnico; a versão da Aula será a identificação pedagógica; o Linear controlará execução e prazos.

Não serão usadas datas fictícias, números de versão reutilizados ou reduzidos, versão publicada diferente da aprovada, PATCH para mudanças incompatíveis, commit como única identificação pública ou prazo de revisão como garantia de correção.

### 10. Resultado da conclusão

- As escolhas 1A a 9A foram aprovadas pelo usuário e registradas como padrão editorial da DEC-07.
- Todos os critérios de aceitação da LEA-110 foram validados.
- A LEA-110 foi concluída no Linear após a sincronização final entre GitHub e Linear.
- A LEA-111 permanece como próxima decisão e não foi iniciada.
- Nenhuma Aula, Formação, Módulo, Milestone pedagógica, Issue pedagógica, Sub-issue pedagógica, diretório futuro ou placeholder foi criado.
- Nenhuma publicação externa foi realizada.

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

- **Último item concluído:** LEA-110 — DEC-07: Padrão editorial das aulas.
- **Item em andamento:** nenhum.
- **Próximo item:** LEA-111 — DEC-08, ainda não iniciada e dependente do fluxo oficial de transição.

## Decisões ainda não concluídas

As decisões DEC-08 a DEC-10 permanecem pendentes e devem ser executadas sequencialmente.

## Universo Didático

A LEA-114 permanece no Backlog e bloqueada pela conclusão da LEA-103. As ideias já discutidas sobre o universo são rascunhos não canônicos e não alteram a sequência atual.
