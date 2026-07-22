# Constituição do Projeto

> **Status:** base operacional, identidade, estrutura pedagógica, níveis de autonomia e fluxo de aprovação aprovados. Estrutura documental, padrão editorial e demais pontos continuarão sendo definidos pelas DEC-05 a DEC-10.

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

A Aula pode conter explicações, exemplos, demonstrações, atividades e verificações de aprendizagem. O padrão editorial detalhado será definido posteriormente na DEC-07.

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

### 8.2 Nível 2 — Preparação em Rascunho

A ferramenta pode preparar textos, documentos, código, análises, planos, propostas de alteração, descrições de issues, mensagens, e-mails ainda não criados no Gmail, comandos, diffs, mensagens de commit e versões completas de arquivos.

Os materiais podem ser preparados na conversa ou em arquivos temporários destinados à revisão do usuário. Devem ser identificados como **RASCUNHO** quando houver risco de serem confundidos com conteúdo aprovado ou publicado.

Sem autorização explícita, a ferramenta não poderá salvar o rascunho em sistemas externos, criar ou alterar issues, criar comentários, branches, commits ou pull requests, criar rascunhos no Gmail, enviar mensagens, criar eventos, substituir arquivos oficiais ou registrar o conteúdo como decisão ou estado do projeto.

Qualquer criação ou gravação em sistema externo pertence ao Nível 3.

### 8.3 Nível 3 — Execução Controlada

Qualquer ação que altere um sistema externo ou o estado oficial do projeto exige autorização do usuário.

O Nível 3 possui duas categorias internas, sem criar novos níveis oficiais.

#### Execução Controlada Padrão

Abrange alterações externas normalmente reversíveis, internas ou privadas, de alcance limitado, sem dados sensíveis, sem comunicação externa e sem alteração relevante do estado oficial.

Uma solicitação direta, específica e suficientemente clara do usuário já poderá funcionar como autorização, desde que o sistema, o alvo, a ação e o resultado estejam definidos.

#### Execução Controlada Crítica

Abrange ações destrutivas, irreversíveis, públicas, comunicacionais, sensíveis ou com impacto relevante sobre o estado oficial.

Inclui, conforme o contexto:

- enviar e-mails ou mensagens;
- publicar conteúdo;
- realizar commits ou merges;
- sobrescrever arquivos oficiais;
- excluir arquivos ou registros;
- fechar ou cancelar tarefas;
- alterar roadmap;
- mudar permissões;
- modificar dados sensíveis;
- executar ações em massa.

Antes da execução, a ferramenta deve apresentar uma confirmação prévia com o sistema afetado, o alvo, a ação, o efeito esperado, o alcance, a possibilidade de reversão e os riscos relevantes. A execução somente poderá ocorrer depois de confirmação explícita do usuário sobre esse resumo.

### 8.4 Alcance e validade das autorizações

A autorização será específica, delimitada e consumível. Ela será válida somente para a ação ou para o conjunto de ações claramente descrito e diretamente relacionado ao objetivo atual.

Uma única autorização poderá abranger várias ações quando estiverem claramente definidos:

- o sistema afetado;
- os alvos;
- as ações;
- o resultado esperado;
- os limites da execução.

A autorização será encerrada quando as ações forem concluídas, o usuário cancelar a execução, houver mudança relevante de alvo, conteúdo, quantidade ou efeito, ou surgir condição diferente da apresentada.

A autorização não se estende automaticamente a ações futuras semelhantes. Nas execuções críticas, qualquer mudança relevante de escopo exige nova autorização.

Autorizações permanentes somente poderão existir quando forem aprovadas como regra oficial do projeto.

### 8.5 Classificação pelo contexto e efeito real

A classificação será determinada pelo contexto e pelo efeito real da execução, e não apenas pelo nome da ação ou pela ferramenta utilizada.

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

### 8.6 Relação com a DEC-04

A DEC-03 define os níveis de autonomia, a classificação de risco e a necessidade de autorização. A DEC-04 define os comandos canônicos, os resumos de confirmação e os fluxos de aprovação, registro, publicação, conclusão e transição, sem permitir que esses comandos contornem a classificação de risco.

## 9. Fluxo e comandos de aprovação

### 9.1 Modelo híbrido

Solicitações em linguagem natural, quando diretas, específicas e inequívocas, poderão produzir o mesmo efeito dos comandos canônicos. Mensagens ambíguas não serão tratadas como aprovação ou autorização.

Os comandos oficiais serão escritos em português do Brasil, entre colchetes, em letras maiúsculas e no formato `AÇÃO + OBJETO`.

### 9.2 Aprovação

Comandos:

```text
[APROVAR CONTEÚDO]
[APROVAR DECISÃO]
[APROVAR ENTREGA]
```

A aprovação confirma a versão aceita, encerra sua revisão e permite preparar os registros finais. A aprovação isoladamente não autoriza commits, atualizações em documentos oficiais, alterações no Linear, publicação, conclusão ou avanço.

### 9.3 Correção e reabertura

```text
[SOLICITAR CORREÇÕES]
[REABRIR ESCOLHA]
```

`[SOLICITAR CORREÇÕES]` autoriza preparar uma nova versão de material em revisão, sem alterar sistemas externos.

`[REABRIR ESCOLHA]` suspende provisoriamente apenas a escolha identificada dentro da decisão atual, preserva as demais escolhas e exige nova resposta antes da consolidação final. Decisões já concluídas e registradas não podem ser sobrescritas por esse comando.

### 9.4 Registro oficial

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

A autorização abrange somente as ações enumeradas no resumo imediatamente anterior ou explicitamente identificado. Não autoriza publicação, exclusões não descritas, ampliação de escopo, início da próxima decisão ou reutilização futura.

### 9.5 Publicação e execução crítica

```text
[AUTORIZAR PUBLICAÇÃO]
[AUTORIZAR EXECUÇÃO CRÍTICA]
```

`[AUTORIZAR PUBLICAÇÃO]` aplica-se somente a uma versão já aprovada e ao canal, público, alcance e momento descritos no resumo.

`[AUTORIZAR EXECUÇÃO CRÍTICA]` aplica-se a ações críticas diferentes de publicação, incluindo exclusão, sobrescrita, merge, envio, alteração de permissões, tratamento de dados sensíveis e operações em massa.

Sem resumo válido, esses comandos iniciam apenas a preparação da confirmação. Qualquer mudança relevante exige novo resumo e nova autorização.

### 9.6 Conclusão da etapa

```text
[CONCLUIR ETAPA]
```

Esse comando solicita validação final e não conclui automaticamente o item.

A declaração `ETAPA CONCLUÍDA` somente poderá ocorrer depois de verificar:

- aprovação da versão final;
- conclusão das escolhas necessárias;
- ausência de correções ou escolhas reabertas;
- atendimento dos critérios de aceitação;
- atualização dos documentos aplicáveis;
- atualização do Linear;
- evidências disponíveis;
- sincronização entre GitHub e Linear;
- próximo item confirmado, mas não iniciado.

### 9.7 Início da próxima decisão

```text
[INICIAR PRÓXIMA DECISÃO]
```

Esse comando solicita a preparação e a validação da transição. Somente poderá ser reconhecido depois que a etapa anterior tiver sido declarada `ETAPA CONCLUÍDA`.

Antes da execução, o ChatGPT deve reconstruir o contexto oficial, confirmar a sincronização, verificar que nenhum item estrutural permanece em andamento, identificar a próxima decisão obrigatória, verificar bloqueios e apresentar o resumo da transição.

A alteração do estado oficial depende de nova autorização por meio de `[AUTORIZAR REGISTRO OFICIAL]`. O comando não pode ignorar decisões intermediárias, iniciar uma issue fora da sequência, reutilizar autorização anterior ou iniciar duas decisões simultaneamente.

## 10. Alteração desta Constituição

Esta Constituição somente poderá ser alterada por decisão ou tarefa operacional registrada no Linear, autorização correspondente e atualização sincronizada no GitHub.
