# Auditoria da v1 — Mapeamento de atores do Atendimento ao Seguro-Desemprego pela URA da Caixa

- **Auditor (assistente 2):** Claude (Anthropic), via Claude.ai
- **Documento auditado:** `B_relatorio_assistente_v1.md`, produzido pelo ChatGPT (OpenAI) com Pesquisa aprofundada
- **Data da auditoria:** 24/11/2026
- **Instrução recebida:** auditoria rigorosa, apontando erros factuais, lacunas de evidência, inferências mal-suportadas, fontes fracas ou ausentes, atribuições incorretas e atores omitidos. Questões cosméticas (formatação, estilo, ordem) não foram contadas como falha.

## Método

1. Leitura integral da v1, confrontando-a com o prompt de pesquisa que a originou (seções 7 e 8 desse prompt definem o que o relatório deveria entregar).
2. Verificação pontual de fontes na web, em 24/11/2026:
   - Página de contratos do MTE (link E09): **confirma** o Contrato nº 07/2026 com a Caixa, processo 19965.202436/2025-28, vigência de 16/04/2026 a 16/04/2031, valor estimado de R$ 383.325.207,75 e objeto de operacionalização dos pagamentos do Seguro-Desemprego (modalidades Formal, Pescador Artesanal, Empregado Doméstico e Trabalhador Resgatado). Esse ponto da v1 está correto.
   - Página da plataforma Facilita (link E14): ver F02.
   - FAQ do Seguro-Desemprego da Caixa (link E04): lista o "Serviço de Atendimento ao Cidadão, pelo 0800 726 0207" entre os canais de consulta, ao lado de CAIXA Tem, Portal Cidadão, Carteira de Trabalho Digital e Portal Emprega Brasil. A existência do canal está confirmada; os horários, não (ver F06).
   - Página oficial de canais de atendimento da Caixa (link E03): não pôde ser acessada pela ferramenta de verificação. A afirmação que depende só dela fica sem confirmação independente.

**Veredito geral:** a v1 acerta o arcabouço institucional (Lei 7.998/1990, FAT, CODEFAT, MTE como gestor, Caixa como agente pagador, Dataprev no processamento) e tem um achado valioso (a discussão de 2023 sobre remuneração da URA). Mas a rastreabilidade é fraca, há classificações "Confirmada" sem evidência registrada, contradições internas e **omissões de atores que mudam o mapa** — em especial o INSS e a Auditoria-Fiscal do Trabalho, que habilitam modalidades do próprio benefício que a v1 cita. Foram identificadas **24 falhas**, numeradas de F01 a F24 para que a v2 trate cada uma.

---

## 1. Erros factuais e atribuições incorretas

**F01 — Fonte do Acórdão TCU nº 1445/2024 não corresponde ao acórdão citado.**
Trecho: *"Acórdão nº 1445/2024 — Plenário: análise de representação relacionada à licitação de solução tecnológica de contact center da Caixa."* A única fonte indicada é o Escavador (agregador privado). No registro de evidências, o item correspondente (E11) aponta para um link do TCU com o número "1424/2024", que não é o acórdão 1445. O acórdão citado não aparece no registro de evidências. Não é possível vincular a afirmação a um documento primário.

**F02 — Funcionalidade da plataforma Facilita superdimensionada.**
Trechos: *"Agendar atendimento em unidade do trabalho | Central 158 e Facilita"* e E14 *"Integração de serviços e agendamento"*. A página oficial do Facilita (verificada) confirma que a plataforma é do MTE e foi desenvolvida pela Dataprev, mas descreve a função de **acompanhar e remarcar** agendamentos; não afirma que permite **criar** um agendamento novo. A v1 atribui ao canal uma funcionalidade não demonstrada pela fonte que ela mesma cita.

**F03 — Hipótese H08 reformulada para uma versão mais fraca.**
O prompt de pesquisa dizia: *"Não está confirmado se a operação da central é própria, terceirizada ou híbrida."* A v1 transforma isso em *"H08 — A central é operada integralmente por empresa terceirizada"* e marca como inconclusiva. A pergunta real (próprio, terceirizado ou **híbrido**) não foi investigada; foi testada uma hipótese que ninguém formulou.

**F04 — Status contraditório da hipótese H05 (Dataprev).**
Na tabela de hipóteses: *"H05 … Parcialmente investigada"* — rótulo que nem pertence às classes exigidas (confirmado, parcialmente confirmado, refutado, inconclusivo). Na ficha A18: *"A participação da Dataprev … foi confirmada … Isso permite atualizar a hipótese H05"*. A tabela não foi atualizada; o mesmo relatório traz dois status para a mesma hipótese.

**F05 — Fonte de dados trabalhistas desatualizada.**
Trecho: *"A21 — CAGED e registros trabalhistas"* e *"CAGED e registros trabalhistas | Informações de origem trabalhista"*. Desde 2020 a declaração ao CAGED foi substituída, para a maior parte dos empregadores, pelo **eSocial** (o "Novo Caged" é captado via eSocial). O eSocial não aparece em nenhum ponto da v1, embora seja a origem provável das informações de vínculo e desligamento usadas na habilitação. A v1 trata como atual uma fonte que, em larga medida, é histórica — exatamente o que o critério de "Atualidade" do prompt pedia para evitar.

---

## 2. Lacunas de evidência (afirmação sem fonte)

**F06 — Horários de atendimento sem evidência.**
Trecho: *"Atendimento eletrônico: 24 horas. Atendimento humano: segunda a sexta, das 8h às 21h; sábado, das 10h às 16h."* Nenhum identificador de evidência (E-ID) sustenta esses horários. A FAQ da Caixa verificada lista o canal, mas não os horários. Como horário é justamente o tipo de dado que muda, precisa de fonte datada.

**F07 — Tabela de validação das hipóteses sem as colunas de evidência e fonte.**
O prompt exigia a estrutura *"ID | Hipótese | Resultado | Evidência | Fonte | Observações"*. A v1 entrega só *"ID | Hipótese | Resultado"*. Onze resultados ("Confirmada", "Inconclusiva" etc.) ficam sem rastreio. Não é questão de formato: sem as colunas, a validação não pode ser conferida.

**F08 — Atores marcados como "Confirmada" sem evidência registrada.**
O inventário de 34 atores não tem a coluna "Fontes" exigida. Exemplos de "Confirmada" sem qualquer evidência citada: *"A10 Rede lotérica e canais físicos … Confirmada"*, *"A34 Instituição bancária do beneficiário … Confirmada"*, *"A02 Empregador … Confirmada"*. Pode ser que estejam corretos (há fontes públicas que mencionam pagamento em lotéricas e crédito em Poupança Social Digital), mas a v1 não as apresenta.

**F09 — Citações agregadas que impedem ligar afirmação a fonte.**
Várias afirmações centrais terminam com marcadores como *"CAIXA+1"*, *"CAIXA+3"*, *"Presidência da República+3"*, *"Portal Dataprev+3"*. Não se sabe qual das fontes agregadas sustenta qual afirmação. Além disso, o registro de evidências (seção 12) omite data do documento, artigo/página/seção e data de consulta, campos exigidos pela seção 8.11 do prompt.

**F10 — Conteúdo de diagramas ausente, deixando afirmações sem suporte.**
As seções 3.2 (*"Representação simplificada das funções institucionais"*), 4 (legenda *"Canais da Caixa / Canais do MTE / Etapas operacionais que precisam ser validadas"*) e 16 (*"A pesquisa permite identificar seis grandes dimensões"*) referem-se a representações visuais cujo conteúdo não está no texto. As "seis grandes dimensões" nunca são nomeadas. O problema não é estético: são conclusões que o leitor não consegue examinar.

**F11 — Fichas detalhadas incompletas, justamente nos campos que o mapa precisa.**
A v1 detalha 11 dos 34 atores e admite isso. Mas mesmo nessas fichas faltam, na maioria, os campos *"Momento ou condição de entrada na jornada"* e *"de saída"* (só A01 e A03 os têm). Esses campos são os que alimentam as colunas "Entra na jornada / Sai da jornada" da tabela RACI do exercício.

---

## 3. Inferências mal-suportadas

**F12 — Contrato de 2023 tratado como "histórico" sem verificar se ainda vigora.**
Trecho: *"Processo contratual MTE nº 04/2023 — Documento histórico de contratação"* e *"O documento histórico demonstra a existência dessa discussão…"*. Na verificação, foi localizado no portal do MTE um **Termo de Apostilamento** de contrato entre MTE e Caixa (processo 19965.126175/2020-28), assinado em 26/02/2026. Isso indica que um instrumento anterior ao Contrato 07/2026 ainda recebia atos em 2026. A v1 não verifica se o contrato de 2023 e o de 2026 se sobrepõem, se um substituiu o outro, nem qual deles regula hoje o atendimento automatizado.

**F13 — O achado mais importante sustentado pela fonte mais vaga.**
A seção 8.3 (discussão de 2023 sobre remunerar a Caixa pelo atendimento automatizado e possível duplicidade com canais do MTE) é apoiada apenas por um ícone genérico *"Serviços e Informações do Brasil"*, sem página, trecho ou número de folha do PDF de 2023. É a afirmação mais relevante para decidir quem financia e responde pela URA e precisa de citação exata.

**F14 — "A Caixa orienta" sem o trecho que comprove a orientação.**
Trecho: *"A Caixa orienta que dúvidas relacionadas à concessão e ao valor do benefício sejam tratadas nos canais do MTE."* A FAQ da Caixa verificada diz que *o número de parcelas e o valor são definidos pelo MTE* — isso é uma informação sobre competência, não necessariamente uma orientação para o cidadão procurar o 158. A diferença importa, porque a v1 usa essa frase para sustentar a transferência T06 ("Orientação institucional documentada").

**F15 — Quem decide a habilitação: afirmação normativa sem evidência operacional.**
A ficha A11 atribui ao MTE a decisão de *"Habilitação"*; a ficha A18 diz que a Dataprev faz *"Verificação de informações e requisitos de elegibilidade"*; e a seção 13.3 conclui que a atuação da Dataprev *"não deve ser confundida com a titularidade da competência administrativa do MTE"*. Isso é uma premissa jurídica razoável, mas a v1 não mostra **onde** ocorre a decisão humana — se é que ocorre — num processo amplamente automatizado. Para o mapa, a diferença entre "quem tem a competência" e "quem efetivamente decide" é central e ficou resolvida por afirmação, não por evidência.

**F16 — Graus de confiança inflados nas relações.**
Exemplos: *"R07 — Bases trabalhistas → Dataprev — Alta"*, sem fonte e sem dizer quais bases; *"R13 — Caixa → Fornecedor de contact center — Contratação tecnológica específica — Média"*, embora a própria v1 diga que o fornecedor *"não foi confirmado"* e que só há uma licitação (licitação não é contrato). Pela régua do próprio relatório, R13 deveria ser hipótese de confiança baixa.

---

## 4. Fontes fracas ou ausentes

**F17 — Fontes genéricas classificadas como "Alta".**
*"E12 — Transparência das contratações Caixa — Possibilidade de investigação de fornecedores — Alta"*: é uma página inicial; não sustenta nenhuma afirmação, apenas indica onde procurar. *"E03 — Canais de atendimento da Caixa"* também é uma página geral. O prompt pedia links diretos para documentos, não páginas iniciais. Somam-se a isso o Escavador como fonte única de um acórdão (F01) e o ícone genérico da F13.

---

## 5. Atores omitidos relevantes

**F18 — INSS omitido, embora seja habilitador de uma modalidade citada pela própria v1.**
A v1 transcreve o objeto do contrato com a modalidade **Pescador Artesanal** (Seguro-Defeso), mas não registra que, desde a Lei 13.134/2015, o requerimento e a habilitação dessa modalidade são feitos pelo **INSS**. O INSS também é o gestor do **CNIS**, que a v1 lista (A20) sem dizer quem o administra. Para essa modalidade, a resposta a "quem decide" não é o MTE.

**F19 — Auditoria-Fiscal do Trabalho omitida.**
Na modalidade **Trabalhador Resgatado**, também citada no contrato, o requerimento nasce da ação de resgate conduzida pelos Auditores-Fiscais do Trabalho. É um ator que inicia a jornada para esse público e não aparece no inventário.

**F20 — eSocial e o sistema Empregador Web omitidos.**
Ligado à F05. O empregador (A02) só aparece como "demandante e origem de dados", sem os sistemas pelos quais entrega esses dados e emite o requerimento (Empregador Web, citado inclusive na página do Facilita, e o eSocial), nem os órgãos que governam o eSocial.

**F21 — Dono da plataforma gov.br omitido.**
A v1 lista *"A22 — gov.br e Carteira de Trabalho Digital"* como canal, mas não identifica quem mantém o login gov.br (Ministério da Gestão e da Inovação em Serviços Públicos). O nível da conta gov.br condiciona o acesso a serviços do benefício; falhas de login são um ponto de bloqueio da jornada com dono próprio.

**F22 — Regulação do canal telefônico não considerada.**
A v1 cita a Lei 13.460/2017 e a LGPD, mas não examina se a central da Caixa está sujeita ao **Decreto nº 11.034/2022** (regras de SAC, inclusive sobre URA e acesso a atendente humano), nem os atores que fiscalizam essas regras (Senacon) ou que supervisionam a Caixa como instituição financeira (Banco Central, inclusive quanto às ouvidorias). A aplicabilidade a um canal de benefício público é discutível — e é exatamente por isso que deveria aparecer como questão em aberto, não estar ausente.

**F23 — Unidade da Caixa citada no texto, mas ausente do inventário.**
A seção 8.2 menciona a *"Centralizadora Nacional Contratações — CECOT"* como responsável pela Licitação 120/2024. É uma unidade interna da Caixa com papel na cadeia de fornecimento da central, mas não entra no inventário de atores. A v1 diz que "unidade interna não identificada", quando identificou ao menos uma.

**F24 — Representantes e públicos específicos omitidos; via judicial ausente.**
O prompt incluía "representantes" na categoria A; a v1 não registra procuradores ou representantes legais, nem diferencia os públicos das modalidades (doméstico, pescador, resgatado). Na seção 11, as instâncias de contestação são só administrativas: Justiça Federal e Defensoria Pública da União, caminhos comuns quando o recurso administrativo é negado, não aparecem nem como atores transversais.

---

## Quadro-resumo

| ID | Tipo | Gravidade para o mapa |
|---|---|---|
| F01 | Atribuição incorreta de fonte | Média |
| F02 | Erro factual (funcionalidade) | Média |
| F03 | Hipótese reformulada | Média |
| F04 | Contradição interna | Baixa |
| F05 | Dado desatualizado | Alta |
| F06 | Afirmação sem fonte | Baixa |
| F07 | Validação sem rastreio | Média |
| F08 | "Confirmada" sem evidência | Média |
| F09 | Citações não rastreáveis | Média |
| F10 | Conclusões não examináveis | Média |
| F11 | Campos de entrada/saída ausentes | Alta |
| F12 | Inferência sobre vigência contratual | Alta |
| F13 | Achado central com fonte vaga | Alta |
| F14 | Competência confundida com orientação | Média |
| F15 | Decisão de habilitação sem evidência | Alta |
| F16 | Confiança inflada | Média |
| F17 | Fontes genéricas | Média |
| F18 | Ator omitido: INSS | Alta |
| F19 | Ator omitido: Auditoria-Fiscal do Trabalho | Alta |
| F20 | Ator omitido: eSocial / Empregador Web | Média |
| F21 | Ator omitido: gestor do gov.br | Média |
| F22 | Regulação do SAC e reguladores | Média |
| F23 | Ator omitido: CECOT | Baixa |
| F24 | Representantes e via judicial | Média |

## Recomendação para a v2

Tratar **cada** falha F01–F24 explicitamente, indicando para cada uma: (a) corrigida com texto novo e fonte, (b) defendida com argumento e evidência, ou (c) marcada como pendente. Prioridade para as de gravidade alta (F05, F11, F12, F13, F15, F18, F19), que alteram quem entra no mapa e quem responde por quê.
