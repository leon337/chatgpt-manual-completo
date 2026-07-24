# Catálogo de Skills

> **Status:** DEC-08 / LEA-111 aprovada, registrada, validada e sincronizada. As definições e o catálogo abaixo constituem a versão oficial concluída. A aprovação não ativa automaticamente as Skills.

## 1. Conceito oficial

Uma Skill é um procedimento operacional aprovado e reutilizável que transforma um gatilho reconhecido em um resultado verificável, mediante finalidade, escopo, pré-condições, fontes, etapas, restrições e critérios de validação declarados.

Uma Skill:

- não substitui decisões oficiais;
- não funciona como memória da conversa;
- não é um comando;
- não é uma ferramenta;
- não cria autorização;
- pode coordenar ferramentas somente dentro dos níveis de autonomia e das autorizações aplicáveis;
- não pode prevalecer sobre regras superiores do projeto.

## 2. Autoridade e limites

A autoridade de toda Skill permanece subordinada:

1. à Constituição do Projeto;
2. às decisões aprovadas;
3. aos níveis de autonomia da DEC-03;
4. ao fluxo e aos comandos da DEC-04;
5. às fontes canônicas e ao estado oficial sincronizado;
6. às autorizações específicas aplicáveis.

Uma Skill pode:

- executar consultas de Nível 1;
- preparar materiais de Nível 2;
- coordenar ferramentas autorizadas;
- executar ações de Nível 3 somente após a autorização exigida;
- interromper o procedimento quando faltar decisão, fonte, pré-condição, evidência ou autorização.

Uma Skill não pode:

- criar ou modificar regras superiores;
- aprovar o próprio resultado;
- conceder autorização a si mesma;
- transformar aprovação em publicação;
- modificar o estado oficial sem autorização;
- concluir, cancelar ou excluir tarefas por inferência;
- alterar roadmap, iniciar decisão posterior ou contornar bloqueios e sequência.

## 3. Estrutura obrigatória

Toda Skill deve possuir:

1. identificador;
2. nome;
3. status e versão;
4. finalidade;
5. escopo e exclusões;
6. gatilhos de ativação;
7. pré-condições;
8. entradas obrigatórias;
9. fontes obrigatórias;
10. procedimento;
11. limites de autoridade e restrições;
12. resultado esperado;
13. método de validação;
14. condições de interrupção.

Quando aplicável, deve também declarar:

- ferramentas utilizadas;
- permissões e autorizações;
- riscos;
- tratamento de erros e exceções;
- evidências produzidas;
- reversibilidade;
- comandos disponíveis;
- periodicidade de revisão;
- histórico de alterações.

## 4. Identificação e nomenclatura

O padrão oficial será:

```text
SKILL-001 — Planejar Formação
```

Regras:

- prefixo fixo `SKILL`;
- numeração global sequencial com três dígitos;
- identificador único;
- nome em português do Brasil;
- nome preferencialmente iniciado por verbo no infinitivo;
- título curto, específico e orientado ao resultado;
- identificadores provisórios podem ser reorganizados antes da aprovação inicial;
- depois do registro, o identificador torna-se permanente;
- identificadores descontinuados não são reutilizados;
- alteração de nome não altera o identificador;
- versão, categoria, ferramenta e status não são codificados no identificador.

## 5. Ativação e pré-condições

A ativação será híbrida e poderá ocorrer por:

- comando canônico específico;
- solicitação em linguagem natural clara e inequívoca;
- reconhecimento automático de correspondência exata entre o pedido e a finalidade da Skill.

Antes da execução, o ChatGPT deve:

1. identificar a Skill aplicável;
2. confirmar que o pedido está dentro do escopo;
3. verificar entradas e pré-condições;
4. consultar as fontes obrigatórias;
5. verificar bloqueios, permissões e autorizações;
6. informar a Skill utilizada quando isso for relevante;
7. interromper ou solicitar esclarecimento diante de ambiguidade.

A presença isolada de uma palavra-chave não ativa uma Skill. Múltiplas Skills não podem ser executadas silenciosamente em conjunto.

## 6. Fontes obrigatórias

Toda Skill deve respeitar a hierarquia geral do projeto e declarar suas fontes específicas.

Hierarquia geral:

1. `docs/CONSTITUICAO_DO_PROJETO.md`;
2. `PROJECT_STATE.md`;
3. `docs/DECISOES.md`;
4. `docs/SKILLS.md`;
5. `ROADMAP.md`;
6. Linear;
7. conversa atual.

Regras:

- fontes superiores não podem ser ignoradas;
- fontes complementares não substituem fontes canônicas;
- divergências interrompem o avanço;
- informações variáveis exigem nova verificação;
- ausência de fonte obrigatória bloqueia a etapa dependente;
- inferências devem ser identificadas;
- lacunas não podem ser preenchidas com dados inventados.

## 7. Procedimento operacional

O procedimento deve ser sequencial, numerado e verificável:

1. reconhecer o gatilho;
2. confirmar escopo e objetivo;
3. verificar pré-condições e entradas;
4. reconstruir o contexto aplicável;
5. consultar as fontes obrigatórias;
6. identificar riscos, bloqueios e autorizações;
7. executar somente as ações permitidas;
8. validar o resultado;
9. registrar evidências quando aplicável;
10. informar conclusão, pendências ou interrupção.

O procedimento pode conter condições, desvios, pontos de parada, tratamento de erros, chamadas explícitas a outras Skills e solicitações de autorização.

Cada etapa deve produzir resultado observável. A Skill termina somente com resultado validado, interrupção justificada ou pendência claramente identificada.

## 8. Validação e evidências

Toda Skill deve definir previamente:

- resultado esperado;
- critérios objetivos de sucesso;
- método de verificação;
- evidências exigidas;
- condições que impedem a conclusão;
- tratamento de resultados parciais ou inconclusivos.

A validação ocorre depois da execução e antes da declaração de sucesso.

Regras:

- a evidência deve ser proporcional ao risco e ao impacto;
- afirmação do ChatGPT não comprova execução externa;
- resultado parcial não pode ser apresentado como conclusão integral;
- ação sem confirmação deve ser classificada como não verificada;
- falhas de ferramenta devem ser informadas;
- alterações em GitHub e Linear exigem verificação de sincronização;
- concluir uma Skill não equivale a aprovar, publicar ou concluir uma etapa estrutural.

## 9. Erros, interrupções e retomadas

Estados possíveis:

- concluída;
- concluída parcialmente;
- interrompida;
- bloqueada;
- aguardando informação;
- aguardando autorização;
- falha não recuperável.

Quando houver falha, a Skill deve informar:

- etapa em que parou;
- ações realizadas e não realizadas;
- resultados e evidências preservados;
- erro ou bloqueio encontrado;
- risco de continuar;
- requisito e próxima ação segura para retomada.

Antes da retomada, contexto e pré-condições devem ser verificados novamente. Autorizações consumidas não podem ser reutilizadas. Ações já confirmadas não devem ser repetidas sem necessidade.

## 10. Ciclo de vida e versionamento

Estados oficiais:

1. Proposta;
2. Em elaboração;
3. Em revisão;
4. Aprovada;
5. Ativa;
6. Em atualização;
7. Suspensa;
8. Descontinuada;
9. Substituída.

Regras:

- criação exige finalidade reutilizável e ausência de duplicidade;
- aprovação não significa registro ou ativação;
- ativação exige aprovação, registro oficial e sincronização;
- versões seguem `MAJOR.MINOR.PATCH`;
- mudanças estruturais, de autoridade ou de procedimento exigem nova aprovação;
- suspensão pode ocorrer por erro, risco, fonte desatualizada ou dependência indisponível;
- descontinuação preserva identificador, versão final, histórico, motivo e substituição quando houver;
- Skills suspensas, descontinuadas ou substituídas não podem ser ativadas automaticamente.

## 11. Skill, comando, ferramenta e autorização

- **Skill:** procedimento reutilizável.
- **Comando:** expressão de intenção ou autorização do usuário.
- **Ferramenta:** capacidade técnica utilizada na execução.
- **Autorização:** permissão específica, delimitada e consumível.

Uma Skill pode utilizar várias ferramentas, e uma ferramenta pode servir a várias Skills. A existência da ferramenta não autoriza seu uso. A aprovação da Skill não cria autorização permanente.

## 12. Comandos

As Skills reutilizam os comandos gerais da DEC-04:

- `[APROVAR CONTEÚDO]`;
- `[APROVAR DECISÃO]`;
- `[APROVAR ENTREGA]`;
- `[SOLICITAR CORREÇÕES]`;
- `[REABRIR ESCOLHA]`;
- `[AUTORIZAR REGISTRO OFICIAL]`;
- `[AUTORIZAR PUBLICAÇÃO]`;
- `[AUTORIZAR EXECUÇÃO CRÍTICA]`;
- `[CONCLUIR ETAPA]`;
- `[INICIAR PRÓXIMA DECISÃO]`.

Uma Skill pode declarar comando específico somente quando houver necessidade operacional não coberta pelos comandos gerais. O comando deve seguir `AÇÃO + OBJETO`, em português do Brasil, letras maiúsculas e colchetes.

Comandos específicos podem ativar uma Skill, mas não autorizam automaticamente ações externas e não substituem pré-condições.

## 13. Critérios para criação de novas Skills

Uma nova Skill somente pode ser proposta quando houver:

1. tipo de trabalho claramente definido;
2. finalidade recorrente ou reutilizável;
3. gatilho reconhecível;
4. resultado verificável;
5. procedimento padronizável;
6. fontes e restrições identificáveis;
7. ausência de Skill existente que cubra adequadamente o trabalho;
8. benefício concreto de consistência, segurança ou eficiência;
9. compatibilidade com as decisões e a arquitetura do projeto.

Antes da criação, devem ocorrer busca de duplicidade, comparação com Skills existentes, avaliação de ampliação de Skill já existente e análise de riscos e autoridade.

Não justificam uma nova Skill: solicitação isolada, preferência de estilo, decisão estrutural, ferramenta, comando, memória ou tarefa já coberta.

## 14. Catálogo oficial inicial

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

A proposta anterior `Aprovar Conteúdo` foi removida porque aprovação é uma decisão humana expressa pelos comandos oficiais, e não uma autoridade autônoma de Skill.

## 15. Escopo resumido das Skills

### SKILL-001 — Planejar Formação

Produz plano de Formação em rascunho com público, nível, objetivos, sequência inicial de Módulos, pré-requisitos, dependências e critérios de conclusão. Não produz Aulas, não publica e não cria registros externos sem autorização.

### SKILL-002 — Planejar Módulo

Produz plano de Módulo em rascunho com posição pedagógica, resultados de aprendizagem, sequência de Aulas, fontes, dependências e critérios de conclusão. Não altera objetivos superiores nem produz integralmente as Aulas.

### SKILL-003 — Produzir Aula

Produz rascunho completo de Aula previamente planejada e autorizada, aplicando o padrão editorial da DEC-07, fontes e verificação de aprendizagem. Não aprova, publica ou substitui revisão independente.

### SKILL-004 — Revisar Aula

Executa revisão crítica e independente, classifica achados como críticos, maiores, menores ou sugestões e emite parecer verificável. Não aprova oficialmente nem altera silenciosamente o conteúdo.

### SKILL-005 — Publicar no GitHub

Executa publicação previamente aprovada e expressamente autorizada, limitada ao repositório, branch, arquivos e alcance descritos no resumo operacional válido. Exige confirmação do commit e do conteúdo publicado.

### SKILL-006 — Atualizar Linear

Atualiza o Linear de forma controlada, com alvo exato, comparação prévia com o GitHub, preservação de informações válidas, releitura do resultado e verificação de sincronização.

### SKILL-007 — Verificar Informações da OpenAI

Pesquisa e verifica informações variáveis ou tecnicamente relevantes sobre produtos, políticas, interfaces, APIs e documentação da OpenAI, priorizando fontes oficiais e distinguindo fatos, inferências e lacunas.

### SKILL-008 — Validar Conclusão de Módulo

Verifica Aulas, revisões, aprovações, resultados de aprendizagem, fontes, versões, pendências e sincronização. Pode recomendar conclusão, mas não concluir o Módulo.

### SKILL-009 — Validar Conclusão de Formação

Verifica todos os Módulos, objetivos gerais, progressão pedagógica, fontes, versões, acessibilidade, índices e sincronização. Pode recomendar conclusão, mas não concluir a Formação.

## 16. Estado após a conclusão da DEC-08

As nove Skills foram aprovadas e registradas no catálogo oficial, mas não são ativadas automaticamente por esse fato. Cada utilização continua dependente de correspondência de escopo, pré-condições, fontes, bloqueios e autorizações aplicáveis.

A conclusão formal da LEA-111 não inicia a DEC-09 automaticamente.
