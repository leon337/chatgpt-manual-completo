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

- **Último item concluído:** LEA-107 — DEC-04: Fluxo e comandos de aprovação.
- **Item em andamento:** LEA-108 — DEC-05: Estrutura e responsabilidades do GitHub.
- **Próximo item:** LEA-109 — DEC-06, somente após a conclusão, o registro e a sincronização da DEC-05.

## Decisões ainda não concluídas

A DEC-05 está em andamento. Nenhuma escolha estrutural da DEC-05 foi aprovada até o momento.

As decisões DEC-06 a DEC-10 permanecem pendentes e devem ser executadas sequencialmente.

## Universo Didático

A LEA-114 permanece no Backlog e bloqueada pela conclusão da LEA-103. As ideias já discutidas sobre o universo são rascunhos não canônicos e não alteram a sequência atual.
