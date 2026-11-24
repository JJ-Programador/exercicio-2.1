# **Relatório de pesquisa v3 — Mapeamento de atores da jornada de Atendimento ao Seguro-Desemprego pela URA da Caixa**

**Disciplina:** Transformação Digital — IDP-TD 2026\
**Exercício:** 2.1 — Mapa de Atores da Jornada de um Serviço Público\
**Assistente responsável:** ChatGPT — OpenAI\
**Auditor:** Claude — Anthropic\
**Data:** 24/11/2026\
**Versão:** 3.0

## **1. Registro das alterações motivadas pela segunda auditoria**

A terceira versão tem como objetivo resolver as inconsistências remanescentes da v2, corrigir as oito novas falhas identificadas pelo auditor e estabelecer critérios objetivos para a seleção dos atores que integrarão o mapa definitivo.

A revisão considera as quatro partes da segunda auditoria, preservando as conclusões anteriores que não foram contestadas. Cada alteração substantiva será acompanhada do identificador que a motivou.

| Ponto da auditoria | Tratamento na v3           | Mudança realizada                                                                                           | Seção  |
| ------------------ | -------------------------- | ----------------------------------------------------------------------------------------------------------- | ------ |
| F01                | Resolvido                  | Localizado o Acórdão TCU nº 1445/2024 em fonte primária oficial.                                            | 6      |
| F02                | Resolvido                  | Identificado o trecho da carta de serviço que confirma o agendamento pelo Facilita.                         | 3      |
| F08                | Corrigido                  | Acrescentada fundamentação legal para a competência da ANPD.                                                | 7      |
| F09                | Corrigido parcialmente     | Individualizadas as referências, eliminando marcadores agregados e registrando limitações.                  | 10     |
| F11                | Corrigido                  | Definidas condições concretas de entrada e saída dos atores prioritários.                                   | 8      |
| F12                | Corrigido parcialmente     | Identificado que o Contrato nº 04/2023 se refere ao Abono Salarial, e não diretamente ao Seguro-Desemprego. | 5      |
| F13                | Corrigido parcialmente     | Localizadas as cláusulas contratuais relativas à remuneração da URA, delimitando seu objeto.                | 5      |
| F16                | Corrigido                  | Revisados o fluxo financeiro e os graus de confiança das relações.                                          | 9      |
| F21                | Parcialmente resolvido     | MGI mantido como dependência da identidade digital, sem presumir participação direta na URA.                | 7      |
| B1                 | Mantido com complementação | Preservada a mudança de competência do Seguro-Defeso, com referência legislativa primária.                  | 4      |
| B2                 | Mantido com ressalva       | Retirada a data não sustentada do novo decreto sobre SAC.                                                   | 7      |
| B3                 | Resolvido                  | Confirmado documentalmente que o Facilita permite iniciar agendamentos.                                     | 3      |
| N01                | Corrigido parcialmente     | Localizada a Lei nº 15.265/2025, art. 37; separada a data legal da transição operacional.                   | 4      |
| N02                | Parcialmente resolvido     | Revogação registrada, sem conclusões não demonstradas sobre o regime substituto.                            | 7      |
| N03                | Corrigido                  | Rebaixadas as classificações relativas ao MPA e ao MMA até comprovação normativa específica.                | 4      |
| N04                | Corrigido                  | Restaurados os links E02 e E15.                                                                             | 10     |
| N05                | Corrigido                  | Separados o financiamento do benefício e a execução financeira pelo agente pagador.                         | 5 e 9  |
| N06                | Corrigido                  | Reclassificada F06 como correção, e não como simples pendência.                                             | 2      |
| N07                | Corrigido                  | Criados critérios para seleção, agrupamento e exclusão de atores.                                           | 8      |
| N08                | Corrigido                  | Eliminadas conclusões exageradas sobre os erros do auditor.                                                 | 12     |
| D1                 | Pendente                   | Funcionamento específico da URA ainda depende de documentação operacional.                                  | 3 e 11 |
| D2                 | Parcialmente resolvido     | Identificada a natureza do contrato de 2023 e o limite de sua utilização como evidência.                    | 5      |
| D3                 | Parcialmente resolvido     | Acórdão localizado; fornecedor e modelo operacional permanecem desconhecidos.                               | 6      |
| D4                 | Corrigido conceitualmente  | Incluído o fluxo de financiamento até o agente pagador, com ressalva sobre a operacionalização contábil.    | 5      |
| D5                 | Pendente                   | Aplicabilidade do novo regime jurídico de SAC ainda não demonstrada.                                        | 7      |
| D6                 | Tratado                    | Classificados os 54 elementos segundo sua pertinência para o mapa.                                          | 8      |

Os identificadores D1 a D6 correspondem aos seis pontos abertos da Parte D da segunda auditoria. Essa numeração foi adotada nesta revisão para facilitar a rastreabilidade.

Fonte da revisão: `B_relatorio_auditoria_v2.md`, Partes A, B, C e D.&#x20;

B_relatorio_auditoria_v2.md



## **2. Sumário executivo e revisão metodológica**

A terceira rodada de investigação produziu quatro avanços documentais relevantes:

- Localização do Acórdão nº 1445/2024 na documentação oficial do TCU, confirmando a participação da CECOT na licitação de contact center da Caixa.
- Confirmação da possibilidade de realizar novos agendamentos pelo Facilita, por meio da carta oficial de prestação do serviço.
- Identificação de que o Contrato MTE nº 04/2023, utilizado anteriormente para investigar a remuneração da URA, tem como objeto o Abono Salarial, e não o Seguro-Desemprego.
- Localização do art. 37 da Lei nº 15.265/2025, que atribui expressamente ao MTE a competência para receber, processar e habilitar requerimentos do Seguro-Defeso.

Também foi localizada evidência normativa sobre a habilitação automatizada do Seguro-Desemprego, permitindo melhorar a análise de quem efetivamente participa das decisões.

A pesquisa continua sem comprovar integralmente o funcionamento específico da URA: menus disponíveis, identificação do usuário, sistemas consultados, fornecedor contratado e procedimentos de transferência.

### **2.1. Classificação das evidências**

Para evitar as inconsistências identificadas em F08, F09 e F16, esta versão adota quatro categorias:

| Classificação                | Critério                                                             |
| ---------------------------- | -------------------------------------------------------------------- |
| Fato confirmado — FC         | Afirmação diretamente sustentada por documento identificado.         |
| Inferência fundamentada — IF | Conclusão derivada de evidências, mas não expressamente demonstrada. |
| Hipótese a verificar — HV    | Possibilidade ainda não comprovada.                                  |
| Lacuna de informação — LI    | Informação necessária não localizada.                                |

A confirmação da existência de uma instituição, sistema ou competência não será interpretada automaticamente como confirmação de sua participação operacional na URA.

### **2.2. Correção da classificação de F06 — N06**

A v2 classificou a retirada dos horários de atendimento como pendência.

Na v3, a classificação passa a ser **correção (a)**, pois a afirmação sem sustentação foi efetivamente retirada do relatório.

A identificação dos horários atuais permanece como lacuna L19, mas não como falha textual não corrigida.

## **3. Jornada do cidadão e validação dos canais**

### **3.1. Delimitação do serviço — N07 e D6**

O objeto central permanece sendo o atendimento telefônico ao cidadão que procura informações sobre o Seguro-Desemprego pelo canal da Caixa.

São consideradas dependências externas apenas aquelas capazes de:

- Produzir ou alterar a informação procurada pelo cidadão.
- Viabilizar o atendimento ou o pagamento.
- Resolver uma demanda que não esteja dentro da competência da Caixa.
- Regulamentar, financiar ou supervisionar atividades relevantes para o serviço.

A existência de uma instituição na política pública, isoladamente, não justifica sua inclusão no mapa principal.

### **3.2. Jornada funcional revisada — D1**

Canal ou competência documentada

Operação específica não comprovada

As linhas tracejadas representam percursos possíveis, não transferências efetivamente demonstradas.

| Etapa | Atividade                                | Situação                           |
| ----- | ---------------------------------------- | ---------------------------------- |
| J01   | Identificar necessidade de informação    | Ponto inicial analítico            |
| J02   | Ligar para a Caixa                       | Canal documentado pela FAQ         |
| J03   | Navegar pelos menus da URA               | Fluxo específico pendente          |
| J04   | Identificar-se                           | Procedimento pendente              |
| J05   | Consultar informações sobre parcelas     | Consulta telefônica documentada    |
| J06   | Obter resposta automatizada              | Funcionalidade específica pendente |
| J07   | Receber atendimento humano               | Roteamento específico pendente     |
| J08   | Buscar outro canal digital ou telefônico | Canais documentados                |
| J09   | Procurar atendimento presencial          | Alternativas documentadas          |
| J10   | Reclamar ou contestar                    | Participação eventual              |

A nova pesquisa documental não permite afirmar que essas etapas ocorram obrigatoriamente nessa sequência.

### **3.3. Validação do Facilita — F02, B3 e F16**

A carta oficial do serviço *Agendar Atendimento Presencial no Ministério do Trabalho e Emprego*, atualizada em 10/11/2026, estabelece como etapa inicial:

> Acesse a Plataforma Facilita Brasil ou entre em contato com a Central Alô Trabalho (158).

O documento apresenta, nas etapas seguintes, a escolha do serviço, da unidade, da data e do horário, seguida da confirmação.

**Evidência E20:** [Carta oficial de agendamento presencial do MTE](https://www.gov.br/pt-br/servicos/agendar-atendimento-presencial-no-ministerio-do-trabalho-e-emprego?utm_source=chatgpt.com), seção “Etapas para a realização deste serviço”.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.gov.br\&sz=32)

Serviços e Informações do Brasil



Consequências:

| Elemento                                          | Classificação revisada |
| ------------------------------------------------- | ---------------------- |
| Existência do Facilita                            | FC                     |
| Criação de agendamentos pelo Facilita             | FC                     |
| Agendamento pela Central 158                      | FC                     |
| Relação R29 — cidadão e Facilita                  | Confiança alta         |
| Agendamento diretamente pela URA Caixa            | HV                     |
| Transferência automática da Caixa para o Facilita | HV                     |

A funcionalidade do Facilita está confirmada. Sua integração operacional com a central da Caixa continua sem comprovação.

## **4. Modalidades do Seguro-Desemprego e decisões de habilitação**

### **4.1. Seguro-Defeso — B1, N01 e F18**

A consulta ao texto primário da Lei nº 15.265, de 21 de novembro de 2025, confirmou a alteração da Lei nº 10.779/2003.

O art. 37 da nova lei atribui ao MTE o recebimento, o processamento dos requerimentos e a habilitação dos beneficiários do Seguro-Defeso.

**Evidência E24:** [Lei nº 15.265/2025 — Presidência da República](https://planalto.gov.br/ccivil_03/_ato2023-2026/2025/lei/l15265.htm?utm_source=chatgpt.com), arts. 37 e 41.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://planalto.gov.br\&sz=32)

Presidência da República



A cronologia deve distinguir o marco operacional informado pelos órgãos públicos da publicação da norma.

| Marco                        | Evidência                               | Situação                                                                            |
| ---------------------------- | --------------------------------------- | ----------------------------------------------------------------------------------- |
| Até 31/10/2025               | Carta de serviço do Seguro-Defeso — E17 | Pedidos anteriores permanecem sob tratamento do INSS, conforme regras de transição. |
| A partir de novembro de 2025 | Informação institucional do MTE — E23   | Transferência operacional informada pelos órgãos.                                   |
| 21/11/2025                   | Lei nº 15.265/2025, art. 37             | Competência do MTE expressamente estabelecida na legislação.                        |

O fundamento normativo específico aplicável ao intervalo anterior à publicação da lei não foi suficientemente esclarecido nesta rodada.

Não se deve concluir que a publicação da lei em 21/11/2025, isoladamente, explica todos os atos administrativos praticados desde 01/11/2025.

### **4.2. Ministério da Pesca e Aquicultura — N03**

A v2 utilizava inadequadamente o Relatório de Gestão do INSS para fundamentar o papel do Ministério da Pesca e Aquicultura.

O art. 37 da Lei nº 15.265/2025, ao alterar o art. 2º, § 4º, da Lei nº 10.779/2003, determina que o Ministério da Pesca e Aquicultura viabilize ao MTE o acesso às informações cadastrais do Registro Geral da Atividade Pesqueira — RGP.

Essa é a nova fundamentação de A46.

**Relação com a jornada:** informações cadastrais podem afetar a habilitação do benefício e, consequentemente, a existência de parcelas sobre as quais o pescador procura atendimento.

A participação dessa instituição na própria ligação telefônica não foi comprovada.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://planalto.gov.br\&sz=32)

Presidência da República



### **4.3. Ministério do Meio Ambiente — N03**

A classificação de A47 como participação confirmada foi retirada.

Embora a regulamentação ambiental seja relevante para a existência dos períodos de defeso, ainda é necessário identificar os atos normativos específicos e os órgãos competentes pela sua edição.

A47 passa a integrar exclusivamente a camada de dependências condicionais, como hipótese institucional a verificar.

### **4.4. Modalidades e públicos**

| Modalidade            | Dependências diferenciadas                                       |
| --------------------- | ---------------------------------------------------------------- |
| Trabalhador formal    | Empregador, registros trabalhistas e MTE.                        |
| Empregado doméstico   | Empregador doméstico, eSocial e MTE.                             |
| Pescador artesanal    | MTE, RGP, Ministério da Pesca e INSS nas situações transitórias. |
| Trabalhador resgatado | Auditoria-Fiscal do Trabalho e MTE.                              |

A Bolsa de Qualificação Profissional também aparece entre as modalidades regulamentadas pelo CODEFAT, mas não integra o objeto do Contrato nº 07/2026 descrito na pesquisa anterior. Sua presença específica no atendimento da URA permanece fora do escopo confirmado desta investigação.

### **4.5. Quem efetivamente decide a habilitação? — F15 e F11**

A consulta à Resolução CODEFAT nº 957/2022 trouxe nova evidência relevante.

O art. 4º, § 1º, estabelece a aferição automatizada dos critérios de habilitação nele previstos, utilizando informações provenientes de bases como CNIS, GFIP e eSocial, entre outras fontes.

O § 2º prevê a possibilidade de recurso quando inconsistências impedem a habilitação automática.

**Evidência E02:** [Resolução CODEFAT nº 957/2022 — versão disponibilizada pelo Portal FAT](https://portalfat.trabalho.gov.br/wp-content/uploads/2026/09/Resolucao-no-957-de-21-de-setembro-de-2022-Revisao-do-SD.pdf?utm_source=chatgpt.com), art. 4º, §§ 1º e 2º.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://portalfat.trabalho.gov.br\&sz=32)

Portal FAT



Isso permite evoluir a conclusão da v2.

| Dimensão                              | Responsável                            | Conclusão                          |
| ------------------------------------- | -------------------------------------- | ---------------------------------- |
| Definição dos critérios               | Legislação e CODEFAT                   | Confirmada                         |
| Competência administrativa            | MTE, ressalvadas situações específicas | Confirmada                         |
| Aferição dos requisitos gerais        | Sistema Seguro-Desemprego              | Automação prevista expressamente   |
| Processamento tecnológico             | Dataprev                               | Participação documentada           |
| Revisão em caso de inconsistência     | Instância administrativa competente    | Possibilidade normativa confirmada |
| Distribuição das intervenções humanas | Unidades e agentes administrativos     | Ainda não detalhada                |

A v3 distingue, portanto, a automação juridicamente prevista da distribuição concreta de trabalho entre agentes humanos e sistemas.

## **5. Financiamento e execução financeira**

### **5.1. Correção do fluxo financeiro — N05, F16 e D4**

O FAT financia o Programa Seguro-Desemprego. O MTE administra a política, enquanto a Caixa atua na operacionalização financeira contratada.

Essas funções não devem ser representadas como se o ministério fosse o destinatário final dos recursos do benefício.

A v3 propõe o seguinte fluxo funcional:

| Relação                               | Natureza                                            | Evidência                                     |
| ------------------------------------- | --------------------------------------------------- | --------------------------------------------- |
| CODEFAT → FAT                         | Governança e deliberação                            | E01                                           |
| FAT → Programa Seguro-Desemprego      | Financiamento                                       | E01, art. 10                                  |
| MTE → Caixa                           | Contratação da execução financeira                  | E09                                           |
| Recursos do programa → agente pagador | Disponibilização financeira necessária ao pagamento | E01 e E09; fluxo contábil específico pendente |
| Caixa → beneficiário                  | Pagamento do benefício                              | E04, E09                                      |

A representação não comprova a existência de uma transferência bancária direta do FAT à Caixa sem unidades orçamentárias ou mecanismos intermediários.

### **5.2. Dois fluxos financeiros distintos**

É fundamental separar duas categorias de despesa:

| Fluxo                                | Finalidade                                                                                |
| ------------------------------------ | ----------------------------------------------------------------------------------------- |
| Recursos destinados ao benefício     | Valores devidos aos trabalhadores elegíveis.                                              |
| Remuneração de serviços operacionais | Pagamento à instituição contratada pela prestação dos serviços previstos contratualmente. |

O financiamento das parcelas não é equivalente ao financiamento da central telefônica.

### **5.3. Revisão do Contrato nº 04/2023 — F12, F13 e D2**

A leitura das páginas iniciais do PDF público permitiu identificar um erro importante de delimitação na pesquisa anterior.

O documento é o Contrato MTE nº 04/2023, processo nº 19965.104455/2022-47, firmado com a Caixa Econômica Federal.

A cláusula 1.1 define seu objeto como prestação de serviços de pagamento do **Abono Salarial destinado aos trabalhadores inscritos no PIS**.

O contrato também contempla remuneração pelo atendimento da URA.

**Contrato MTE nº 04/2023 — Abono Salarial**

Tarifa unitária por atendimento URA

# **R$ 0,62**

Valor estimado da URA em 60 meses

# **R$ 68,73 mi**

Valor total estimado do contrato

# **R$ 407,51 mi**

Vigência originalmente prevista

**02/04/2023 a 02/04/2028**

Fonte: Contrato nº 04/2023, páginas 1 e 2, cláusulas 1ª, 2ª e 3ª. Os valores são estimativos contratuais, não despesas efetivamente realizadas.

**Evidência E10:** [Contrato nº 04/2023 — documento completo, 173 páginas](https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/licitacoes-e-contratos/contratos/pdf/04_2023completo.pdf?utm_source=chatgpt.com).&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.gov.br\&sz=32)

Serviços e Informações do Brasil



Foram realizadas buscas textuais adicionais pelos termos “duplicidade” e “automatizado” no documento, sem localização dos trechos anteriormente mencionados.

#### **Consequências para o diagnóstico**

O contrato comprova que existe um modelo de remuneração de atendimento por URA na relação contratual entre MTE e Caixa para o Abono Salarial.

Porém, não comprova que o mesmo modelo seja utilizado no Seguro-Desemprego.

Assim:

- A possibilidade de remuneração contratual específica da URA possui precedente documental.
- Os valores identificados não podem ser atribuídos ao Seguro-Desemprego.
- A alegada discussão sobre redundância de canais não foi localizada com precisão e permanece sem comprovação.

### **5.4. Contrato nº 07/2026 — Seguro-Desemprego**

Permanecem válidos os dados confirmados na primeira auditoria.

| Informação         | Registro                                              |
| ------------------ | ----------------------------------------------------- |
| Contratante        | MTE                                                   |
| Contratada         | Caixa Econômica Federal                               |
| Contrato           | 07/2026                                               |
| Processo           | 19965.202436/2025-28                                  |
| Objeto             | Operacionalização dos pagamentos do Seguro-Desemprego |
| Valor estimado     | R$ 383.325.207,75                                     |
| Vigência divulgada | 16/04/2026 a 16/04/2031                               |

Fonte E09: [Portal de contratações do MTE — 2026](https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/licitacoes-e-contratos/pca/2026-1?utm_source=chatgpt.com), registro correspondente ao Contrato nº 07/2026.

**Conclusão revisada:** o contrato de 2023 identificado não deve ser tratado como instrumento anterior de mesmo objeto automaticamente substituído pelo de 2026.

O instrumento que remunera especificamente o atendimento telefônico do Seguro-Desemprego permanece não identificado.

## **6. Infraestrutura tecnológica e fornecedores**

### **6.1. Localização do Acórdão TCU nº 1445/2024 — F01 e D3**

A pesquisa na base oficial do TCU permitiu localizar o acórdão anteriormente citado de forma inconsistente.

O documento confirma que o Tribunal examinou representação relativa à Licitação Caixa nº 120/2024, sob responsabilidade da Centralizadora Nacional Contratações — CECOT.

O objeto do certame abrangia uma solução tecnológica de contact center em nuvem, incluindo atendimento automatizado, configuração, integração com sistemas corporativos, suporte e documentação, pelo período previsto de 60 meses.

**Evidência E11:** [Boletim do TCU — Deliberações dos Colegiados nº 129, de 26/07/2024](https://sessoes-portal-ms.apps.tcu.gov.br/api/sessoes/downloadPautaPublicada/22204?utm_source=chatgpt.com), página 140, Acórdão nº 1445/2024 — Plenário.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://sessoes-portal-ms.apps.tcu.gov.br\&sz=32)

Sessions Portal MS



A divergência de numeração observada na versão anterior pode ser explicada pela estrutura do documento de publicação, que reúne diversas decisões. A referência passa a identificar expressamente o acórdão correto e sua localização.

### **6.2. O que a evidência permite afirmar**

| Afirmação                                                | Classificação |
| -------------------------------------------------------- | ------------- |
| A Caixa promoveu licitação de solução de contact center. | FC            |
| A CECOT foi responsável pela Licitação 120/2024.         | FC            |
| O objeto incluía atendimento automatizado.               | FC            |
| A licitação previa integração com sistemas corporativos. | FC            |
| A contratação foi concluída nos termos originais.        | LI            |
| A solução integra atualmente a URA do Seguro-Desemprego. | HV            |
| A identidade do fornecedor atual é conhecida.            | LI            |
| A operação humana da central é terceirizada.             | HV            |

A CECOT passa a ter participação confirmada na contratação examinada pelo TCU, mas não na gestão cotidiana da URA específica.

### **6.3. Modelo operacional da central**

Continuam válidas as três hipóteses:

| Modelo       | Descrição                                         | Situação       |
| ------------ | ------------------------------------------------- | -------------- |
| Próprio      | Infraestrutura e atendimento operados pela Caixa. | Não comprovado |
| Terceirizado | Operação atribuída a prestadores contratados.     | Não comprovado |
| Híbrido      | Combinação de recursos próprios e contratados.    | Não comprovado |

A contratação de uma plataforma tecnológica não implica necessariamente a terceirização dos atendentes ou da gestão do serviço.

### **6.4. Fontes de dados e sistemas**

A distinção realizada na v2 entre eSocial, CAGED, Novo CAGED e Empregador Web permanece válida.

A Resolução CODEFAT nº 957/2022, art. 4º, acrescenta fundamentação direta à utilização de registros oficiais na aferição automatizada de critérios de habilitação.

| Recurso                   | Finalidade                                 | Relação com a URA                            |
| ------------------------- | ------------------------------------------ | -------------------------------------------- |
| CNIS                      | Informações previdenciárias e trabalhistas | Indireta; consulta direta não comprovada     |
| eSocial                   | Registro de eventos trabalhistas           | Indireta; utilização na habilitação prevista |
| GFIP e registros de FGTS  | Informações trabalhistas e previdenciárias | Indireta; fontes previstas normativamente    |
| CAGED                     | Registros históricos e residuais           | Utilização específica pendente               |
| Novo CAGED                | Produção estatística                       | Excluído do mapa operacional principal       |
| Empregador Web            | Transmissão de requerimentos               | Dependência anterior ao atendimento          |
| Sistema Seguro-Desemprego | Aferição de requisitos e processamento     | Dependência funcional                        |
| Dataprev                  | Suporte tecnológico e processamento        | Interface direta com a URA não comprovada    |
| Contact center            | Infraestrutura de atendimento              | Solução específica atual pendente            |

## **7. Governança digital, regulamentação e controle**

### **7.1. Secretaria de Governo Digital do MGI — F21**

A Portaria SGD/MGI nº 11.229, de 12 de dezembro de 2025, estabelece diretrizes para criação e gestão de contas digitais na plataforma gov.br.

A identificação dessa norma permite fundamentar a inclusão do Ministério da Gestão e da Inovação em Serviços Públicos, particularmente da Secretaria de Governo Digital, na camada de dependências tecnológicas.

**Evidência E25:** [Atos normativos de 2025 — MGI](https://www.gov.br/gestao/pt-br/acesso-a-informacao/institucional/atos-normativos/2025/2025-portarias?utm_source=chatgpt.com), seção Secretaria de Governo Digital.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.gov.br\&sz=32)

Serviços e Informações do Brasil



| Elemento                                                | Classificação revisada                        |
| ------------------------------------------------------- | --------------------------------------------- |
| A40 — MGI/Secretaria de Governo Digital                 | FC quanto à governança da identidade digital  |
| R25 — MGI → Plataforma gov.br                           | Confiança alta quanto à competência normativa |
| Participação do MGI na autenticação telefônica da Caixa | Não comprovada                                |

O MGI somente deverá integrar uma ramificação da jornada quando o cidadão precisar recorrer a um serviço digital que utilize a conta gov.br.

### **7.2. Agência Nacional de Proteção de Dados — F08**

A competência da ANPD passa a ter fundamentação expressa no art. 55-J da Lei nº 13.709/2018 — Lei Geral de Proteção de Dados Pessoais.

**Evidência E26:** [Lei nº 13.709/2018 — texto compilado](https://planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709compilado.htm?utm_source=chatgpt.com), art. 55-J, especialmente incisos I, IV e V.

A norma fundamenta a atuação da ANPD na proteção de dados, fiscalização e apreciação de petições nas condições estabelecidas legalmente.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://planalto.gov.br\&sz=32)

Presidência da República



A ANPD não integra o atendimento ordinário da URA. Sua inclusão ocorre na camada de controle, condicionada à existência de questão relativa ao tratamento de dados pessoais.

### **7.3. Novo regime jurídico do SAC — N02, B2 e D5**

A pesquisa complementar permitiu confirmar a data anteriormente questionada e acessar o conteúdo do novo decreto.

| Informação              | Registro confirmado         |
| ----------------------- | --------------------------- |
| Norma                   | Decreto nº 13.135/2026      |
| Data                    | 09/10/2026                  |
| Publicação              | DOU de 13/10/2026, página 5 |
| Entrada em vigor        | 20 dias após a publicação   |
| Norma revogada          | Decreto nº 11.034/2022      |
| Fundamento da revogação | Art. 24                     |
| Fundamento da vigência  | Art. 25                     |

**Evidência E27:** [Decreto nº 13.135/2026 — Senado Federal](https://legis.senado.leg.br/norma/44154496/publicacao/44157502?utm_source=chatgpt.com).&#x20;

[image](https://www.google.com/s2/favicons?domain=https://legis.senado.leg.br\&sz=32)

Senado Federal+1



Entre os dispositivos relevantes para o estudo estão:

| Dispositivo   | Assunto                                                          |
| ------------- | ---------------------------------------------------------------- |
| Art. 1º       | Delimitação do SAC nas relações de consumo                       |
| Art. 4º       | Qualidade do atendimento e disponibilidade de atendimento humano |
| Art. 5º       | Proteção dos dados pessoais                                      |
| Art. 7º       | Continuidade do tratamento da demanda                            |
| Art. 8º       | Gratuidade e condições de acesso                                 |
| Art. 23       | Fiscalização pela Senacon e competências regulatórias            |
| Arts. 24 e 25 | Revogação e vigência                                             |

[image](https://www.google.com/s2/favicons?domain=https://anvisalegis.datalegis.net\&sz=32)

Anvisa Legis+2

O novo decreto mantém e amplia disposições relacionadas à qualidade do atendimento e ao acesso a atendimento humano.

Contudo, permanece a questão jurídica central: o atendimento realizado pela Caixa na condição de agente pagador de um benefício público configura relação de consumo para os fins desse decreto?

A pesquisa não identificou manifestação jurídica específica que permita responder conclusivamente.

Portanto:

- **A41 — Senacon:** competência regulatória geral confirmada; incidência específica sobre a URA condicionada.
- **A43 — Banco Central:** permanece como ator regulatório condicionado à natureza financeira da demanda.

### **7.4. Complementação final da transição do Seguro-Defeso — N01 e B1**

Uma busca complementar realizada nesta rodada identificou os instrumentos que faltavam para explicar a transição institucional do Seguro-Defeso.

| Norma                                     | Contribuição                                                                 |
| ----------------------------------------- | ---------------------------------------------------------------------------- |
| MP nº 1.323, de 04/11/2025                | Estabeleceu a mudança de competência e a distinção entre períodos de defeso. |
| Resolução CODEFAT nº 1.027, de 10/11/2025 | Disciplinou procedimentos e regras de transição.                             |
| Lei nº 15.265, de 21/11/2025              | Alterou expressamente a competência prevista na Lei nº 10.779/2003.          |
| Lei nº 15.399/2026                        | Estabeleceu regras posteriores relativas ao Seguro-Defeso e à transição.     |

**Evidências complementares:**

- E28 — [Medida Provisória nº 1.323/2025](https://planalto.gov.br/ccivil_03/_ato2023-2026/2025/mpv/mpv1323impressao.htm?utm_source=chatgpt.com), arts. 2º a 4º.
- E29 — [Resolução CODEFAT nº 1.027/2025](https://portalfat.trabalho.gov.br/wp-content/uploads/2026/10/Resolucao-no-1027-de-10.11.2025-SDPA.pdf?utm_source=chatgpt.com), art. 1º.
- E30 — [Lei nº 15.399/2026 — legislação federal, Senado](https://legis.senado.leg.br/norma/43240303/publicacao/43249294?utm_source=chatgpt.com), arts. 2º e 3º.

[image](https://www.google.com/s2/favicons?domain=https://planalto.gov.br\&sz=32)

Presidência da República+2

**Conclusão:** 1º de novembro de 2025 constitui o marco de referência dos períodos de defeso abrangidos pela transferência de competência. Não deve ser confundido com a data de publicação dos atos normativos.

Essa evidência resolve a principal lacuna temporal identificada em N01 e complementa a seção 4.1 deste relatório.

## **8. Inventário de atores e critérios de inclusão no mapa**

### **8.1. Critério de seleção — N07, F11 e D6**

A ampliação do inventário de 34 para 54 elementos na v2 não significa que todos devam aparecer no mapa definitivo.

A v3 propõe três camadas de representação.

Modelo de organização do mapa. A posição nas camadas representa proximidade funcional com a jornada, não hierarquia institucional.

| Camada                            | Critério                                                                                                                |
| --------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| C1 — Mapa principal               | Participa do atendimento ou possui responsabilidade essencial pela informação, resolução ou financiamento do serviço.   |
| C2 — Dependências                 | Produz informações, tecnologia ou serviços que influenciam a jornada, ainda que não interaja diretamente com o cidadão. |
| C3 — Contexto e controle          | Participação eventual, regulatória, fiscalizatória ou específica de determinada situação.                               |
| X — Não representar separadamente | Recursos ou elementos redundantes que devem ser agrupados com outros atores.                                            |

A seleção final será submetida à entrevista adversarial. O presente relatório apresenta uma proposta fundamentada, não o mapa definitivo.

### **8.2. Classificação dos 54 elementos inventariados**

A tabela preserva os identificadores da v2 e acrescenta a justificativa de pertinência para a jornada.

| ID  | Elemento                              | Camada | Justificativa                                                |
| --- | ------------------------------------- | ------ | ------------------------------------------------------------ |
| A01 | Cidadão                               | C1     | Inicia a demanda.                                            |
| A02 | Empregador                            | C2     | Produz informações que podem afetar a habilitação.           |
| A03 | URA                                   | C1     | Componente central do atendimento investigado.               |
| A04 | Atendente                             | C1     | Possível responsável pelo tratamento humano da demanda.      |
| A05 | Caixa                                 | C1     | Instituição responsável pelo canal e pelo pagamento.         |
| A06 | Gestor da central                     | C2     | Potencial responsável por fluxos, regras e resultados.       |
| A07 | Supervisor                            | C2     | Potencial responsável por exceções.                          |
| A08 | Equipe de qualidade                   | C2     | Potencial responsável pelo monitoramento do atendimento.     |
| A09 | Agência Caixa                         | C2     | Alternativa presencial para questões não resolvidas.         |
| A10 | Rede lotérica                         | C2     | Alternativa de recebimento, quando aplicável.                |
| A11 | MTE                                   | C1     | Responsável pela administração do benefício.                 |
| A12 | Unidade gestora do benefício          | X      | Agrupar inicialmente com MTE.                                |
| A13 | Central 158                           | C1     | Canal alternativo para questões ministeriais.                |
| A14 | SRT                                   | C2     | Alternativa presencial vinculada ao MTE.                     |
| A15 | SINE                                  | C2     | Rede descentralizada de atendimento ao trabalhador.          |
| A16 | CODEFAT                               | C1     | Governa as regras e deliberações do programa.                |
| A17 | FAT                                   | C1     | Fonte de financiamento do benefício.                         |
| A18 | Dataprev                              | C1     | Dependência tecnológica essencial do processamento.          |
| A19 | Sistema Seguro-Desemprego             | C2     | Recurso de processamento e aferição de requisitos.           |
| A20 | CNIS                                  | C2     | Fonte de informações utilizadas na habilitação.              |
| A21 | CAGED                                 | C2     | Fonte histórica ou residual, conforme necessidade.           |
| A22 | gov.br e Carteira de Trabalho Digital | C2     | Acesso aos serviços digitais.                                |
| A23 | Aplicativos e Portal Cidadão Caixa    | C2     | Canais alternativos de consulta.                             |
| A24 | Fornecedor de contact center          | C2     | Dependência tecnológica potencial.                           |
| A25 | Operadora de telefonia                | C2     | Viabiliza a comunicação.                                     |
| A26 | Empresa de teleatendimento            | C2     | Dependência operacional potencial.                           |
| A27 | Gestores e fiscais de contratos       | C2     | Acompanham a prestação contratada.                           |
| A28 | TCU                                   | C3     | Controle externo.                                            |
| A29 | CGU                                   | C3     | Controle interno federal.                                    |
| A30 | SAC e Ouvidoria Caixa                 | C2     | Tratamento de manifestações sobre o atendimento.             |
| A31 | Ouvidoria MTE                         | C2     | Tratamento de manifestações ministeriais.                    |
| A32 | Fala.BR                               | X      | Representar como recurso das ouvidorias.                     |
| A33 | ANPD                                  | C3     | Atuação condicionada a questões de proteção de dados.        |
| A34 | Banco do beneficiário                 | C2     | Participação eventual no recebimento.                        |
| A35 | INSS                                  | C3     | Participação específica na transição do Seguro-Defeso.       |
| A36 | Auditoria-Fiscal do Trabalho          | C3     | Origem administrativa do benefício do trabalhador resgatado. |
| A37 | eSocial                               | C2     | Fonte de informações trabalhistas.                           |
| A38 | Empregador Web                        | C2     | Recepção de informações e requerimentos.                     |
| A39 | Gestores do eSocial                   | C3     | Governança das informações.                                  |
| A40 | MGI/Secretaria de Governo Digital     | C2     | Governança do acesso aos canais digitais.                    |
| A41 | Senacon                               | C3     | Regulação consumerista, quando aplicável.                    |
| A42 | CECOT                                 | C2     | Participação documentada na licitação tecnológica.           |
| A43 | Banco Central                         | C3     | Supervisão financeira, quando aplicável.                     |
| A44 | Justiça Federal                       | C3     | Eventual contestação judicial.                               |
| A45 | DPU                                   | C3     | Eventual assistência jurídica.                               |
| A46 | Ministério da Pesca e Aquicultura     | C3     | Produção de dados relevantes ao Seguro-Defeso.               |
| A47 | Ministério do Meio Ambiente           | C3     | Dependência ambiental específica ainda a validar.            |
| A48 | Facilita                              | X      | Representar como recurso digital do MTE.                     |
| A49 | Controle interno Caixa                | C3     | Supervisão institucional.                                    |
| A50 | Representante legal                   | C3     | Participação eventual em nome do beneficiário.               |
| A51 | Trabalhador formal                    | X      | Especialização do ator A01.                                  |
| A52 | Empregado doméstico                   | X      | Especialização do ator A01.                                  |
| A53 | Pescador artesanal                    | X      | Especialização do ator A01.                                  |
| A54 | Trabalhador resgatado                 | X      | Especialização do ator A01.                                  |

**Regra adicional:** os elementos classificados como recursos tecnológicos ou financeiros podem aparecer no diagrama de jornada, mas não devem receber automaticamente atribuições de responsabilidade administrativa na matriz RACI.

### **8.3. Fichas dos atores prioritários — F11**

As fichas seguintes especificam as condições de entrada e saída de maneira mais concreta. Quando a participação operacional não foi comprovada, essa limitação é registrada.

**A01 — Cidadão**

- Entrada: necessidade de obter informação sobre requerimento, parcela, pagamento ou impedimento.
- Atividade: formular demanda e utilizar os canais disponíveis.
- Saída: informação obtida, orientação recebida, demanda não resolvida ou desistência.
- Evidências: E04 e E05.

**A03 — URA da Caixa**

- Entrada: chamada encaminhada ao atendimento automatizado.
- Atividade: execução de menus e funcionalidades disponíveis.
- Saída possível: resposta automatizada, roteamento ou encerramento.
- Situação: condições específicas da modalidade Seguro-Desemprego ainda não validadas.

**A04 — Atendente humano**

- Entrada potencial: chamada encaminhada para atendimento humano.
- Atividade: interpretar e tratar a demanda dentro de suas atribuições.
- Saída possível: resposta, registro, encaminhamento ou escalonamento.
- Situação: acesso aos sistemas e procedimentos específicos não comprovados.

**A05 — Caixa Econômica Federal**

- Entrada: recebimento de demanda de atendimento ou informação necessária à execução financeira.
- Atividade: administrar seus canais e operacionalizar pagamentos contratados.
- Saída: disponibilização de informação, pagamento realizado ou registro de ocorrência.
- Evidências: E04, E09 e E11.

**A11 — Ministério do Trabalho e Emprego**

- Entrada: recebimento de requerimento, recurso ou necessidade de administração do benefício.
- Atividade: gestão administrativa e execução das competências previstas normativamente.
- Saída: resultado de processamento, decisão administrativa ou informação necessária à execução financeira.
- Evidências: E01, E02, E24 e E30.

**A13 — Central 158**

- Entrada: cidadão procura atendimento do MTE.
- Atividade: orientação e agendamento de serviços ministeriais.
- Saída: informação prestada ou agendamento confirmado.
- Evidências: E20.

**A16 — CODEFAT**

- Entrada: necessidade de deliberação normativa ou financeira.
- Atividade: estabelecer normas e deliberar dentro das competências legais.
- Saída: resolução ou deliberação aplicável ao programa.
- Evidências: E01, E02 e E29.

**A17 — FAT**

- Condição de participação: necessidade de custeio do Programa Seguro-Desemprego.
- Função: fonte de financiamento.
- Resultado esperado: recursos disponibilizados para as finalidades legais.
- Evidência: E01.
- Natureza: fundo financeiro, não agente decisório autônomo.

**A18 — Dataprev**

- Entrada: demanda de processamento ou manutenção tecnológica.
- Atividade: operar soluções relacionadas ao processamento do benefício.
- Saída: resultado de processamento ou serviço tecnológico disponibilizado.
- Evidências: E07 e E08.
- Limitação: contrato atual e interface direta com a URA não identificados.

### **8.4. Proposta preliminar de mapa principal**

Os componentes centrais são cidadão, Caixa, URA, atendente, MTE, Central 158, Dataprev, CODEFAT e FAT. O diagrama não demonstra interfaces técnicas nem a sequência efetiva das operações.

Esse núcleo reúne nove elementos candidatos, dos quais sete representam pessoas, instituições, funções ou canais organizacionais e dois são recursos tecnológicos ou financeiros — URA e FAT.

A admissibilidade desses elementos como atores propriamente ditos deverá ser discutida na entrevista adversarial.

## **9. Relações e transferências revisadas**

### **9.1. Inventário de relações — F16 e N05**

Os identificadores da v2 foram preservados, acrescentando-se novas relações quando necessárias.

| ID  | Origem → Destino                                     | Natureza da relação                    | Confiança                           | Evidência                                    |
| --- | ---------------------------------------------------- | -------------------------------------- | ----------------------------------- | -------------------------------------------- |
| R01 | CODEFAT → FAT                                        | Governança                             | Alta                                | E01                                          |
| R02 | FAT → Programa Seguro-Desemprego                     | Financiamento                          | Alta                                | E01                                          |
| R03 | CODEFAT → MTE                                        | Regulamentação                         | Alta                                | E01, E02                                     |
| R04 | MTE → Caixa                                          | Contratação                            | Alta                                | E09                                          |
| R05 | Caixa → Cidadão                                      | Pagamento e atendimento                | Alta                                | E04, E09                                     |
| R06 | MTE → Dataprev                                       | Processamento contratado               | Média                               | E07, E08                                     |
| R07 | Bases oficiais → Sistema Seguro-Desemprego           | Aferição automatizada                  | Alta quanto à previsão normativa    | E02, art. 4º                                 |
| R08 | MTE → Caixa                                          | Informações para pagamento             | Alta quanto à previsão normativa    | E02                                          |
| R09 | Caixa → MTE                                          | Retorno de informações financeiras     | Alta quanto à previsão normativa    | E02                                          |
| R10 | Cidadão → Caixa                                      | Solicitação de atendimento             | Alta                                | E04                                          |
| R11 | URA → Atendente                                      | Roteamento                             | Baixa                               | Operação pendente                            |
| R12 | URA → Sistema Seguro-Desemprego                      | Consulta específica                    | Baixa                               | Interface não comprovada                     |
| R13 | Caixa → Fornecedor                                   | Contratação tecnológica efetiva        | Baixa                               | E11 comprova licitação, não contrato vigente |
| R14 | Atendente → Supervisor                               | Escalonamento                          | Baixa                               | Procedimento não localizado                  |
| R15 | Caixa → MTE                                          | Encaminhamento operacional             | Baixa                               | Transferência não comprovada                 |
| R16 | MTE → SRT/SINE                                       | Atendimento descentralizado            | Alta                                | E05                                          |
| R17 | TCU → MTE                                            | Controle externo                       | Alta                                | E08                                          |
| R18 | TCU → Caixa/CECOT                                    | Controle da Licitação 120/2024         | Alta                                | E11                                          |
| R19 | Cidadão → Ouvidoria Caixa                            | Manifestação                           | Média                               | E03                                          |
| R20 | Cidadão → Ouvidoria MTE                              | Manifestação                           | Alta                                | E13                                          |
| R21 | Empregador → eSocial                                 | Informações trabalhistas               | Alta                                | E18                                          |
| R22 | Empregador → Empregador Web                          | Transmissão de informações             | Alta                                | E19                                          |
| R23 | INSS → Pescador                                      | Competência residual                   | Alta                                | E28, E30                                     |
| R24 | Auditoria-Fiscal → Trabalhador resgatado             | Origem administrativa do benefício     | Alta                                | E01                                          |
| R25 | MGI → gov.br                                         | Governança da identidade digital       | Alta quanto à competência normativa | E25                                          |
| R26 | MTE → Pescador                                       | Gestão e habilitação                   | Alta                                | E24, E28–E30                                 |
| R27 | Ministério da Pesca → MTE                            | Disponibilização de informações do RGP | Alta                                | E24, art. 37                                 |
| R28 | Ministério do Meio Ambiente → Período de defeso      | Dependência normativa ambiental        | Baixa                               | Norma específica pendente                    |
| R29 | Cidadão → Facilita                                   | Agendamento                            | Alta                                | E20                                          |
| R30 | Recursos do FAT → Agente pagador                     | Disponibilização financeira funcional  | Média                               | E01, E09; circuito contábil pendente         |
| R31 | ANPD → Agentes de tratamento                         | Supervisão de dados pessoais           | Alta quanto à competência geral     | E26                                          |
| R32 | Senacon → Fornecedores sujeitos ao Decreto SAC       | Fiscalização                           | Alta quanto à competência geral     | E27, art. 23                                 |
| R33 | Sistema Seguro-Desemprego → Resultado da habilitação | Aferição automatizada dos requisitos   | Alta quanto à previsão normativa    | E02, art. 4º                                 |

As relações R31 e R32 não comprovam fiscalização efetiva sobre essa URA específica.

### **9.2. Transferências de responsabilidade**

| ID  | Transferência                           | Informação ou atividade entregue     | Situação                            |
| --- | --------------------------------------- | ------------------------------------ | ----------------------------------- |
| T01 | Cidadão → URA                           | Demanda de atendimento               | Fluxo específico pendente           |
| T02 | URA → Atendente                         | Chamada e eventual contexto          | Não comprovada                      |
| T03 | URA → Sistema                           | Consulta tecnológica                 | Não comprovada                      |
| T04 | Atendente → Supervisor                  | Exceção operacional                  | Não comprovada                      |
| T05 | Caixa → Canal digital                   | Possível orientação                  | Encaminhamento pendente             |
| T06 | Caixa → MTE                             | Possível demanda de concessão        | Transferência direta não comprovada |
| T07 | Central 158 → Unidade MTE               | Agendamento                          | Documentado — E20                   |
| T08 | MTE → Caixa                             | Informações necessárias ao pagamento | Previsão normativa — E02            |
| T09 | Caixa → MTE                             | Informações financeiras              | Previsão normativa — E02            |
| T10 | SAC → Ouvidoria                         | Manifestação não resolvida           | Procedimento específico pendente    |
| T11 | Empregador → Empregador Web             | Requerimento                         | Documentado — E19                   |
| T12 | Cidadão → Facilita                      | Solicitação de agendamento           | Documentado — E20                   |
| T13 | Ministério da Pesca → MTE               | Informações cadastrais do RGP        | Previsão legal — E24                |
| T14 | Beneficiário → Instância administrativa | Recurso por inconsistência           | Previsão normativa — E02            |

A identificação dos pontos de transferência não permite presumir que exista integração automática, compartilhamento integral de informações ou continuidade do atendimento entre todos os canais.

## **10. Registro consolidado das evidências**

### **10.1. Referências documentais — F09 e N04**

As referências são apresentadas individualmente, com identificador, endereço eletrônico e localização relevante. A data de referência da revisão é 24/11/2026.

**Legenda:**

- V3: fonte consultada nesta rodada.
- AUD: fonte confirmada em uma das auditorias.
- ANT: fonte herdada das versões anteriores, sem revalidação integral.
- PISTA: documento ou página que não comprova isoladamente a afirmação investigada.

| ID  | Fonte e endereço eletrônico                                                                                                                                                                                                    | Localização e finalidade                                              | Situação                 |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------- | ------------------------ |
| E01 | [Lei nº 7.998/1990](https://www.planalto.gov.br/ccivil_03/leis/l7998compilado.htm?utm_source=chatgpt.com)                                                                                                                      | Arts. 2º-C, 10, 11, 18 e 19; modalidades e financiamento              | ANT                      |
| E02 | [Resolução CODEFAT nº 957/2022](https://portalfat.trabalho.gov.br/wp-content/uploads/2026/09/Resolucao-no-957-de-21-de-setembro-de-2022-Revisao-do-SD.pdf?utm_source=chatgpt.com)                                              | Arts. 4º e 65; habilitação, processamento e informações financeiras   | V3, verificação seletiva |
| E03 | [Canais de atendimento Caixa](https://www.caixa.gov.br/atendimento/Paginas/default.aspx?utm_source=chatgpt.com)                                                                                                                | Página institucional; canais de atendimento                           | ANT                      |
| E04 | [FAQ Seguro-Desemprego — Caixa](https://www.caixa.gov.br/beneficios-trabalhador/seguro-desemprego/perguntas-frequentes/paginas/default.aspx?utm_source=chatgpt.com)                                                            | Informações sobre consultas e competências                            | AUD                      |
| E05 | [Solicitar Seguro-Desemprego](https://www.gov.br/pt-br/servicos/solicitar-o-seguro-desemprego?utm_source=chatgpt.com)                                                                                                          | Carta de serviço; requerimentos e canais                              | ANT                      |
| E06 | [Cadastrar recurso do Seguro-Desemprego](https://www.gov.br/pt-br/servicos/cadastrar-recurso-relativo-ao-seguro-desemprego?utm_source=chatgpt.com)                                                                             | Carta de serviço; contestação administrativa                          | ANT                      |
| E07 | [Seguro-Desemprego — Dataprev](https://dataprev.gov.br/solucoes/casos-de-sucesso/seguro-desemprego?utm_source=chatgpt.com)                                                                                                     | Documentação institucional; processamento                             | ANT                      |
| E08 | [Acórdão TCU nº 135/2024](https://pesquisa.apps.tcu.gov.br/doc/acordao-completo/135/2024/Plen%C3%A1rio?utm_source=chatgpt.com)                                                                                                 | Gestão e controles do benefício                                       | ANT                      |
| E09 | [Contratos do MTE — 2026](https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/licitacoes-e-contratos/pca/2026-1?utm_source=chatgpt.com)                                                                            | Registro do Contrato 07/2026                                          | AUD                      |
| E10 | [Contrato MTE nº 04/2023](https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/licitacoes-e-contratos/contratos/pdf/04_2023completo.pdf?utm_source=chatgpt.com)                                                     | Páginas 1 e 2, cláusulas 1ª a 3ª; Abono Salarial e remuneração da URA | V3                       |
| E11 | [Boletim TCU nº 129 — 26/07/2024](https://sessoes-portal-ms.apps.tcu.gov.br/api/sessoes/downloadPautaPublicada/22204?utm_source=chatgpt.com)                                                                                   | Página 140; Acórdão 1445/2024                                         | V3                       |
| E12 | [Portal de contratações Caixa](https://www.caixa.gov.br/licitacoes/transparencia/Paginas/default.aspx?utm_source=chatgpt.com)                                                                                                  | Localização de documentos contratuais                                 | PISTA                    |
| E13 | [Ouvidoria MTE](https://www.gov.br/trabalho-e-emprego/pt-br/canais_atendimento/ouvidoria/ouvidoria/formas-de-acesso?utm_source=chatgpt.com)                                                                                    | Formas de acesso                                                      | ANT                      |
| E14 | [Facilita — MTE](https://www.gov.br/trabalho-e-emprego/pt-br/servicos/facilita/?utm_source=chatgpt.com)                                                                                                                        | Apresentação institucional da plataforma                              | AUD                      |
| E15 | [Tratamento de dados pessoais — Dataprev](https://www.dataprev.gov.br/acesso-informacao-tratamento-de-dados-pessoais/tratamento-de-dados-pessoais-operados-pela-dataprev?utm_source=chatgpt.com)                               | Documentação institucional; finalidade específica a detalhar          | ANT                      |
| E16 | [Relatório de Gestão 2025 — INSS](https://www.gov.br/inss/pt-br/acesso-a-informacao/transparencia-e-prestacao-de-contas/pretacao-de-contas-anual/relatorio-de-gestao/copy_of_RelatoriodeGestao2025.pdf?utm_source=chatgpt.com) | Página 106; transição do Seguro-Defeso                                | ANT                      |
| E17 | [Solicitar Seguro-Defeso](https://www.gov.br/pt-br/servicos/solicitar-seguro-defeso-pescador-artesanal?utm_source=chatgpt.com)                                                                                                 | Atualização 20/10/2026; competências administrativas                  | AUD                      |
| E18 | [Portaria MTP nº 671/2021](https://www.gov.br/trabalho-e-emprego/pt-br/assuntos/legislacao/portarias-1/portarias-vigentes-3/PDFPortarian671de8denovembrode2021compilada03.06.2024.pdf?utm_source=chatgpt.com)                  | Art. 144; substituição do CAGED pelo eSocial                          | ANT                      |
| E19 | [Empregador Web](https://sd.maisemprego.trabalho.gov.br/?utm_source=chatgpt.com)                                                                                                                                               | Transmissão de requerimentos                                          | ANT                      |
| E20 | [Agendar atendimento presencial no MTE](https://www.gov.br/pt-br/servicos/agendar-atendimento-presencial-no-ministerio-do-trabalho-e-emprego?utm_source=chatgpt.com)                                                           | Atualização 10/11/2026; etapa 1                                       | V3                       |
| E21 | [Decreto nº 11.034/2022](https://planalto.gov.br/ccivil_03/_ato2019-2022/2022/decreto/d11034.htm?utm_source=chatgpt.com)                                                                                                       | Registro de revogação                                                 | AUD                      |
| E22 | [Novo CAGED — MTE](https://www.gov.br/trabalho-e-emprego/pt-br/assuntos/estatisticas-trabalho/o-pdet/o-que-e-o-novo-caged?utm_source=chatgpt.com)                                                                              | Fontes da produção estatística                                        | ANT                      |
| E23 | [Notícia institucional sobre Seguro-Defeso](https://www.gov.br/trabalho-e-emprego/pt-br/noticias-e-conteudo/2026/outubro/pescadores-tem-prazo-ampliado-para-solicitar-o-seguro-defeso/?utm_source=chatgpt.com)                 | 09/10/2026; competência do MTE                                        | AUD                      |
| E24 | [Lei nº 15.265/2025](https://planalto.gov.br/ccivil_03/_ato2023-2026/2025/lei/l15265.htm?utm_source=chatgpt.com)                                                                                                               | Arts. 37 e 41; competência e vigência                                 | V3                       |
| E25 | [Portarias MGI de 2025](https://www.gov.br/gestao/pt-br/acesso-a-informacao/institucional/atos-normativos/2025/2025-portarias?utm_source=chatgpt.com)                                                                          | Portaria SGD/MGI 11.229/2025                                          | V3                       |
| E26 | [Lei nº 13.709/2018 — LGPD](https://planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709compilado.htm?utm_source=chatgpt.com)                                                                                               | Art. 55-J; competências da ANPD                                       | V3                       |
| E27 | [Decreto nº 13.135/2026](https://legis.senado.leg.br/norma/44154496/publicacao/44157502?utm_source=chatgpt.com)                                                                                                                | Arts. 1º, 4º, 5º, 7º, 8º e 23 a 25; SAC                               | V3                       |
| E28 | [MP nº 1.323/2025](https://planalto.gov.br/ccivil_03/_ato2023-2026/2025/mpv/mpv1323impressao.htm?utm_source=chatgpt.com)                                                                                                       | Arts. 2º a 4º; transição do Seguro-Defeso                             | V3                       |
| E29 | [Resolução CODEFAT nº 1.027/2025](https://portalfat.trabalho.gov.br/wp-content/uploads/2026/10/Resolucao-no-1027-de-10.11.2025-SDPA.pdf?utm_source=chatgpt.com)                                                                | Art. 1º; regras de transição                                          | V3                       |
| E30 | [Lei nº 15.399/2026](https://legis.senado.leg.br/norma/43240303/publicacao/43249294?utm_source=chatgpt.com)                                                                                                                    | Arts. 2º e 3º; competências e transição                               | V3                       |

### **10.2. Limites da rastreabilidade**

A classificação V3 não significa que todos os dispositivos de cada documento tenham sido examinados integralmente.

Também não significa que uma norma comprove sua implementação operacional.

Os documentos herdados da v1 e da v2 foram mantidos para preservar o histórico da pesquisa, mas devem ser diferenciados das fontes efetivamente revalidadas.

## **11. Lacunas remanescentes e preparação para a entrevista adversarial**

### **11.1. Registro de lacunas**

A pesquisa documental avançou na identificação das competências institucionais, mas a operação concreta da central continua sendo a principal área de incerteza.

| ID  | Lacuna                                                              | Situação na v3                                          | Prioridade |
| --- | ------------------------------------------------------------------- | ------------------------------------------------------- | ---------- |
| L01 | Árvore de menus da URA                                              | Aberta                                                  | Alta       |
| L02 | Funcionalidades específicas                                         | Aberta                                                  | Alta       |
| L03 | Identificação do cidadão                                            | Aberta                                                  | Alta       |
| L04 | Consulta automatizada de parcelas                                   | Aberta                                                  | Alta       |
| L05 | Unidade gestora da central                                          | Aberta                                                  | Alta       |
| L06 | Modelo próprio, terceirizado ou híbrido                             | Aberta                                                  | Alta       |
| L07 | Fornecedor tecnológico atual                                        | Aberta                                                  | Alta       |
| L08 | Remuneração específica da URA                                       | Aberta                                                  | Alta       |
| L09 | Sistemas consultados por atendentes                                 | Aberta                                                  | Alta       |
| L10 | Integração Caixa–Dataprev                                           | Aberta                                                  | Alta       |
| L11 | Transferência direta ao MTE                                         | Aberta                                                  | Alta       |
| L12 | Unidade gestora atual do benefício                                  | Aberta                                                  | Média      |
| L13 | Indicadores de qualidade, tempo e resolução                         | Aberta                                                  | Média      |
| L14 | Responsabilidades específicas sobre dados pessoais                  | Aberta                                                  | Média      |
| L15 | Escalonamento operacional                                           | Aberta                                                  | Média      |
| L16 | Encaminhamentos sem resolução                                       | Aberta                                                  | Média      |
| L17 | Contrato atualizado MTE–Dataprev                                    | Aberta                                                  | Alta       |
| L18 | Acórdão correto do TCU                                              | Resolvida — E11                                         | —          |
| L19 | Horários atuais da central                                          | Aberta                                                  | Média      |
| L20 | Relação entre contratos de pagamento                                | Parcialmente resolvida; objetos distintos identificados | Alta       |
| L21 | Discussão documental sobre remuneração                              | Parcialmente resolvida; identificado objeto distinto    | Alta       |
| L22 | Automação versus intervenção humana                                 | Parcialmente resolvida — E02                            | Alta       |
| L23 | Aplicabilidade das normas do SAC                                    | Parcialmente resolvida — E27                            | Média      |
| L24 | Atendimento mediante representação                                  | Aberta                                                  | Média      |
| L25 | Governança detalhada do eSocial                                     | Aberta                                                  | Média      |
| L26 | Governança da identidade digital                                    | Parcialmente resolvida — E25                            | Média      |
| L27 | Participação da CECOT                                               | Resolvida quanto à licitação — E11                      | —          |
| L28 | Gestão e utilização operacional do CNIS                             | Parcialmente resolvida — E02                            | Média      |
| L29 | Circuito contábil de disponibilização de recursos ao agente pagador | Aberta                                                  | Alta       |

### **11.2. Estratégias de validação**

| Questão                      | Evidência necessária                                                  |
| ---------------------------- | --------------------------------------------------------------------- |
| Funcionamento da URA         | Manual público de atendimento ou documentação institucional.          |
| Unidade responsável          | Estrutura organizacional e atribuições internas da Caixa.             |
| Fornecedor                   | Resultado da Licitação 120/2024, contrato e eventuais aditivos.       |
| Financiamento do atendimento | Contrato 07/2026 completo, projeto básico e planilhas de remuneração. |
| Integração tecnológica       | Documentação oficial dos serviços e sistemas envolvidos.              |
| Fluxo financeiro             | Instrumentos de execução orçamentária e financeira do programa.       |
| Aplicação das normas de SAC  | Manifestação jurídica ou regulatória específica.                      |
| Desempenho do serviço        | Indicadores oficiais de atendimento, resolução e satisfação.          |

Na ausência desses documentos, as informações correspondentes não deverão ser convertidas em afirmações categóricas para a matriz de responsabilidades.

### **11.3. Questões prioritárias para a etapa&#x20;**`/grill-me`

**Roteiro preparatório da entrevista**

0 de 15 questões examinadas

## **0%**

1\. Qual é o evento que inicia a jornada e qual resultado determina seu encerramento?

2\. O mapa contemplará todas as modalidades ou priorizará o trabalhador formal?

3\. Quais atores são indispensáveis para resolver uma demanda apresentada à URA?

4\. Caixa e MTE devem aparecer como instituições únicas ou subdivididas em unidades?

5\. A URA deve ser representada como ator ou como recurso tecnológico?

6\. O FAT deve aparecer como ator ou como fonte de financiamento?

7\. Quem possui responsabilidade pela operação do canal telefônico?

8\. Quem estabelece as regras de habilitação e quem realiza o processamento?

9\. Qual é a participação comprovada da Dataprev e qual permanece hipotética?

10\. O atendimento humano precisa ser representado separadamente da Caixa?

11\. Existe transferência de responsabilidade entre Caixa e MTE ou apenas indicação de outro canal?

12\. Central 158 e Facilita são atores independentes ou canais subordinados ao MTE?

13\. Em quais situações o INSS e a Auditoria-Fiscal do Trabalho precisam aparecer?

14\. Quais fornecedores e unidades internas podem ser mantidos sem confirmação documental?

15\. Quais papéis podem ser atribuídos na matriz RACI sem transformar inferências em fatos?

&#x20;Copiar roteiro

Essas questões constituem subsídios preparatórios. Não representam a realização da entrevista nem substituem o arquivo `C_grill_transcript.md`.

## **12. Conclusão da pesquisa v3 — N08**

O Atendimento ao Seguro-Desemprego pela URA da Caixa constitui um serviço cuja prestação depende da articulação entre atendimento ao cidadão, governança pública, execução financeira e processamento de informações.

A pesquisa permite estabelecer as seguintes conclusões:

**Primeira:** a Caixa possui responsabilidade institucional pelo canal telefônico e pela execução financeira contratada, mas não concentra as competências administrativas relativas à habilitação do benefício.

**Segunda:** o MTE é responsável pela administração do benefício, devendo ser consideradas as particularidades de cada modalidade e as competências residuais do INSS na transição do Seguro-Defeso.

**Terceira:** a Dataprev e os registros administrativos constituem dependências tecnológicas relevantes, havendo previsão normativa expressa de aferição automatizada dos requisitos de habilitação.

**Quarta:** o CODEFAT e o FAT desempenham funções distintas de governança e financiamento. Seus papéis não devem ser confundidos com a execução do atendimento.

**Quinta:** a contratação de infraestrutura tecnológica de contact center pela Caixa possui antecedente documental confirmado, mas a composição atual da operação e a identidade de seus fornecedores permanecem desconhecidas.

**Sexta:** a existência de canais alternativos, como Central 158, Facilita e serviços digitais, não comprova integração operacional entre esses canais e a URA da Caixa.

**Sétima:** a remuneração da URA identificada no Contrato nº 04/2023 refere-se ao Abono Salarial e não deve ser atribuída ao Seguro-Desemprego.

O mapa definitivo deverá representar essas distinções, privilegiando os atores necessários à compreensão da jornada e evitando a inclusão indiscriminada de instituições sem relação funcional demonstrada.

## **13. Verificação final do tratamento da auditoria**

Resolvidos

# **15**

Parciais

# **10**

Em aberto

# **1**

TodosResolvidosParciaisAbertos

**F01**

Acórdão correto localizado

**F02**

Agendamento pelo Facilita comprovado

**F08**

Competência da ANPD fundamentada

**F09**

Referências individualizadas; fontes antigas não integralmente verificadas

**F11**

Critérios e fichas prioritárias aprimorados

**F12**

Objeto do contrato de 2023 esclarecido

**F13**

Cláusulas localizadas; financiamento da URA específica pendente

**F16**

Relações e graus de confiança revisados

**F21**

Governança do gov.br fundamentada

**B1**

Transição do Seguro-Defeso fundamentada

**B2**

Data, publicação e vigência do decreto confirmadas

**B3**

Funcionalidade do Facilita demonstrada

**N01**

MP, resolução e legislação posterior identificadas

**N02**

Novo decreto examinado; incidência específica pendente

**N03**

MPA fundamentado; participação do MMA rebaixada

**N04**

Links restaurados

**N05**

Fluxo financeiro corrigido conceitualmente

**N06**

Classificação de F06 corrigida

**N07**

Critério de escopo aplicado aos 54 elementos

**N08**

Metacomentários inadequados retirados

**D1**

Operação específica da URA não comprovada

**D2**

Financiamento específico da URA não comprovado

**D3**

Acórdão localizado; fornecedor atual pendente

**D4**

Circuito financeiro funcional representado

**D5**

Aplicabilidade específica do SAC pendente

**D6**

Proposta de seleção dos atores apresentada

Contagem dos 26 pontos tratados nesta rodada, incluindo ressalvas e pontos abertos que possuem sobreposição temática.

O tratamento das falhas foi realizado mediante correção de afirmações, complementação documental, revisão de classificações ou reconhecimento das lacunas remanescentes.

A pesquisa não realizou entrevistas, não acessou sistemas internos da Caixa e não comprovou experimentalmente o funcionamento da URA.

As fichas detalhadas desta versão concentram-se nos elementos prioritários. Os demais permanecem no inventário classificado, sem fichas individuais completas. A seleção em camadas constitui uma proposta metodológica adotada pelo pesquisador e deverá ser validada posteriormente.

A versão 3 está concluída como relatório de pesquisa documental, mas não representa um diagnóstico operacional integralmente validado.

## **Próxima etapa do exercício**

O conteúdo acima corresponde ao relatório:

`B_relatorio_assistente_v3.md`

Com isso, você conclui o ciclo de pesquisa e auditoria da Parte B:

Pesquisa inicial — B_relatorio_assistente_v1.md

Primeira auditoria — B_relatorio_auditoria_v1.md

Pesquisa revisada — B_relatorio_assistente_v2.md

Segunda auditoria — B_relatorio_auditoria_v2.md

Pesquisa final — B_relatorio_assistente_v3.md

**Parte C — Entrevista adversarial com grill-me**

Próxima etapa

Construção do mapa definitivo de atores

O relatório foi entregue nesta conversa, não como arquivo `.md` para download. Ao salvá-lo, preserve as tabelas, os identificadores das falhas, os endereços das fontes e as ressalvas documentais. Esses elementos são essenciais para demonstrar a evolução entre as versões exigidas pelo professor.