# A — Meta-prompt

- **Assistente usado:** ChatGPT (assistente 1)
- **Serviço público:** Atendimento ao Seguro-Desemprego pela URA (Unidade de Resposta Audível) da Caixa Econômica Federal
- **Canal:** central telefônica (URA + atendimento humano)
- **Órgãos envolvidos:** Caixa Econômica Federal (agente pagador) e Ministério do Trabalho e Emprego (gestor do benefício)

---

## Meta-prompt enviado ao assistente 1

Aja como engenheiro de prompts. A partir do objetivo e do contexto abaixo, gere um prompt estruturado — com **papel, contexto, entradas, passos, formato de saída e critérios de qualidade** — para um assistente de deep research realizar uma pesquisa na web. Não faça a pesquisa agora: quero apenas o prompt, pronto para ser colado em outra conversa com Deep Research ativado.

**Objetivo:**
Quero um prompt que ajude a diagnosticar o Atendimento ao Seguro-Desemprego pela URA da Caixa, começando por mapear quem são os atores da jornada e qual o papel de cada um. Na jornada, o cidadão liga para a central telefônica, navega por menus de voz, é roteado entre canais automatizados e atendentes humanos e, eventualmente, obtém uma resposta: consulta de status do benefício, informação sobre parcelas, agendamento ou encaminhamento a uma agência ou posto físico. Não quero só quem aparece no ponto de contato com o cidadão. Quero também os atores "invisíveis": quem normatiza, quem financia, quem opera os sistemas por trás, quem fornece a tecnologia da URA e da central, quem supervisiona e audita, quem faz o controle externo e por onde o cidadão reclama. O resultado da pesquisa não é o produto final. Ele vai servir de contexto para uma etapa seguinte, em que farei uma entrevista adversarial com outro agente de IA para decidir o mapa final de atores (tabela RACI ou diagrama). Por isso, prefiro uma pesquisa ampla, bem documentada e honesta sobre o que é incerto a uma resposta curta e confiante.

**Contexto que já tenho (a verificar, não tratar como fato):**
- O Seguro-Desemprego está previsto na Lei 7.998/1990 e é custeado pelo Fundo de Amparo ao Trabalhador (FAT), cujo conselho deliberativo é o CODEFAT.
- O Ministério do Trabalho e Emprego responde pela política e pela habilitação do benefício; a Caixa atua como agente pagador.
- O requerimento hoje é feito sobretudo pela Carteira de Trabalho Digital / gov.br, além das unidades do SINE e das superintendências regionais do trabalho.
- A Dataprev aparece associada ao processamento de dados do benefício.
- A Caixa mantém uma central telefônica para benefícios sociais com menus automatizados, mas não sei qual é o número, se a operação é terceirizada nem quais opções existem para o Seguro-Desemprego.
- Não sei se a URA resolve algo sozinha (status, parcelas) ou se apenas informa e encaminha.

**O que o prompt gerado deve exigir do assistente de pesquisa:**
1. Fontes verificáveis, com link (legislação, resoluções do CODEFAT, páginas oficiais da Caixa e do MTE, relatórios do TCU e da CGU, contratos e licitações públicas, notícias), e distinção explícita entre fato confirmado, inferência e lacuna.
2. Lista de atores organizada por categorias — por exemplo: demandantes, atendimento automatizado, atendimento humano, gestão e supervisão, sistemas e fornecedores de tecnologia, normatização e financiamento, controle e ouvidoria.
3. Para cada ator: papel na jornada, em que momento entra e sai, o que decide ou executa, com quem interage e qual a fonte.
4. Os pontos de transferência da jornada: onde o cidadão sai da URA e vai para um atendente, para o aplicativo ou para a agência.
5. Uma seção final de lacunas e perguntas em aberto que eu precise decidir depois.

Escreva o prompt em português.

---

## Apêndice — Prompt gerado pelo assistente 1 a partir deste meta-prompt

> O texto abaixo é a resposta do ChatGPT ao meta-prompt. Ele foi colado, sem alterações, em uma nova conversa com Pesquisa aprofundada ativada e originou o `B_relatorio_assistente_v1.md`.

### Deep Research — Mapeamento de atores da jornada de Atendimento ao Seguro-Desemprego pela URA da Caixa

#### 1. Papel

Atue como pesquisador sênior especializado em:

- Políticas públicas brasileiras;
- Governança e arranjos institucionais;
- Mapeamento de stakeholders;
- Arquitetura de serviços públicos;
- Centrais de atendimento e Unidade de Resposta Audível (URA);
- Sistemas de informação governamentais;
- Contratações públicas;
- Auditoria, fiscalização e controle da administração pública.

Adote uma postura investigativa, crítica, independente e orientada por evidências. Não presuma que as responsabilidades formalmente atribuídas às instituições correspondam integralmente à operação prática dos serviços.

#### 2. Objetivo da pesquisa

Realize uma pesquisa aprofundada na web para identificar, caracterizar e documentar os atores envolvidos direta ou indiretamente na jornada de Atendimento ao Seguro-Desemprego pela URA da Caixa Econômica Federal.

A pergunta central da pesquisa é:

**Quem participa, viabiliza, condiciona, governa, executa, supervisiona ou fiscaliza essa jornada de atendimento e quais são as responsabilidades e relações de dependência entre esses atores?**

A investigação deve contemplar tanto os atores visíveis ao cidadão quanto aqueles que atuam nos bastidores da prestação do serviço.

O resultado será utilizado como insumo para uma etapa posterior de entrevista adversarial com outro agente de inteligência artificial, destinada a questionar, validar e refinar o mapa de atores, que poderá assumir a forma de uma matriz RACI ou de um diagrama de relações.

Portanto, não produza uma matriz RACI definitiva nesta etapa. Priorize a abrangência da investigação, a rastreabilidade das evidências e a explicitação das incertezas.

#### 3. Contexto e delimitação do objeto

Considere como jornada de referência a situação em que um cidadão busca atendimento telefônico relacionado ao Seguro-Desemprego por meio de uma central da Caixa.

Nessa jornada hipotética, o cidadão pode:

1. Identificar um canal telefônico de atendimento;
2. Ligar para a central;
3. Navegar por menus automatizados de voz;
4. Informar dados ou realizar procedimentos de identificação;
5. Consultar informações sobre o benefício;
6. Receber uma resposta automatizada;
7. Ser transferido para atendimento humano;
8. Ser orientado a utilizar outro canal digital;
9. Ser encaminhado para uma agência, unidade ou posto físico;
10. Registrar uma reclamação ou buscar outra instância de atendimento.

Essa sequência é uma hipótese inicial de jornada, não uma descrição comprovada da operação atual.

Investigue quais dessas etapas efetivamente existem, quais são alternativas, quais não são suportadas pelo canal e quais permanecem desconhecidas.

O foco principal é a jornada de atendimento telefônico pela Caixa, mas a pesquisa deve abranger os atores externos que influenciam sua execução, inclusive aqueles responsáveis pela concessão, processamento, pagamento, regulamentação, financiamento e fiscalização do benefício.

Evite expandir a investigação para toda a política pública do Seguro-Desemprego quando não houver relação identificável com a jornada analisada.

#### 4. Entradas e hipóteses iniciais

Utilize as informações abaixo exclusivamente como hipóteses de partida. Todas devem ser verificadas, corrigidas, complementadas ou refutadas mediante pesquisa documental.

- O Seguro-Desemprego está previsto na Lei nº 7.998/1990 e é custeado pelo Fundo de Amparo ao Trabalhador (FAT), cujo conselho deliberativo é o CODEFAT.
- O Ministério do Trabalho e Emprego (MTE) responde pela política pública e pela habilitação do benefício, enquanto a Caixa atua como agente pagador.
- O requerimento é realizado principalmente pela Carteira de Trabalho Digital e pelos serviços do gov.br, além das unidades do SINE e das superintendências regionais do trabalho.
- A Dataprev está associada ao processamento de dados e à operação de sistemas relacionados ao benefício.
- A Caixa mantém uma central telefônica para benefícios sociais com menus automatizados.
- Não está confirmado qual número telefônico atende especificamente às demandas relacionadas ao Seguro-Desemprego.
- Não está confirmado se a operação da central é própria, terceirizada ou híbrida.
- Não estão confirmadas as funcionalidades disponíveis na URA para o Seguro-Desemprego.
- Não está confirmado se a URA consulta dados individualizados, informa status e parcelas, realiza agendamentos ou apenas fornece orientações e encaminhamentos.

Não limite a descoberta de atores às instituições mencionadas nessas hipóteses.

#### 5. Etapas da investigação

##### Etapa 1 — Verificar a existência e o escopo do serviço

Identifique:

- Os números telefônicos oficiais relacionados ao atendimento do Seguro-Desemprego;
- A instituição responsável por cada canal;
- A denominação oficial das centrais;
- Os públicos atendidos;
- Os horários de funcionamento;
- As funcionalidades documentadas;
- A existência de atendimento automatizado e humano;
- As opções de menu da URA, quando publicamente documentadas;
- Os limites de atuação de cada canal;
- A relação entre as centrais da Caixa e os canais do MTE.

Verifique se existe efetivamente uma jornada de atendimento ao Seguro-Desemprego pela URA da Caixa nos termos apresentados no contexto.

Caso a premissa inicial esteja incorreta, incompleta ou desatualizada, explicite isso e reconstrua o objeto da pesquisa com base nas evidências encontradas.

Diferencie atendimento sobre concessão e habilitação do benefício de atendimento sobre pagamento, disponibilização e recebimento de parcelas.

##### Etapa 2 — Investigar o arranjo normativo e institucional

Pesquise a legislação, os regulamentos e os instrumentos administrativos que definem as competências relacionadas ao Seguro-Desemprego.

Investigue:

- Quem formula a política pública;
- Quem regulamenta o benefício;
- Quem define critérios de elegibilidade;
- Quem financia sua execução;
- Quem administra os recursos;
- Quem analisa e habilita requerimentos;
- Quem autoriza, processa e executa pagamentos;
- Quem estabelece as obrigações dos agentes envolvidos;
- Quem define ou supervisiona os padrões de atendimento ao cidadão;
- Quais instrumentos formalizam as relações entre as instituições.

Diferencie competências legais, responsabilidades contratuais, atribuições administrativas e atividades efetivamente executadas.

##### Etapa 3 — Reconstruir a jornada operacional

Reconstrua a jornada de atendimento com base nas informações disponíveis, desde a necessidade inicial do cidadão até a resolução, o encaminhamento ou a interrupção do atendimento.

Para cada etapa, identifique:

- A necessidade do cidadão;
- O canal utilizado;
- Os atores participantes;
- As atividades realizadas;
- As decisões tomadas;
- Os sistemas ou informações necessários;
- As dependências institucionais e tecnológicas;
- Os possíveis resultados;
- O próximo ponto da jornada.

Investigue separadamente, quando aplicável, os seguintes cenários:

- Consulta de situação do requerimento;
- Consulta de status do benefício;
- Consulta de parcelas;
- Consulta de datas ou condições de pagamento;
- Problemas no recebimento;
- Divergências cadastrais;
- Benefício bloqueado, suspenso ou indeferido;
- Orientação sobre recursos administrativos;
- Agendamento;
- Encaminhamento para outros canais.

Não presuma que todos esses serviços sejam disponibilizados pela Caixa ou pela URA.

##### Etapa 4 — Identificar e categorizar os atores

Realize um levantamento amplo de atores, utilizando inicialmente as categorias abaixo.

**A. Demandantes e beneficiários**

Cidadãos, trabalhadores, beneficiários, representantes e outros possíveis demandantes do serviço.

**B. Atendimento automatizado**

URA, plataformas de atendimento automatizado, mecanismos de identificação, roteamento e autosserviço.

**C. Atendimento humano**

Atendentes, operadores, equipes especializadas, unidades presenciais e demais responsáveis pelo contato direto com o cidadão.

**D. Gestão e supervisão operacional**

Gestores de canais, responsáveis pelo serviço, supervisores, equipes de qualidade, gestores de contratos e unidades organizacionais responsáveis pela operação.

**E. Sistemas, dados e fornecedores de tecnologia**

Instituições processadoras de dados, operadores de sistemas, fornecedores de telefonia, plataformas de contact center, empresas terceirizadas, integradores e responsáveis pelas interfaces tecnológicas.

**F. Normatização e governança**

Órgãos formuladores da política pública, instâncias deliberativas, autoridades normativas e instituições responsáveis pelas regras do benefício.

**G. Financiamento e execução financeira**

Fundos, gestores de recursos, agentes pagadores e instituições envolvidas na execução financeira.

**H. Controle, auditoria e fiscalização**

Instâncias de controle interno e externo, auditorias, órgãos fiscalizadores e entidades responsáveis pela supervisão da conformidade.

**I. Ouvidoria, reclamação e resolução de conflitos**

Ouvidorias, serviços de atendimento ao consumidor, plataformas de manifestações, instâncias administrativas de recurso e demais canais pertinentes.

**J. Atores transversais ou complementares**

Outros atores identificados durante a pesquisa que não se enquadrem adequadamente nas categorias anteriores.

As categorias são orientativas, não exaustivas nem mutuamente exclusivas.

Diferencie explicitamente:

- Instituições;
- Unidades organizacionais;
- Papéis funcionais;
- Pessoas ou grupos de pessoas;
- Sistemas e componentes tecnológicos;
- Canais de atendimento;
- Fundos e instrumentos institucionais.

Não atribua responsabilidade decisória a um sistema tecnológico quando essa responsabilidade pertencer a uma instituição, unidade ou agente humano.

Identifique também os atores candidatos cuja participação seja plausível, mas ainda não comprovada.

##### Etapa 5 — Investigar os atores invisíveis e a cadeia de fornecimento

Dedique atenção especial aos atores que não aparecem diretamente na interação com o cidadão.

Investigue, na medida em que existam evidências públicas:

- Quem é o proprietário institucional do serviço;
- Quem administra a central telefônica;
- Quem define os menus e fluxos da URA;
- Quem estabelece os procedimentos e scripts de atendimento;
- Quem fornece a infraestrutura de telefonia;
- Quem fornece ou mantém a plataforma de atendimento;
- Quem contrata e emprega os atendentes;
- Quem supervisiona a operação;
- Quem mantém as bases de dados consultadas;
- Quem é responsável pela integração entre sistemas;
- Quem autoriza o acesso às informações do benefício;
- Quem define os indicadores de desempenho;
- Quem fiscaliza os contratos;
- Quem responde por falhas, indisponibilidades e informações incorretas;
- Quem responde pelo tratamento e pela proteção dos dados pessoais.

Pesquise contratos, editais, termos de referência, licitações, aditivos, documentos de governança, relatórios institucionais e auditorias.

Ao identificar fornecedores, verifique:

- Razão social;
- Objeto da contratação;
- Instituição contratante;
- Número do contrato ou processo;
- Período de vigência;
- Escopo dos serviços contratados;
- Relação comprovada ou potencial com o atendimento investigado.

Não conclua que uma empresa opera a URA do Seguro-Desemprego apenas porque possui um contrato genérico de atendimento com a Caixa.

Considere a possibilidade de coexistência de diferentes fornecedores, contratos, unidades operacionais e soluções tecnológicas.

##### Etapa 6 — Mapear relações e pontos de transferência

Identifique os pontos de transferência de atendimento, informação, execução ou responsabilidade entre atores.

Investigue especialmente:

- URA para atendente humano;
- URA para aplicativo ou portal;
- URA para atendimento presencial;
- Atendente humano para equipe especializada;
- Caixa para MTE;
- Caixa para outros canais institucionais;
- Atendimento para ouvidoria;
- Central de atendimento para sistemas de retaguarda;
- Gestores operacionais para fornecedores;
- Instituições executoras para instâncias de controle.

Para cada transferência, identifique:

- Ator de origem;
- Ator de destino;
- Evento ou condição que provoca a transferência;
- Finalidade;
- Informações ou demandas transferidas;
- Canal ou mecanismo utilizado;
- Responsabilidade antes e depois da transferência;
- Evidência disponível;
- Incertezas existentes.

Diferencie transferência efetiva de atendimento de simples orientação para que o cidadão procure outro canal por conta própria.

Investigue também situações em que o cidadão possa ser encaminhado repetidamente entre instituições sem resolução clara da demanda, desde que existam evidências ou que a situação seja explicitamente apresentada como hipótese.

##### Etapa 7 — Investigar controle, responsabilização e reclamações

Identifique quem pode supervisionar, fiscalizar, auditar ou receber manifestações relacionadas à jornada.

Investigue a pertinência de instituições e mecanismos como:

- Controle interno da Caixa;
- Controle interno do MTE;
- CODEFAT;
- Controladoria-Geral da União (CGU);
- Tribunal de Contas da União (TCU);
- Ouvidoria da Caixa;
- Ouvidoria do MTE;
- Plataforma Fala.BR;
- Instâncias administrativas de recurso;
- Autoridades relacionadas à proteção de dados pessoais;
- Outros mecanismos de controle ou responsabilização pertinentes.

Verifique individualmente a competência e a relação de cada ator com o objeto pesquisado.

Não confunda fiscalização da política pública, fiscalização contratual, supervisão operacional, reclamação sobre atendimento e recurso contra decisão administrativa.

##### Etapa 8 — Triangular evidências e identificar contradições

Compare as informações encontradas em diferentes fontes.

Procure divergências entre:

- Competências legais e práticas operacionais;
- Documentação institucional e contratos;
- Serviços anunciados e funcionalidades documentadas;
- Contratos históricos e contratos vigentes;
- Atribuições da Caixa e do MTE;
- Responsabilidades de fornecedores e instituições contratantes;
- Relatos de usuários e informações oficiais.

Apresente as contradições relevantes sem resolvê-las artificialmente.

Quando não houver evidência suficiente, mantenha a questão em aberto.

#### 6. Estratégia de busca e fontes

Priorize fontes primárias, oficiais, verificáveis e atualizadas.

Consulte, quando pertinentes:

- Portal da Legislação e Presidência da República;
- Diário Oficial da União;
- Leis, decretos, portarias e resoluções do CODEFAT;
- Páginas oficiais da Caixa Econômica Federal;
- Páginas oficiais do Ministério do Trabalho e Emprego;
- Portal gov.br;
- Documentação institucional da Dataprev;
- Portal Nacional de Contratações Públicas (PNCP);
- Compras.gov.br;
- Portais de licitações, contratos e transparência da Caixa;
- Portal da Transparência;
- Relatórios, acórdãos e auditorias do TCU;
- Relatórios e auditorias da CGU;
- Cartas de serviços ao cidadão;
- Relatórios de gestão;
- Documentos técnicos e manuais publicamente disponíveis;
- Documentos de ouvidoria;
- Notícias institucionais;
- Notícias jornalísticas de veículos confiáveis;
- Estudos acadêmicos pertinentes.

Utilize fontes secundárias como complemento, especialmente para identificar pistas, problemas operacionais e possíveis contradições.

Relatos de usuários podem indicar problemas ou hipóteses investigativas, mas não devem ser tratados isoladamente como comprovação de uma regra operacional.

Realize buscas com diferentes combinações de termos, incluindo variações como:

- Seguro-Desemprego;
- Atendimento Caixa;
- Benefícios sociais;
- URA;
- Central de atendimento;
- Atendimento telefônico;
- Teleatendimento;
- Contact center;
- Call center;
- Agente pagador;
- Processamento de benefícios;
- FAT;
- CODEFAT;
- Dataprev;
- Contratação de serviços de atendimento;
- Fiscalização contratual;
- Ouvidoria;
- Integração de sistemas.

Registre a data de referência da pesquisa e diferencie informações atuais de registros históricos.

#### 7. Classificação das evidências

Classifique cada afirmação materialmente relevante utilizando uma das seguintes categorias:

| Classificação | Definição |
|---|---|
| Fato confirmado | Afirmação diretamente sustentada por evidência documental identificável e pertinente. |
| Inferência fundamentada | Conclusão indireta derivada de evidências disponíveis, acompanhada da explicação do raciocínio. |
| Hipótese não verificada | Possibilidade plausível cuja sustentação documental ainda é insuficiente. |
| Lacuna de informação | Informação necessária que não foi localizada ou não pôde ser determinada. |
| Evidência contraditória | Situação em que fontes relevantes apresentam informações incompatíveis ou aparentemente divergentes. |

Atribua também um grau de confiança — alto, médio ou baixo — acompanhado de justificativa sucinta.

A classificação deve ser aplicada às afirmações sobre os atores e seus papéis, e não apenas ao ator como um todo.

Uma instituição pode ter existência e competência legal confirmadas, mas possuir participação operacional na URA ainda não demonstrada.

Não utilize ausência de evidência como evidência de ausência.

#### 8. Formato de saída

Produza um relatório de pesquisa em português brasileiro, estruturado nas seções abaixo.

##### 8.1. Sumário executivo

Apresente:

- Principais descobertas;
- Configuração institucional identificada;
- Situação da premissa inicial sobre a URA da Caixa;
- Principais atores confirmados;
- Principais incertezas;
- Limitações da pesquisa.

##### 8.2. Validação das hipóteses iniciais

Utilize a seguinte estrutura:

| ID | Hipótese inicial | Resultado da verificação | Evidência | Fonte | Observações |
|---|---|---|---|---|---|

Classifique o resultado como confirmado, parcialmente confirmado, refutado ou inconclusivo.

##### 8.3. Contexto normativo e institucional

Apresente as bases legais, os instrumentos administrativos e a distribuição de competências entre as instituições.

Sempre que possível, indique os artigos, dispositivos ou trechos específicos que fundamentam as atribuições identificadas.

##### 8.4. Reconstrução da jornada de atendimento

Utilize a seguinte estrutura:

| Etapa | Necessidade do cidadão | Canal | Atividade | Atores envolvidos | Sistema ou informação | Resultado possível | Evidência |
|---|---|---|---|---|---|---|---|

Diferencie etapas confirmadas de etapas hipotéticas.

Apresente ramificações relevantes da jornada, sem forçar a representação de um fluxo linear único.

##### 8.5. Inventário ampliado de atores

Organize os atores por categoria e atribua um identificador único a cada um, como A01, A02 e A03.

Utilize a seguinte estrutura:

| ID | Ator | Categoria | Natureza do ator | Papel na jornada | Participação direta ou indireta | Situação da evidência | Fontes |
|---|---|---|---|---|---|---|---|

Inclua atores confirmados e atores candidatos, distinguindo-os claramente.

##### 8.6. Ficha detalhada de cada ator

Para cada ator identificado, apresente:

- Identificador;
- Nome oficial;
- Sigla, quando aplicável;
- Categoria principal e categorias secundárias;
- Natureza do ator;
- Instituição à qual está vinculado;
- Papel na jornada;
- Competência formal;
- Atuação operacional identificada;
- Momento ou condição de entrada na jornada;
- Momento ou condição de saída da jornada;
- Decisões que toma;
- Atividades que executa;
- Informações que recebe;
- Informações que produz ou disponibiliza;
- Sistemas e recursos utilizados ou administrados;
- Atores com os quais interage;
- Dependências em relação a outros atores;
- Responsabilidades de gestão ou supervisão;
- Fundamentação normativa, contratual ou documental;
- Classificação das evidências;
- Grau de confiança;
- Lacunas específicas.

Para atores transversais, indique quando não existe um ponto único de entrada ou saída da jornada.

Utilize os mesmos identificadores em todo o relatório para permitir o cruzamento posterior das informações.

##### 8.7. Inventário de relações entre atores

| ID da relação | Ator de origem | Ator de destino | Tipo de relação | Objeto da relação | Evidência | Grau de confiança |
|---|---|---|---|---|---|---|

Considere relações de:

- Normatização;
- Financiamento;
- Contratação;
- Execução;
- Supervisão;
- Fiscalização;
- Prestação de contas;
- Compartilhamento de dados;
- Integração tecnológica;
- Encaminhamento;
- Atendimento;
- Dependência operacional.

##### 8.8. Pontos de transferência da jornada

| ID | Origem | Destino | Condição de transferência | Finalidade | Mecanismo | Mudança de responsabilidade | Evidência | Lacunas |
|---|---|---|---|---|---|---|---|---|

Destaque transferências críticas, responsabilidades indefinidas e dependências cuja falha possa comprometer a resolução da demanda do cidadão.

##### 8.9. Sistemas, infraestrutura e fornecedores

Apresente um inventário específico dos sistemas, plataformas, componentes tecnológicos e fornecedores identificados.

Diferencie:

- Proprietário institucional;
- Responsável pela gestão;
- Operador;
- Desenvolvedor;
- Fornecedor;
- Mantenedor;
- Usuário institucional;
- Responsável pelos dados.

Inclua os dados das contratações públicas localizadas e explicite quando não for possível vincular determinada contratação especificamente à jornada do Seguro-Desemprego.

##### 8.10. Controle, fiscalização e reclamações

Apresente os mecanismos de controle e responsabilização identificados, indicando:

- Quem fiscaliza quem;
- Qual é o objeto da fiscalização;
- Qual é a competência da instância;
- Onde o cidadão pode reclamar;
- Onde o cidadão pode contestar uma decisão sobre o benefício;
- Quais são os limites de atuação de cada canal.

##### 8.11. Registro de evidências

Atribua um identificador único a cada evidência, como E01, E02 e E03.

| ID | Afirmação sustentada | Instituição ou autor | Documento | Data | Página, artigo ou seção | Link direto | Classificação |
|---|---|---|---|---|---|---|---|

Sempre que possível, utilize links diretos para os documentos originais, e não apenas para páginas iniciais ou resultados de busca.

Indique a data de publicação, a vigência e a data de consulta quando pertinentes.

##### 8.12. Contradições e interpretações alternativas

Apresente os pontos em que as evidências permitem interpretações diferentes.

Para cada ponto, informe:

- Questão controversa;
- Interpretações possíveis;
- Evidências favoráveis a cada interpretação;
- Evidências contrárias;
- Informação necessária para resolver a divergência;
- Consequência para o futuro mapa de atores.

##### 8.13. Lacunas e perguntas em aberto

Organize as lacunas em uma tabela:

| ID | Lacuna | O que já se sabe | O que falta confirmar | Impacto no mapa de atores | Prioridade | Possível forma de validação |
|---|---|---|---|---|---|---|

Classifique a prioridade como alta, média ou baixa, considerando o impacto da lacuna na definição dos atores, das responsabilidades e das relações.

Diferencie:

- Lacunas documentais;
- Lacunas normativas;
- Lacunas operacionais;
- Lacunas tecnológicas;
- Lacunas contratuais;
- Lacunas de governança;
- Lacunas de delimitação conceitual.

Sugira formas de validação posterior, como consulta a documentos adicionais, pedidos de acesso à informação, entrevistas com gestores ou observação autorizada da jornada.

##### 8.14. Subsídios para a futura entrevista adversarial

Elabore um conjunto de perguntas críticas que possam ser utilizadas posteriormente para questionar o mapa de atores.

As perguntas devem explorar, entre outros aspectos:

- Atores possivelmente omitidos;
- Atores incluídos sem evidência suficiente;
- Sobreposição de competências;
- Ambiguidade de responsabilidades;
- Confusão entre instituições, papéis e sistemas;
- Diferença entre responsabilidade formal e atuação operacional;
- Granularidade adequada dos atores;
- Limites do escopo da jornada;
- Dependências tecnológicas;
- Responsabilidade pela resolução da demanda;
- Pontos de transferência;
- Governança interinstitucional.

Identifique quais decisões precisam ser tomadas pelo responsável pelo mapeamento, em vez de serem determinadas unilateralmente pela pesquisa.

Não realize a entrevista adversarial nesta etapa. Apenas prepare os insumos para sua realização posterior.

##### 8.15. Referências

Apresente a relação consolidada das fontes utilizadas, agrupadas por natureza documental, com links verificáveis.

#### 9. Critérios de qualidade

O relatório deverá atender aos seguintes critérios:

1. **Abrangência:** contemplar atores visíveis e invisíveis, sem limitar a investigação às instituições inicialmente conhecidas.

2. **Rastreabilidade:** permitir que cada afirmação relevante seja vinculada às respectivas evidências.

3. **Rigor factual:** distinguir fatos, inferências, hipóteses, lacunas e contradições.

4. **Atualidade:** diferenciar estruturas vigentes de informações históricas ou desatualizadas.

5. **Precisão institucional:** não confundir concessão, habilitação, processamento, pagamento e atendimento.

6. **Precisão operacional:** não presumir funcionalidades da URA que não estejam documentadas.

7. **Precisão tecnológica:** distinguir sistemas, canais, operadores, fornecedores e responsáveis institucionais.

8. **Precisão contratual:** não atribuir a um fornecedor responsabilidades que extrapolem o objeto comprovado de sua contratação.

9. **Consistência:** utilizar identificadores e denominações coerentes em todas as seções.

10. **Neutralidade:** não favorecer uma instituição ou interpretação sem fundamentação documental.

11. **Transparência:** explicitar limitações de acesso, documentos não localizados, fontes conflitantes e informações não verificáveis.

12. **Utilidade analítica:** produzir insumos suficientemente detalhados para permitir uma futura entrevista adversarial e a construção de uma matriz RACI ou diagrama de atores.

13. **Delimitação:** justificar a inclusão de atores indiretos com base em sua relação com a jornada investigada.

14. **Reprodutibilidade:** permitir que outro pesquisador localize as fontes e revise as conclusões.

#### 10. Restrições e orientações finais

- Não invente fontes, links, contratos, números telefônicos, opções de menu, sistemas ou responsabilidades.
- Não trate as hipóteses fornecidas como fatos estabelecidos.
- Não confunda existência institucional com participação comprovada na jornada.
- Não confunda competência legal com execução operacional.
- Não confunda orientação para outro canal com transferência efetiva de atendimento.
- Não force uma conclusão quando as evidências forem insuficientes.
- Não exclua um ator potencialmente relevante apenas porque sua participação ainda não pôde ser comprovada. Registre-o separadamente como candidato.
- Não apresente uma matriz RACI definitiva.
- Não realize a entrevista adversarial.
- Não transforme o relatório em uma proposta de redesenho da jornada ou plano de melhoria do atendimento.
- Utilize exclusivamente fontes e informações legitimamente acessíveis.
- Priorize profundidade, documentação e honestidade epistemológica em detrimento da concisão.

Antes de finalizar, revise criticamente o próprio relatório, procurando atores omitidos, responsabilidades atribuídas sem evidência, generalizações indevidas e conclusões excessivamente confiantes.

O resultado esperado não é uma resposta definitiva sobre quem são os atores, mas uma base de conhecimento estruturada, verificável, questionável e suficientemente abrangente para fundamentar a próxima etapa do trabalho.