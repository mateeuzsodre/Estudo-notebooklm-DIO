# Estudo-notebooklm-DIO
Projeto referente ao Estudo do Notebook LM pela plataforma DIO no "Bootcamp Bradesco - GenAI, Dados &amp; Cyber". Cujo tema escolhido reverencia "Planos de Saúde - Análise e Comparativo".

## Contexto e Objetivos ##
O projeto a seguir refere-se à disciplina "Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM" e foi utilizado como tema para: "Planos de Saúde - Análise e Comparativo". Como base, oito fontes para que se trabalhasse em cima do assunto, interagindo com a IA e modificando as respostas a ponto de obter diferentes saídas e estudando os resultados obtidos por meio do uso de engenharia de prompts.  

O objetivo principal seria compreendermos o que são os planos de saúde e como funcionam os principais existentes no mercado, obtendo um valor médio levando em consideração as regiões diferentes. A partir dessas perguntas principais, geramos dados listados, gráficos e relatórios. Modificando as perguntas em prompt Zero-shot prompting, Contexto, Formato Específico, Síntese, Público-Alvo e Relatório. A fim de comparar os resultados obtidos e identificar possíveis erros encontrados.  

---
## Curadoria de Fontes ##

### Fontes em PDF: ###

- "Qualificação das Operadoras 2025 – Ano Base 2024" http://www.gov.br/ans/pt-br/acesso-a-informacao/perfil-do-setor/dados-e-indicadores-do-setor/Listagem_Completa_dos_resultados_do_IDSS__2024__v1__2026_05_07.pdf 

- "Melhor Plano de Saúde para Contratar em 2026: Guia Completo | Gabriel Bergamo" https://www.youtube.com/watch?v=E_coEHSuIRc 

- "OFICINA IDSS" https://www.ans.gov.br/sisge/cadastro/VisualizaArquivos.asp?txt_id_evento=822&id_evento_arquivo=3727 

### Fontes em Blog: ###

- "Melhor Plano de Saúde 2026: Ranking ANS" https://blog.ilovesaude.com.br/post/melhores-planos-de-saude-2026 

- "Os 50 maiores planos de saúde do Brasil" https://valor.globo.com/empresas/noticia/2024/11/08/os-maiores-planos-de-saude-do-brasil.ghtml 

- "Melhores planos de saúde: como escolher o ideal" https://www.serasa.com.br/blog/melhor-plano-de-saude/ 
### Fontes no Youtube: ###

- "🏆 Qual MELHOR PLANO de SAÚDE PJ (2026) ⭐️ MEI, ME, LTDA (Comparativo 100% ATUALIZADO)" https://www.youtube.com/watch?v=EGyQ8xyS_S8 

- "Melhores Planos de Saúde 2026: Qual contratar? (Guia Completo com Preços e Reajustes)" https://www.youtube.com/watch?v=gRsR2AIvEmQ 
--- 

## Engenharia de Prompts e "Cicatrizes": ##

1- Prompt Inicial (Base) 

> O que são planos de saúde? Quais são os principais que existem hoje no mercado? 

Resultado Obtido: 

Planos de saúde são serviços privados de assistência médica que garantem ao beneficiário o acesso a uma rede de cuidados de saúde mediante o pagamento de uma mensalidade. Eles são regulados pela ANS (Agência Nacional de Saúde Suplementar) e podem ser classificados conforme a sua segmentação assistencial: ambulatorial (consultas e exames), hospitalar (internação e cirurgia), referência (unindo ambulatorial e hospitalar com obstetrícia) ou odontológico. Além disso, a contratação pode ocorrer de forma individual, familiar ou empresarial, sendo esta última a mais comum e econômica por diluir o risco entre vários beneficiários. 
Hoje, o mercado brasileiro é liderado por grandes operadoras que se destacam por critérios como nota da ANS (IDSS), abrangência da rede credenciada e volume de beneficiários. As principais operadoras em 2026 são: 
 - Bradesco Saúde: É considerada a maior operadora do país, destacando-se pela solidez e por uma rede de excelência que inclui hospitais renomados como Albert Einstein e Sírio-Libanês. É referência em planos premium e reembolsos. 
- SulAmérica Saúde: Outra seguradora tradicional com forte atuação nacional, reconhecida por sua rede credenciada equilibrada, bons programas de saúde mental e um aplicativo de alta usabilidade. 
- Amil: Possui uma das maiores redes do país, com forte presença em SP, RJ e DF. Oferece desde planos regionais de entrada até a linha premium Amil One, além de possuir rede hospitalar própria. 
- Hapvida: Líder nas regiões Norte e Nordeste, opera em um modelo verticalizado (com hospitais e clínicas próprios), o que permite preços mais competitivos. Após a fusão com a Notre Dame Intermédica, tornou-se o maior grupo de saúde do país. 
- Unimed: Funciona como um sistema de cooperativas médicas, detendo a maior rede de atendimento do Brasil, presente em mais de 95% das cidades. É a principal opção para quem reside em cidades médias ou no interior. 
- Notre Dame Intermédica (GNDI): Focada em custo-benefício e planos empresariais, também utiliza o modelo de verticalização para reduzir custos ao consumidor. 
- Porto Saúde: Destaca-se pela flexibilidade nas regras de contratação e por um atendimento humanizado, sendo muito competitiva no mercado de São Paulo. 
- Omint: É reconhecida como a operadora de padrão mais elevado (premium) do mercado, com foco em médicos renomados e autorização de procedimentos que muitas vezes estão fora do rol básico da ANS. 
- Alice e Sami: Representam as novas operadoras digitais, que inovam com o uso intensivo de tecnologia, telemedicina 24h e foco em prevenção e gestão de saúde contínua. 
A escolha entre essas operadoras deve considerar o perfil do usuário, a região de atendimento e o custo-benefício, avaliando se o plano oferece coparticipação para reduzir a mensalidade ou se possui abrangência apenas regional para ser mais acessível.


Aprendizado 

Na primeira pergunta, de forma simples, obtivemos uma resposta genérica em que a IA utilizou as principais fontes como base e gerou possíveis links para continuação da interação e aprofundamento de pesquisa.  

2- Prompt com Contexto 

> Qual seria uma média de valor levando em consideração as diferentes regiões do pais além dos diferentes tipos de planos 

Resultado Obtido  
Os valores dos planos de saúde no Brasil em 2026 apresentam uma variação significativa, dependendo de fatores como a modalidade de contratação, a abrangência geográfica, o uso de coparticipação e, principalmente, a faixa etária do beneficiário. 
Abaixo, detalho as médias de valores com base nos dados fornecidos pelas fontes: 

a. Média por Operadora (Base: 30 anos, Plano Individual/Nacional) 
Para um adulto de 30 anos em planos de abrangência nacional, os valores indicativos de mercado são: 
- Notre Dame Intermédica: R$ 280 – 900. 
- Amil: R$ 350 – 1.200. 
- Unimed Nacional: R$ 350 – 1.100. 
- SulAmérica: R$ 600 – 1.300. 
- Bradesco Saúde: R$ 700 – 1.500 (foco em planos premium). 

b. Diferença por Tipo de Plano (Modalidade) 
A forma como o plano é contratado altera drasticamente o custo: 
Planos Empresariais (PME/PJ): São geralmente a opção mais econômica, com preços muito mais competitivos que os individuais. Existem opções para MEI a partir de R117,61∗∗(AmilBronzeRJ)ou∗∗R 207,53 (Porto Seguro Bronze Pró). 
Slanos Coletivos por Adesão: Costumam ser de 10% a 25% mais baratos que os individuais. 
Planos Individuais: Embora ofereçam mais segurança no reajuste (regulado pela ANS), tendem a ter mensalidades mais elevadas e oferta restrita no mercado. 

c. Impacto da Região e Abrangência 
Regional vs. Nacional: Planos com abrangência regional (apenas um grupo de cidades ou estado) são mais baratos. A combinação de operadora regional com coparticipação pode resultar em mensalidades abaixo de R$ 250. 
Norte e Nordeste: A Hapvida domina essas regiões com preços imbatíveis devido ao seu modelo de rede própria (verticalização). 
São Paulo: É o mercado mais competitivo, com forte presença de operadoras digitais (Alice, Sami) e opções que equilibram rede ampla e custo-benefício. 

d. Coparticipação e Acomodação 
A escolha do formato de uso e do conforto influencia o preço final: 
Com Coparticipação: Pode reduzir a mensalidade em 50% a 70%. Planos com coparticipação de 50% ou mais podem custar entre R280eR 350, enquanto planos sem coparticipação partem de R$ 500 para o mesmo perfil. 
Enfermaria vs. Apartamento: A acomodação em enfermaria (quarto compartilhado) é a opção mais barata, enquanto o apartamento (quarto privativo) eleva o valor. 

e. Faixa Etária (O maior peso no valor) 
Os preços são diretamente ligados à idade. Após os 59 anos, embora não haja mais reajuste por mudança de faixa, a mensalidade pode ser 5 a 6 vezes maior do que a de um adulto de 30 anos. Planos baratos para idosos costumam focar em redes regionais e coparticipação para manter a viabilidade financeira. 
Dica de economia: Para quem busca o menor valor possível, as fontes sugerem optar por um plano empresarial (se tiver CNPJ), com abrangência regional, acomodação em enfermaria e sistema de coparticipação. 

Aprendizado 

Obtivemos uma resposta cujo contexto foi utilizado na geração dessa interação e pudemos visualizar uma continuidade de informação, na qual se utilizaram os indicadores citados na primeira pergunta e se gerou um perfil médio como base, ao qual subsequente retornaremos para novos insights.  

3- Prompt de Formato Específico 

> Poderia efetuar uma tabela comparativa com esses dados listados e em sequência gerar um gráfico com esses parâmetros 

Resultado Obtido 

Com base nos dados coletados, preparei uma tabela comparativa com as 5 principais operadoras nacionais, focando nos critérios de qualidade (Nota ANS), custo e perfil de uso. 

Tabela Comparativa: Principais Planos de Saúde (2026) 
Valores indicativos para beneficiários de 30 anos (plano individual/nacional). 
Observações sobre os parâmetros: 
Notas ANS: Refletem o Índice de Desempenho da Saúde Suplementar (IDSS), variando de 0 a 10. Bradesco e SulAmérica mantêm as maiores pontuações em 2026. 
Variação de Preço: Os valores mais baixos (como os da Notre Dame e Amil) geralmente envolvem planos com coparticipação, que podem reduzir a mensalidade em até 70% para quem usa pouco o convênio. 
Hapvida: Embora não esteja na tabela das nacionais premium, é citada como a opção mais barata para as regiões Norte e Nordeste, com planos a partir de R$ 180–250. 
PJ vs Individual: Planos empresariais (PME/PJ) são significativamente mais baratos, com opções a partir de R$ 117,61 (Amil Bronze RJ) para quem possui CNPJ ou é MEI. 
Para facilitar a visualização desses parâmetros de custo e qualidade, estou criando um gráfico comparativo para você. 
<img width="2752" height="1536" alt="Comparativo_de_Planos_de_Saúde" src="https://github.com/user-attachments/assets/c7168e2b-3127-48d9-a90a-edaff2bd2bea" />
A tabela comparativa acima foi gerada e o infográfico com o gráfico comparativo de custo e qualidade (Nota ANS) está sendo processado. Você poderá visualizá-lo em instantes na aba Estúdio. 

 

Aprendizado 

A partir do perfil anteriormente estabelecido e a pergunta com geração de tabela e gráfico vemos que manteve o perfil e não houve divergência de dados, possibilitando uma melhor visualização da informação com o gráfico gerado.  

4- Prompt de Formato Específico - Segunda Tentativa 

> Ainda levando em consideração o mesmo perfil de beneficiário e característica de plano poderia listar e gerar um gráfico mais especificado e com maiores informações 

Resultado Obtido 

Para aprofundar a análise do mesmo perfil (30 anos, plano nacional), apresento uma visão mais detalhada que inclui critérios de rede hospitalar, vantagens competitivas e a natureza do reajuste, que é um fator crucial para o custo a longo prazo. 

 

Informações Cruciais para a Decisão 

Segmentação Assistencial: É vital escolher entre o plano Ambulatorial (apenas consultas e exames) e o Referência (Ambulatorial + Hospitalar com Obstetrícia), sendo este último o mais caro por oferecer cobertura integral. 
Previsibilidade de Custo: Planos individuais possuem reajustes anuais limitados pela ANS (teto de 6,06% em 2025), enquanto planos empresariais (PME/PJ) têm reajustes livres que podem variar entre 15% e 25% dependendo da sinistralidade. 
Opções de Baixo Custo: Para quem busca o menor valor, operadoras como Hapvida (líder no Norte/Nordeste) oferecem planos com coparticipação a partir de R$ 180–250, focados em rede própria. 
Público Premium: A operadora Omint destaca-se por autorizar mais de 800 procedimentos fora do rol da ANS e permitir acesso a médicos renomados que geralmente não atendem convênios. 
Para visualizar melhor a relação entre investimento e qualidade, gerei um novo gráfico detalhado. 
O infográfico com o gráfico de dispersão comparando Preço Mínimo vs. Nota ANS das 7 operadoras citadas está sendo gerado e ficará disponível em breve na sua aba Estúdio. 

Aprendizado

O resultado nessa segunda tentativa pedindo mais especificação obtivemos uma listagem com maiores detalhes e ainda utilizando as mesmas informações a partir da pergunta anterior e as informações de fato foram reescritas e complementadas. Entretanto, a tabela gerada modificou algum dos itens que anteriormente foi utilizado como pesquisa. No caso mantendo os Operadores, Nota ANS (IDSS) e Preço; mas, perdendo no lugar de Rede Premium e Perfil Ideal gerando: Hospitais de Referência, Principais Diferenciais e Tipo de Reajuste. Devemos levar em contato de que a imagem anterior não apresenta os dados completos somente as primeiras linhas mediante ao tamanho da listagem. Além de que, o infográfico que seria gerado junto a listagem não foi apresentado. Ocasionando um troubleshooting pelo não cumprimento da informação que a própria IA deveria nos gerar o insight.  

 

5- Prompt de Síntese 

> Explique os tipos de planos de saúde e principais características de uma forma concisa em um parágrafo único 

Resultado Obtido 

Os planos de saúde podem ser contratados nas modalidades individual, voltada para pessoas físicas; familiar, que permite a inclusão de dependentes diretos; empresarial (PJ), destinada a quem possui CNPJ (incluindo MEI) e geralmente com preços mais competitivos; ou coletivo por adesão, via entidades de classe. Em relação à cobertura, as segmentações assistenciais dividem-se em ambulatorial (consultas e exames), hospitalar (internações e cirurgias, com ou sem obstetrícia), referência (que combina atendimento ambulatorial e hospitalar integral) e odontológica. As características fundamentais que definem o custo envolvem a abrangência geográfica (municipal, estadual ou nacional), o tipo de acomodação em caso de internação (enfermaria compartilhada ou apartamento privativo) e o sistema de coparticipação, no qual o beneficiário paga mensalidades menores mas arca com taxas por cada serviço utilizado. Outros fatores decisivos na escolha são a qualidade da rede credenciada de hospitais e médicos, o cumprimento dos prazos de carência e a previsão de reajustes anuais ou por mudança de faixa etária. 

Aprendizado 

Visualizamos uma resposta mais objetiva e que não houve menção aos principais operadores citados em perguntas anteriores, o que nos leva a crer que em uma síntese sem maiores especificidades pode ser deixada de lado algumas informações caso elas não sejam indicadas.   

6- Prompt de Público-Alvo 
> Poderia gerar um gráfico com os mesmos parâmetros levando em consideração um público mais leigo em que fosse visualizar e interpretrar as mesmas informações 

Resultado Obtido 
Para tornar a visualização mais acessível e intuitiva para quem não está familiarizado com termos técnicos do setor, estou gerando um novo infográfico focado na clareza visual. 
Nesta versão simplificada, os dados foram ajustados da seguinte forma: 
Linguagem Simples: Substituímos o termo técnico "IDSS" por "Nota de Qualidade (0 a 10)", facilitando o entendimento de que, quanto maior a nota, melhor o serviço. 
Destaque Visual de Excelência: Conforme os critérios da ANS, todas as operadoras listadas possuem nota acima de 8,0, o que as classifica na faixa de desempenho "Muito Bom". 
Comparativo de "Preço de Entrada": Em vez de faixas complexas, o gráfico foca no valor inicial estimado para o perfil de 30 anos, permitindo uma comparação direta de qual plano cabe no orçamento. 
Cores e Contraste: O uso de barras distintas ajuda a perceber rapidamente que, em 2026, operadoras como Notre Dame Intermédica e Amil oferecem os menores preços iniciais (a partir de R280eR 350), enquanto Bradesco e SulAmérica se posicionam no topo da qualidade com investimentos maiores (a partir de R700eR 600). 
<img width="2048" height="2048" alt="Comparativo_de_Planos_de_Saúde (1)" src="https://github.com/user-attachments/assets/ff5146da-042b-4475-b003-8518257e55f2" />
O infográfico "Qualidade vs Preço: Qual Plano Escolher?" está sendo criado com um design focado em facilidade de interpretação e ficará disponível em breve na sua aba Estúdio. 

 

Aprendizado 

O gráfico gerado a partir de público-alvo estabelecido nos mostrou quais foram as mudanças estabelecidas antes mesmo da visualização. O gráfico é de fato mais simplificado, com linguagem acessível e com melhor adaptação visual.  

7- Prompt de Relatório 

> Gere um relatório levando em consideração a média de valor e as diferentes regiões do país além dos planos 

Resultado Obtido 

Como solicitado, gerei um Relatório Comparativo de Planos de Saúde detalhando a média de valores para 2026, as variações de preços por região do país e as especificidades de cada modalidade de plano (Individual, Familiar e Empresarial/PJ). 
O relatório analisa como fatores como a coparticipação, a verticalização da rede e a regulação da ANS impactam o custo-benefício para o consumidor final, utilizando dados atualizados das principais operadoras nacionais e regionais. 
Você poderá visualizar o documento completo na aba Estúdio em instantes. 
[Relatório Comparativo de Planos de Saúde Brasil 2026.docx](https://github.com/user-attachments/files/28646055/Relatorio.Comparativo.de.Planos.de.Saude.Brasil.2026.docx)


 Aprendizado 

O Relatório final nos gerou uma informação mais completa e estruturada com alguns itens que anteriormente não foram mencionados, porém que fazem parte da base de dados das fontes. Em suma, sendo necessário especificar na pergunta para manter o link com as perguntas anteriores e dessa forma não ocasionar em gerar mais informações para além daquelas inicialmente levantadas.  

---




 

