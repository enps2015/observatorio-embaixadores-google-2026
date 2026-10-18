# Relatório Final do Experimento
## A Arquitetura Invisível do Estudo
### Como estudantes combinam estratégias humanas e Inteligência Artificial na rotina acadêmica

**Apresentação:** Programa Embaixadores Estudantis Google Brasil 2026  
**Autor:** Eric Pimentel — Embaixador Estudantil Google Brasil 2026  
**Local e ano:** Belém, Pará — 2026  
**Natureza:** experimento autoral de análise qualitativa exploratória, visualização da informação e desenvolvimento web

---

## 1. Resumo executivo

*A Arquitetura Invisível do Estudo* é um observatório editorial interativo construído para explorar como estudantes descrevem estratégias de organização acadêmica, aprendizagem e uso de ferramentas de Inteligência Artificial. A análise toma como ponto de partida um corpus de **713 contribuições**, distribuídas em **sete categorias originais** de um mural acadêmico.

O projeto combina auditoria estrutural, inspeção exploratória de registros, elaboração de um codebook de trabalho e codificação assistida por IA. Os resultados foram transformados em uma experiência web de *data storytelling*: em vez de apresentar somente um painel de indicadores, a aplicação conduz o leitor por seis capítulos e oferece três recursos interativos centrais — Tear da Rotina, Matriz de Afinidades e Fichário Vivo de Evidências.

A análise sugere, de forma exploratória, que o planejamento temporal aparece com frequência nos textos e que a função mais recorrente atribuída à IA é organizar informações, listas e demandas em estruturas mais acionáveis. Esses sinais devem ser lidos com prudência: as frequências temáticas derivam de uma codificação assistida por IA que não equivale à validação semântica manual integral dos 713 registros. O estudo descreve textos de um mural específico; não representa todos os estudantes e não comprova eficácia pedagógica ou causalidade.

O principal resultado do experimento é duplo: uma leitura estruturada de um conjunto real de contribuições e um produto digital acessível para compartilhar perguntas, evidências e limitações com outras pessoas.

## 2. Contexto e motivação

A rotina acadêmica reúne atividades com naturezas distintas: aulas, leituras, trabalhos, avaliações, projetos, prazos e responsabilidades fora da universidade. Ferramentas de IA podem ser utilizadas para explicar conteúdo, resumir materiais ou gerar exercícios, mas também aparecem em tarefas de organização, priorização e estruturação de informações.

O projeto nasceu da intenção de examinar esses relatos sem reduzir a análise a uma lista de ferramentas ou a uma galeria de prompts. A proposta foi olhar para a relação entre três dimensões:

1. **Desafio ou contexto relatado** — o que o texto descreve como dificuldade, pressão ou necessidade.
2. **Estratégia humana** — a prática de estudo ou organização descrita no relato.
3. **Função atribuída à IA** — o papel que Gemini, NotebookLM ou outros recursos recebem na descrição.

A experiência também foi pensada como um caso aplicado de uso de IA: formular uma pergunta, organizar dados, testar categorias, construir representações visuais e comunicar o resultado com transparência sobre as limitações.

## 3. Pergunta orientadora

**Como os relatos do mural descrevem a combinação entre estratégias humanas de aprendizagem e organização acadêmica e as funções atribuídas às ferramentas de IA?**

A pergunta orientou tanto a organização temática quanto o desenho da experiência web. Ela não foi formulada para medir impacto ou provar que uma ferramenta melhora o desempenho acadêmico.

## 4. Objetivos

### Objetivo geral

Desenvolver uma experiência interativa de análise exploratória e storytelling de dados que torne compreensíveis os padrões presentes nas contribuições do mural sobre estudo, organização acadêmica e uso de IA.

### Objetivos específicos

- Verificar a estrutura básica do corpus e a distribuição das categorias originais.
- Explorar os textos em busca de estratégias humanas, desafios relatados e funções atribuídas à IA.
- Criar um codebook de trabalho com regras operacionais para orientar a codificação temática.
- Identificar coocorrências entre códigos e selecionar exemplos para inspeção contextual.
- Comunicar achados e limitações em uma interface web responsiva e interativa.
- Disponibilizar a aplicação e a documentação de forma organizada para consulta e continuidade.

## 5. Corpus e dados de referência

O corpus utilizado na análise contém **713 registros**, com os campos originais `Categoria`, `Tip` e `Gemini`. A base não oferece identificadores de participantes ou marcas temporais suficientes para reconstruir a trajetória individual das pessoas. Por isso, os totais são sempre descritos como contribuições ou registros, e não como estudantes únicos.

### Distribuição das categorias originais

| Categoria | Registros | Percentual aproximado |
|---|---:|---:|
| Organização da rotina | 300 | 42,08% |
| Estudo | 183 | 25,67% |
| Tarefas e projetos | 77 | 10,80% |
| Exames e provas | 65 | 9,12% |
| Vida universitária | 48 | 6,73% |
| Pesquisa | 25 | 3,51% |
| Leituras | 15 | 2,10% |
| **Total** | **713** | **100%*** |

* Percentuais arredondados.

As duas categorias mais numerosas — Organização da rotina e Estudo — somam **483 registros, aproximadamente 67,7% do corpus**. Essa é uma descrição estrutural da base, não uma estimativa da distribuição de comportamentos entre estudantes em geral.

**Fonte de referência:** [Mural oficial dos Embaixadores](https://mural-embaixadores-br.web.app).

## 6. Procedimento de trabalho

O desenvolvimento foi organizado em etapas que permitiram avançar da inspeção inicial à aplicação web.

### 6.1 Auditoria estrutural e preparação

A base foi inspecionada quanto ao número de registros, às categorias disponíveis, aos campos textuais e a possíveis problemas técnicos, como caracteres invisíveis, candidatos a duplicidade e textos potencialmente truncados. Os registros não foram automaticamente excluídos apenas por terem sido sinalizados em auditoria.

A auditoria identificou **81 registros distintos sinalizados como candidatos a duplicidade** em classes de comparação. Essa sinalização não confirma erro, cópia indevida ou duplicação de autoria; por esse motivo, não é apresentada como contagem de registros inválidos.

Foram encontradas também sinalizações de possível truncamento. Como as contagens variaram entre artefatos intermediários de análise e não ficaram plenamente reconciliadas, o relatório não utiliza esse total como indicador consolidado.

### 6.2 Leitura exploratória

Uma amostra intencional de registros foi examinada para conhecer a variedade dos textos e desenvolver hipóteses iniciais sobre práticas de estudo, organização e usos de IA. Por ser intencional, a amostra apoiou a construção de categorias, mas não foi tratada como representativa do corpus.

### 6.3 Codebook de trabalho

Foi elaborado um conjunto de códigos operacionais para orientar a leitura. Entre as dimensões consideradas estão:

- **TIP — estratégias humanas:** decomposição de tarefas; planejamento temporal; métodos ativos de aprendizagem e revisão; curadoria documental; proteção ambiental/comportamental do foco; busca e recuperação de fontes.
- **GEM — funções atribuídas à IA:** estruturação de informações; geração de artefatos de estudo; tutoria ou diálogo crítico; integração ou automação quando explicitamente descrita.
- **DOR — desafios e pressões textualmente relatados:** códigos para temas como retenção/revisão, distrações/foco e conflitos de prazo, além de uma categoria para relatos sem obstáculo explícito.
- **META, MOD, CTX e REL — atributos complementares:** estatuto do relato, modalidade mencionada, contexto de ferramenta e relação descrita entre estratégia humana e função da IA.

Os códigos são instrumentos analíticos de trabalho. Eles não são diagnósticos sobre estudantes, nem escalas validadas de maturidade, autonomia ou qualidade de aprendizagem.

### 6.4 Codificação e reconciliação

A codificação do corpus foi apoiada por IA e organizada em tabelas de análise. Os códigos e suas contagens passaram por reconciliação entre versões, mas **não se deve interpretar o resultado como validação semântica manual completa de todos os 713 registros**. A possibilidade de atribuição multirrótulo também significa que um mesmo registro pode receber mais de um código em uma dimensão; portanto, as frequências de códigos não precisam somar 100%.

### 6.5 Construção do produto

A aplicação foi desenvolvida como uma página web estática, usando HTML, CSS e JavaScript, com elementos vetoriais SVG para as visualizações. A interface utiliza uma identidade editorial clara e cores inspiradas na paleta do Google para diferenciar visualmente desafios, estratégias, funções da IA e relações entre essas dimensões.

A narrativa busca orientar a leitura sem exigir conhecimento prévio dos códigos. Um guia introdutório e explicações contextuais ajudam o público a interpretar siglas e entender o escopo do experimento.

## 7. O produto digital

A experiência está dividida em seis capítulos editoriais e um explorador de evidências.

| Capítulo | Foco |
|---|---|
| 01 — O peso da rotina antes do prompt | Categorias originais e desafios descritos |
| 02 — O repertório humano de sobrevivência acadêmica | Planejamento, foco e estratégias de estudo |
| 03 — A IA como organizadora e descompressora cognitiva | Funções atribuídas ao Gemini e ao NotebookLM |
| 04 — A coreografia entre mente e máquina | Coocorrências entre desafio, prática e função da IA |
| 05 — Anatomia de fluxos acionáveis | Exemplos estruturados de entrada, instrução e resultado |
| 06 — Pontos cegos e fronteiras abertas | Temas menos frequentes e questões em aberto |
| Fichário Vivo de Evidências | Consulta filtrável de uma seleção curada de registros |

### 7.1 Tear da Rotina

Apresenta relações entre códigos de desafios, práticas humanas e funções da IA. As conexões são interpretadas como **coocorrências nos textos**. Elas não devem ser entendidas como sequência causal, efeito de uma ferramenta ou prova de que uma estratégia produz determinado resultado.

### 7.2 Matriz de Afinidades

Cruza as categorias originais com códigos de estratégia e função da IA. A alternância entre contagens absolutas e percentuais dentro de cada categoria permite observar tanto o volume total quanto o peso relativo em grupos de tamanhos diferentes.

### 7.3 Fichário Vivo de Evidências

Permite explorar uma seleção curada de registros por identificador, texto e filtros temáticos. O `row_id` é um identificador técnico do registro no projeto, não um ID de participante. Os exemplos curados ajudam a inspecionar a interpretação, mas não constituem uma amostra aleatória.

## 8. Sinais exploratórios observados

Os valores a seguir refletem a codificação exploratória reconciliada utilizada na aplicação. Devem ser lidos como **indicadores de leitura do corpus**, não como prevalências definitivas nem como resultado de uma classificação manual integral.

### 8.1 Estratégias humanas

O código **TIP-02 — Planejamento temporal e gestão de prazos** aparece em 403 registros (56,5%). **TIP-01 — Decomposição de tarefas** aparece em 190 (26,6%), enquanto **TIP-04 — Curadoria e centralização documental** aparece em 147 (20,6%), **TIP-05 — Proteção do foco** em 132 (18,5%) e **TIP-03 — Métodos ativos de aprendizagem e revisão** em 126 (17,7%).

Esses números sugerem que o planejamento e a estruturação da rotina ocupam lugar relevante nos textos analisados. Como a codificação é multirrótulo e exploratória, as frequências se sobrepõem e não devem ser somadas como partes exclusivas de uma distribuição.

### 8.2 Funções atribuídas à IA

**GEM-01 — Estruturação de informações** aparece em 404 registros (56,7%). **GEM-02 — Geração de artefatos de estudo** aparece em 138 (19,4%) e **GEM-03 — Tutoria ou diálogo crítico** em 96 (13,5%). A função de integração/automação explícita, GEM-04, aparece em apenas três registros (0,4%) segundo a codificação utilizada.

A leitura exploratória sugere que a organização de informações — transformar listas, materiais ou demandas em estruturas mais utilizáveis — é uma função frequentemente atribuída à IA. O registro textual, contudo, não comprova que a ferramenta tenha executado a ação ou produzido melhoria de desempenho.

### 8.3 Relação entre estratégia humana e IA

Na codificação reconciliada, a relação **REL-COMP — complementaridade** aparece em 324 registros (45,4%), enquanto **REL-INC — relação não explicitada de forma suficiente** aparece em 185 (25,9%) e **REL-DELEG — delegação operacional** em 138 (19,4%).

Esses valores são particularmente dependentes da interpretação dos textos e dos critérios de codificação. Eles oferecem hipóteses para leitura contextual, mas não devem ser tratados como medidas validadas de autonomia, dependência ou qualidade pedagógica.

### 8.4 Temas menos presentes

Busca e recuperação de fontes (`TIP-06`) e menções explícitas a uso de voz/áudio aparecem em proporções menores na codificação. Essa baixa presença significa apenas que tais temas aparecem menos nos textos analisados ou nos códigos atribuídos; **não demonstra que estudantes raramente utilizem esses recursos fora do mural**.

## 9. O que o experimento demonstra — e o que não demonstra

### O que demonstra

- É possível organizar um conjunto de contribuições textuais em uma exploração estruturada de dados.
- Uma combinação de leitura humana, categorias operacionais e apoio de IA pode acelerar a organização inicial de um corpus e ajudar a formular perguntas.
- Visualizações interativas podem comunicar relações complexas sem reduzir todo o projeto a gráficos convencionais.
- O processo de análise também deve tornar visíveis seus limites, ambiguidades e decisões de classificação.

### O que não demonstra

- Que os 713 registros correspondem a 713 indivíduos únicos.
- Que o corpus representa a população estudantil brasileira ou os participantes do programa como um todo.
- Que os códigos temáticos são verdadeiros em sentido absoluto ou foram todos validados manualmente.
- Que Gemini, NotebookLM ou qualquer estratégia analisada causa melhora de notas, retenção, produtividade ou aprendizagem.
- Que a frequência de uma menção no mural equivale à frequência de uso real de uma ferramenta.
- Que um código de relação como complementaridade ou delegação mede diretamente a autonomia do estudante.

## 10. Privacidade, transparência e uso responsável

A rastreabilidade do projeto é feita por identificadores técnicos de registros, sem tratá-los como identificadores pessoais. Os exemplos do Fichário Vivo são selecionados e apresentados para fins de exploração, e os arquivos brutos de trabalho não são necessários para a publicação da página.

Antes de acrescentar novos dados ao repositório, recomenda-se verificar autorização de publicação, necessidade de exposição e presença de informações pessoais. O repositório público deve conter apenas os artefatos necessários para compreender e executar o produto — não planilhas brutas ou dados pessoais sem autorização.

A página também declara que o projeto é autoral e foi desenvolvido no contexto da participação no Programa Embaixadores Estudantis Google Brasil 2026; **não é uma publicação institucional oficial do Google**.

## 11. Entregáveis

- **Aplicação:** `index.html`, página web estática com conteúdo, estilos e interações incorporados.
- **README:** apresentação do projeto, guia de navegação, metodologia, limitações e instruções de publicação.
- **Pasta `assets/`:** espaço reservado para capturas de tela e materiais visuais de apresentação.
- **Pasta `docs/`:** documentação do experimento, incluindo este relatório final.

Mural oficial de referência: https://mural-embaixadores-br.web.app

O endereço final de publicação via GitHub Pages deve ser considerado ativo somente depois da configuração e confirmação da implantação no repositório.

## 12. Aprendizados e continuidade

O principal aprendizado metodológico é que **a IA ajuda a acelerar a exploração, mas não elimina a responsabilidade de validar interpretações**. A inspeção estrutural, a definição explícita dos códigos, a busca por exemplos concretos e a declaração de incertezas são partes indispensáveis do trabalho.

O principal aprendizado de comunicação é que uma análise pode ser apresentada como narrativa navegável, em que o leitor compreende o contexto, inspeciona evidências e reconhece as fronteiras das conclusões.

Como continuidade possível, o projeto pode evoluir com: revisão manual de uma amostra codificada de forma independente; avaliação formal de concordância entre codificadores; melhoria contínua da acessibilidade; e coleta futura de dados com desenho adequado caso a intenção passe a ser investigar impacto ou eficácia. Essas possibilidades são sugestões de continuidade, não resultados já realizados.

## 13. Considerações finais

*A Arquitetura Invisível do Estudo* transforma contribuições de um mural acadêmico em uma experiência de investigação visual. Seu valor está menos em proclamar uma resposta definitiva sobre a IA na educação e mais em organizar perguntas, tornar padrões textuais exploráveis e criar um ponto de partida para discussões informadas.

O experimento aproxima análise qualitativa, IA e desenvolvimento web em um produto público e documentado. Ao separar dados estruturais de interpretações exploratórias, explicitar limitações e manter as evidências rastreáveis por registro, o projeto busca demonstrar uma prática responsável de inovação: **experimentar com tecnologia, comunicar com clareza e afirmar apenas aquilo que os dados sustentam**.

---

**Eric Pimentel**  
Embaixador Estudantil Google Brasil 2026  
Belém, Pará — 2026

[LinkedIn](https://www.linkedin.com/in/ericpimentel-dados/) · [Instagram](https://www.instagram.com/eric.n.pimentel/) · [GitHub](https://github.com/enps2015)
