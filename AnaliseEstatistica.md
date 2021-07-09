

Junho de 2021

**RESUMO**

Relatório de interpretação estatística dos dados

relativos aos Estados Unidos da América com o

objetivo de explicar como a expectativa de vida

é influenciada por diversos fatores.

**Palavras-chave:** expectativa de vida, Estados

Unidos, estatística.

**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**

**Carlos Eduardo Fontaneli**

<carlos.fontaneli@estudante.ufscar.br>

**Hugo da Silva e Souza**

<hugo.souza@estudante.ufscar.br>

**Luana de Queiroz Garcia**

<luanaqg@estudante.ufscar.br>

**Luís Augusto Simas do Nascimento**

<luissimas@estudante.ufscar.br>

**Matheus Rezende Milani Videira**

<matheus.videira@estudante.ufscar.br>

**Rafael Vinicius Polato Passador**

<rafaelpassador@estudante.ufscar.br>

***RELATÓRIO DE***

***PROBABILIDADE E***

***ESTATÍSTICA.***

***Análise Estatística***

**\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_**

**1**





Análise Estatística

Título do trabalho

**1 INTRODUÇÃO**

No conjunto de dados são apresentados os nomes de 50 estados norte-americanos,

juntamente com as seguintes variáveis: *pop* (população estimada em julho de 1975), *percap*

(renda per capita do ano em 1974 em USD), *analf* (proporção de analfabetos em 1970),

*expvida* (expectativa de vida em anos de 1969-70), *crime* (taxa de criminalidade por 100.000

habitantes em 1976), *estud* (porcentagem de estudantes que concluem o segundo grau em

1970), *ndias* (número de dias do ano com temperatura abaixo de zero grau Celsius na cidade

mais importante do estado) e *area* (área do estado em milhas quadradas). Ademais, o

interesse neste estudo é tentar explicar a expectativa de vida da população a partir de análises

das variáveis *percap* , *analf*, *crime*, *estud*, *ndias* e *dens* em que *dens = pop/area.*

Dessarte, a fim de realizar tais análises, será feito dois tipos de análises a partir do

conjunto de dados fornecido, sendo elas: análise descritiva unidimensional e análise descritiva

bidimensional. Haja vista que todas as variáveis disponibilizadas pela amostra são

quantitativas, serão utilizadas, então, tabelas de frequências unidimensionais e tabelas de

frequências bidimensionais, com suas respectivas tabelas de medidas descritivas

correspondentes.

**1.1 Amostra**

Para realização desse experimento, o plano probabilístico e o processo de amostragem

utilizados, os quais reúnem todas as técnicas que usam mecanismos aleatórios(sorteio) de

seleção dos elementos da amostra, atribuindo a cada um deles uma probabilidade conhecida

de seleção, foi a Amostragem Casual Simples (A.C.S), em que todos os elementos da

população têm igual probabilidade de pertencer a amostra.

Considerou-se para o presente experimento as seguintes características, com seus

respectivos tipos, dispostas na seguinte tabela:

**2**





Análise Estatística

Título do trabalho

Variáveis

*pop*

Tipo de Variável

Descrição

Quantitativa Contínua

Quantitativa Contínua

Quantitativa Contínua

Quantidade estimada de pessoas no estado

Renda per capita mensurada em dólares (USD)

*percap*

*analf*

Proporção de pessoas analfabetas em relação à

população

*expvida*

*crime*

Quantitativa Contínua

Quantitativa Contínua

Quantitativa Contínua

Expectativa de vida em anos

Taxa de criminalidade por 100.000 habitantes

*estud*

Porcentagem de estudantes que concluem o ensino

médio

*ndias*

Quantitativa Discreta

Quantidade de dias com a temperatura abaixo de 0

graus Celsius na cidade mais importante

*area*

*dens*

Quantitativa Contínua

Quantitativa Contínua

Área do estado em milhas quadradas

População dividida pela área do estado

**1.2 Objetivos**

Esta análise estatística possui como principal objetivo analisar e buscar uma explicação

sobre a expectativa de vida nas presentes populações com bases nos dados relativos à renda

per capita, ao índice de analfabetismo, à taxa de criminalidade, ao nível de estudo, ao número

de de dias com temperatura abaixo de zero e à densidade demográfica, expondo uma possível

correlação entre as variáveis em questão.

**1.3 Metodologia Estatística e Apresentação dos Resultados**

A partir da organização, representação e sumarização dos dados obtidos pela análise

da amostra, faz-se necessário obter maiores informações através de técnicas apropriadas.

Nesse contexto, utilizou-se o software R para realizar a análise unidimensional e bidimensional

dos dados, juntamente com alguns pacotes adicionais de funções da linguagem.

Nesse ínterim, a fim de conhecer o comportamento de cada variável, analisou-se suas

ocorrências através de tabelas de frequências, absolutas e relativas, bem como seus gráficos

correspondentes, que ofertam uma ideia de como elas se distribuem perante a população.

Assim sendo, as variáveis quantitativas discretas são representadas a partir da ocorrência do

córpus, concomitantemente, os dados relativos às variáveis quantitativas contínuas são

agrupados em classes (faixas) escolhidas de maneira arbitrária pelo grupo.

Paralelamente, utilizou-se de gráficos para representar a distribuição das variáveis, bem

como informações sobre variabilidade, simetria, valores discrepantes, entre outros aspectos

**3**





Análise Estatística

Título do trabalho

relevantes. Por conseguinte, como todas em questão são quantitativas, optou-se por

representá-las através de histogramas.

Os dados categóricos são apresentados em números absolutos e percentuais, e as

variáveis quantitativas em média e mediana e interquartis. A análise de associação entre as

variáveis foi realizada a partir de análises gráficas e, concomitantemente, da correlação

empírica entre estas. Ademais, para traçar as correlações empíricas entre as variáveis

utilizou-se o coeficiente de correlação de Pearson.

Por fim, a fim de estimar correlações lineares entre as variáveis realizou-se uma

análise de regressão linear. Dessarte, testes de hipóteses para os coeficientes de correlação,

representações gráficas e verificação de adequabilidade das hipóteses estabelecidas sobre

normalidade dos erros e variância constante foram realizadas também, em busca de sustentar

a análise de regressão linear feita.

**2 ANÁLISE DESCRITIVA UNIDIMENSIONAL**

**I. População:**

Dos 50 estados avaliados, 22 (44,9%) estados têm uma população menor que 2.448

habitantes e somente 2 estados (2,04%) tem população maior que 12.864 habitantes. Ademais,

a média de habitantes por estado é de 4.246 habitantes.

**Tabela 1.1.** Tabela de frequência relativa à variável quantitativa *população*.

**4**





Análise Estatística

Título do trabalho

**Gráfico 1.1.** Histograma relativo à variável quantitativa contínua *população*.

**5**





Análise Estatística

Título do trabalho

**Gráfico 1.2.** Gráfico de densidade empírica relativo à variável quantitativa contínua *população*.

**Tabela 1.2.** Medidas descritivas relativas à variável quantitativa contínua *população*.

**6**





Análise Estatística

Título do trabalho

**Figura 1.** Boxplot relativo à variável quantitativa contínua *população*.

**II. Renda per capita:**

Dos 50 estados avaliados, 18(36%) deles possuem uma renda per capita entre R$4500

e $5000, 2(4%) estados possuem entre $3000,00 e $3500,00 e somente 1 (2%) possuem

renda acima de $6000,00. A renda per capita média entre os estados é de $4435,80, sendo a

mínima $3098,00 (Mississippi) e a máxima $6315,00 (Alaska).

**Tabela 2.1.** Tabela de frequência relativa à variável quantitativa *renda per capita*.

**7**





Análise Estatística

Título do trabalho

**Gráfico 2.1.** Histograma relativo à variável quantitativa contínua *renda per capita*.

**8**





Análise Estatística

Título do trabalho

**Gráfico 2.2.** Gráfico de densidade empírica relativo à variável quantitativa contínua *renda per*

*capita.*

**Tabela 2.2.** Medidas descritivas relativas à variável quantitativa contínua *renda per capita*.

**9**





Análise Estatística

Título do trabalho

**Figura 2.** Boxplot relativo à variável quantitativa contínua *renda per capita*.

**III. População de analfabetos:**

Dos 50 estados avaliados, 18(36%) deles possuem uma taxa de analfabetismo

populacional entre 0,5% e 0,78%, sendo que apenas 3(6%) deles têm uma taxa maior que

2,3%. A taxa de analfabetismo nos estados tem média de 0,95%, com taxa mínima de 0,5% e

máxima de 2,8%.

**Tabela 3.1.** Tabela de frequência relativa à variável quantitativa *taxa de analfabetismo*.

**10**





Análise Estatística

Título do trabalho

**Gráfico 3.1.** Histograma relativo à variável quantitativa contínua *taxa de analfabetismo*.

**Gráfico 3.2.** Gráfico de densidade empírica relativo à variável quantitativa contínua *taxa de*

*analfabetismo.*

**11**





Análise Estatística

Título do trabalho

**Tabela 3.2.** Medidas descritivas relativas à variável quantitativa contínua *taxa de analfabetismo*.

**Figura 3.** Boxplot relativo à variável quantitativa contínua *taxa de analfabetismo*.

**I V. Expectativa de vida:**

Dos 50 estados avaliados, 21(42%) deles possuem uma expectativa de vida entre 69.9

e 70.9 anos, sendo que apenas 2(4%) deles têm uma expectativa maior que 72.9 anos. A

expectativa de vida nos estados tem média aritmética de 70.6 anos, com mínimo de 67.9 e

máximo de 73.9.

**12**





Análise Estatística

Título do trabalho

**Tabela 4.1.** Tabela de frequência relativa à variável quantitativa *expectativa de vida*.

**Gráfico 4.1.** Histograma relativo à variável quantitativa contínua *expectativa de vida*.

**13**





Análise Estatística

Título do trabalho

**Gráfico 4.2.** Gráfico de densidade empírica relativo à variável quantitativa contínua *expectativa*

*de vida.*

**Tabela 4.2.** Medidas descritivas relativas à variável quantitativa contínua *expectativa de vida*.

**14**





Análise Estatística

Título do trabalho

**Figura 4.** Boxplot relativo à variável quantitativa contínua *expectativa de vida*.

**V. Taxa de criminalidade:**

Dos 50 estados avaliados, 19(38%) deles possuem uma taxa de criminalidade entre

1.4% e 5.9%, 17(34%) deles possuem taxa entre 5.9% e 10.5%, 13(26%) deles possuem taxa

entre 10.5% e 15.1%, sendo que apenas 1(2%) deles têm uma taxa maior que 15.1%. A taxa

de criminalidade nos estados tem média aritmética de 6.8%, com mínimo de 1.4% e máximo de

15.1%. A taxa de criminalidade está bastante dispersa nos estados.

**Tabela 5.1.** Tabela de frequência relativa à variável quantitativa da taxa *de criminalidade*.

**15**





Análise Estatística

Título do trabalho

**Gráfico 5.1.** Histograma relativo à variável quantitativa contínua *taxa de criminalidade*.

**Gráfico 5.2.** Gráfico de densidade empírica relativo à variável quantitativa contínua *taxa de*

*criminalidade.*

**16**





Análise Estatística

Título do trabalho

**Tabela 5.2.** Medidas descritivas relativas à variável quantitativa contínua taxa *de criminalidade*.

**Figura 5.** Boxplot relativo à variável quantitativa contínua *expectativa de vida*.

**VI. Estudantes que concluem o ensino médio:**

Entre os 50 estados avaliados, cerca de 14(28%) estados apresentam uma população

com um índice de conclusão do segundo grau abaixo de aproximadamente 50%, enquanto

28(56%) estados apresentam um índice aproximado de uma intervalo de 50% a 60%, por fim,

8(16%) estados apresentam índices aproximados superiores a 60%. O índice médio se

aproxima de 53%, enquanto o estado com menor índice apresentou uma taxa de 37.80% o de

maior apresentou uma de 67.30%. Veja, Tabelas 6.1 e 6.2 e Gráficos 6, 6.1 e 6.2.

**17**





Análise Estatística

Título do trabalho

**Tabela 6.1.** Tabela de frequência relativa à variável quantitativa *taxa de conclusão do*

*segundo grau*.

**Gráfico 6.1.** Histograma relativo à variável quantitativa contínua *taxa de conclusão do segundo*

*grau*.

**18**





Análise Estatística

Título do trabalho

**Gráfico 6.2.** Gráfico de densidade empírica relativo à variável quantitativa contínua *taxa de*

*conclusão do segundo grau.*

**Tabela 6.2.** Medidas descritivas relativas à variável quantitativa contínua *taxa de conclusão do*

*segundo grau*.

**19**





Análise Estatística

Título do trabalho

**Figura 6.** Boxplot relativo à variável quantitativa contínua *taxa de conclusão do segundo grau*.

**VII. Número de dias do ano com temperatura abaixo de 0:**

Os dados relativos aos dias são bastante particulares de cada estado e espaçados, tal

fato se deve a relação entre localização do estado e temperatura. Dessa forma, percebe-se que

os estados mais ao norte(maior latitude) apresentam uma quantidade maior de dias com

temperatura abaixo de 0 graus Celsius que os estados localizados mais ao sul (menor latitude).

O menor número de dias registrado foi 0 relativo ao Havaí (território anexado, fruto da ação

imperialista dos Estados Unidos, que se localiza em um arquipélago no Oceano Pacíficio,

localizado fora do território da América do Norte), a média é de 114 dias aproximadamente e o

máximo registrado foi de 188 dias.

**20**





Análise Estatística

Título do trabalho

**Tabela 6.2** Tabela de frequência variável *número de dias com temperatura abaixo de 0°C*.

**21**





Análise Estatística

Título do trabalho

**22**





Análise Estatística

Título do trabalho

**Gráfico 7.1.** Gráfico relativo à variável quantitativa discreta *número de dias do ano com*

*temperatura abaixo de 0°C*.

**Tabela 7.2.** Medidas descritivas relativas à variável quantitativa discreta *número de dias do ano*

*com temperatura abaixo de 0°C*.

**23**





Análise Estatística

Título do trabalho

**Figura 7.** Boxplot relativo à variável quantitativa discreta *número de dias do ano com*

*temperatura abaixo de 0°C*.

**VIII. Área do estado:**

Em relação às áreas dos estados, em milhas, 30(60%) estados possuem uma área

dentro do intervalo de 0 a 60000 milhas, 15(30%) estados possuem áreas entre 60.000 e

120.000 milhas, 2 (4%) estados com áreas entre 120.000 e 180.000 milhas, 2(4%) estados

com áreas entre 240.000 e 300.000 milhas e 1(2%) estado com área entre 540.000 e 600.000

milhas. O menor estado possui uma área de cerca de 1049 milhas, o maior estado possui área

de 655.432 milhas e a média nacional foi de 54.277 milhas.

**24**





Análise Estatística

Título do trabalho

**Tabela 8.1.** Tabela de frequência relativa à variável quantitativa *área em milhas*.

**25**





Análise Estatística

Título do trabalho

**Gráfico 8.1.** Histograma relativo à variável quantitativa contínua *área em milhas*.

**Gráfico 8.2.** Gráfico de densidade empírica relativo à variável quantitativa contínua *área em*

*milhas.*

**26**





Análise Estatística

Título do trabalho

**Tabela 8.2.** Medidas descritivas relativas à variável quantitativa contínua *área em milhas*.

**Figura 8.** Boxplot relativo à variável quantitativa contínua *área em milhas*.

**IX. Densidade populacional:**

Em relação a densidade populacional têm-se que 45(90%) estados possuem uma

densidade entre 0 e 0.44, 3(6%) estados possuem um índice entre 0.44 e 0.89, 1(2%) estado

entre 0.89 e 1.34 e 1 estado com índice entre 2.69 e 3.13, o cálculo é feito com base em:

*densidade = população / área*. O estado com menor densidade possui um índice de 0.000064,

o estado maior densidade tem índice de 2.68 e a média nacional foi de 0.06.

**27**





Análise Estatística

Título do trabalho

**Tabela 9.1.** Tabela de frequência relativa à variável quantitativa *densidade populacional*.

**28**





Análise Estatística

Título do trabalho

**Gráfico 9.1.** Histograma relativo à variável quantitativa contínua *densidade populacional*.

**Gráfico 9.2.** Gráfico de densidade empírica relativo à variável quantitativa contínua *densidade*

*populacional.*

**29**





Análise Estatística

Título do trabalho

**Tabela 9.2.** Medidas descritivas relativas à variável quantitativa contínua *densidade*

*populacional*.

**Figura 9.** Boxplot relativo à variável quantitativa contínua *densidade populacional*.

**3 ANÁLISE DESCRITIVA BIDIMENSIONAL**

**1. Renda per capita:**

Em geral, a renda per capita apresentou uma correlação positiva baixa (0,34) com a

expectativa de vida. Como pode ser constatado no gráfico 10.1, nas faixas mais baixas de

renda a correlação parece ser um pouco mais significativa, porém ainda insuficiente para inferir

conclusões precisas. Os dados se tornam mais difusos ainda a partir da faixa dos $4000 per

capita. Dessa forma, pelo menos na amostra coletada, a renda per capita não apresentou uma

correlação significativa com a expectativa de vida.

**30**





Análise Estatística

Título do trabalho

**Gráfico 10.1.** Gráfico de correlação entre expectativa de vida e renda per capita*.*

**2. Taxa de analfabetismo:**

A taxa de analfabetismo apresenta uma correlação negativa (-0,59) com a expectativa

de vida. Ademais, vale destacar que na amostra coletada nos extremos do gráfico parece haver

uma clara correlação entre a taxa de analfabetismo e a expectativa de vida. Apesar das

tendências constatadas nos extremos, no resto do gráfico constata-se uma correlação fraca

entre as duas variáveis e uma difusão dos dados. Por fim, é sabido que a taxa de

analfabetismo pode ser um indicativo para outros fatores que possam impactar de forma mais

direta na expectativa de vida, porém na amostra coletada ela não apresenta uma correlação

forte o bastante para se afirmar uma implicação direta.

**31**





Análise Estatística

Título do trabalho

**Gráfico 10.2.** Gráfico de correlação entre expectativa de vida e taxa de analfabetismo*.*

**3. Taxa de criminalidade:**

Dentre todas as variáveis analisadas, a taxa de criminalidade estabelece a correlação

negativa mais forte (-0,78) com a expectativa de vida. Assim sendo, é possível constatar

através do gráfico 10.3 uma tendência indicando que, em geral, uma taxa de criminalidade

mais baixa está associada a uma expectativa de vida mais alta. Vale ressaltar que, apesar de

ser possível constatar uma tendência, na amostra coletada alguns estados apresentam um

desvio significativo dessa tendência.

**32**





Análise Estatística

Título do trabalho

**Gráfico 10.3.** Gráfico de correlação entre expectativa de vida e taxa de criminalidade*.*

**4. Porcentagem de estudantes que concluem o ensino médio:**

A porcentagem de estudantes que concluem o ensino médio apresenta uma correlação

positiva de 0,58 com a expectativa de vida. Ao observar o gráfico 10.4 é possível constatar uma

dispersão dos dados e, em geral, uma baixa taxa de correlação. Apesar dessa dispersão geral,

nota-se que nas faixas mais altas do gráfico (tanto de porcentagem de conclusão do ensino

médio quanto de expectativa de vida) parece haver uma correlação mais forte entre as duas

variáveis em comparação às faixas mais baixas do gráfico, nas quais não constata-se

correlação nenhuma entre ambas as variáveis.

**33**





Análise Estatística

Título do trabalho

**Gráfico 10.4.** Gráfico de correlação entre expectativa de vida e porcentagem de conclusão do

ensino médio.

**5. Dias do ano com temperatura abaixo de 0°C:**

O número de dias do ano com temperatura abaixo de zero estabelece a correlação mais

fraca com a expectativa de vida, com uma taxa de correlação empírica de 0,26. Através do

gráfico é possível constatar uma dispersão alta dos dados, decorrente da baixa correlação

entre as duas variáveis.

**34**





Análise Estatística

Título do trabalho

**Gráfico 10.5.** Gráfico de correlação entre expectativa de vida e dias do ano com temperatura

abaixo de 0°C*.*

**6. Densidade populacional:**

A densidade populacional apresentou a correlação negativa mais baixa com a

expectativa de vida, com uma taxa de correlação empírica de -0,26. Além disso, pode ser

constatado através do gráfico 10.6 a dispersão nos dados e a concentração dos dados da

densidade populacional na faixa dos valores mais baixos do eixo das ordenadas.

**35**





Análise Estatística

Título do trabalho

**Gráfico 10.6.** Gráfico de correlação entre expectativa de vida e densidade populacional*.*

**4 ANÁLISE DE REGRESSÃO LINEAR SIMPLES**

Nesta seção, vamos conduzir algumas análises de regressão linear simples para

determinar quais variáveis são importantes para explicar a variabilidade da **expectativa de**

**vida**. Assumimos um nível de significância de 5% para os testes de hipóteses conduzidos para

este fim. Com o intuito de verificar se a regressão é linear, realizou-se para cada tipo de dado

dois testes de hipótese relativos às variáveis β0, que representa o valor esperado da

expectativa de vida média (variável resposta) quando a variável explicativa é zero e β1, que

representa a mudança na média dessa expectativa de vida quando aumenta-se uma unidade

no valor da variável explicativa.

**1. Expectativa de vida e renda per capita:**

Os resultados dos testes de hipótese para as variáveis β e β são apresentados na

0

1

Figura 10.1.

**36**





Análise Estatística

Título do trabalho

**Figura 10.1.** Resultado dos testes de hipótese de regressão linear entre expectativa de vida e a

renda per capita.

Analisando os testes de hipótese entre a expectativa de vida e a renda per capita

(Figura 10.1), observamos que é razoável assumir que existe uma relação linear entre as

variáveis em questão com um nível de significância de 5%.

**Gráfico 11.1.** Gráfico de dispersão com a reta

estimada entre a expectativa de vida e a renda per capita.

A partir do gráfico de dispersão (Gráfico 11.1), observamos que a expectativa de vida

aumenta conforme o aumento da renda per capita da população. Assim, há evidências de uma

relação linear crescente entre as variáveis, a qual é expressa pela seguinte equação estimada

푦 = (6, 758 × 10) + (7, 433 × 10⁻⁴)푥,

em que 푦 representa a expectativa de vida média dada uma renda per capita 푥 da população.

**37**





Análise Estatística

Título do trabalho

Nesse ínterim, observa-se dois parâmetros, β0 que representa o valor esperado da

expectativa de vida média quando a renda per capita é zero e β1 é a mudança na média dessa

expectativa de vida quando aumenta-se uma unidade no valor da renda per capita.

A adequabilidade da hipótese de que os erros do modelo linear simples são distribuídos

normalmente com variância constante pode ser verificada nos Gráficos 12.1 e 13.1.

**Gráfico 12.1.** Gráfico de variância constante entre expectativa de vida e renda per capita

**Gráfico 13.1.** Gráfico de normalidade entre expectativa de vida e renda per capita

Levando-se em conta que na análise bidimensional, apesar de apresentar uma taxa de

correlação positiva baixa (de 0, 34) entre renda per capita e expectativa de vida, têm-se com a

regressão linear, possuindo hipóteses confirmadas de que os erros do modelo linear simples

são distribuídos normalmente com variância constante, uma reiteração de resultados.

Apesar do gráfico de variância constante entre expectativa de vida e renda per capita

(Gráfico 12.1) não ter obtido um resultado regular, devido à ocorrência de outliers nas pontas,

**38**





Análise Estatística

Título do trabalho

isso não se torna um fator tão importante a ponto de rejeitar a hipótese de linearidade da

correlação em questão.

**2. Expectativa de vida e proporção de analfabetos:**

Os resultados dos testes de hipótese para as variáveis β e β são apresentados na

0

1

Figura 10.2.

**Figura 10.2.** Resultado dos testes de hipótese de regressão linear entre expectativa de

vida e proporção de analfabetos.

Analisando os testes de hipótese entre a expectativa de vida e a proporção de

analfabetos (Figura 10.2), observamos que é razoável assumir que existe uma relação linear

entre as variáveis em questão com um nível de significância de 0, 1%.

**Gráfico 11.2.** Gráfico de dispersão com a reta estimada entre expectativa de vida e

proporção de analfabetos*.*

**39**





Análise Estatística

Título do trabalho

A partir do gráfico de dispersão (Gráfico 11.2), observamos que a expectativa de vida

*diminui* conforme aumenta-se a proporção de analfabetos da população. Assim, há evidências

de uma relação linear decrescente entre as variáveis, a qual é expressa pela seguinte equação

estimada

푦 = 72, 395 − 1, 296푥,

em que 푦 representa a expectativa de vida média dada a proporção de analfabetos 푥 da

população.

Nesse ínterim, observa-se dois parâmetros, β0 que representa o valor esperado da

expectativa de vida média quando a proporção de analfabetos é zero e β1 é a mudança na

média dessa expectativa de vida quando aumenta-se uma unidade no valor da proporção de

analfabetos.

A adequabilidade da hipótese de que os erros do modelo linear simples são distribuídos

normalmente com variância constante pode ser verificada nos Gráficos 12.2 e 13.2.

**Gráfico 12.2.** Gráfico de variância constante entre expectativa de vida e proporção de

analfabetos.

**40**





Análise Estatística

Título do trabalho

**Gráfico 13.2.** Gráfico de normalidade

entre expectativa de vida e proporção de analfabetos.

Levando-se em conta que a análise bidimensional, apresentou uma correlação negativa

(-0,59) entre a proporção de analfabetos e expectativa de vida, têm-se com a regressão linear

possuindo hipóteses confirmadas de que os erros do modelo linear simples são distribuídos

normalmente com variância constante uma reiteração de resultados.

**3. Expectativa de vida e taxa de criminalidade:**

Os resultados dos testes de hipótese para as variáveis β e β são apresentados na

0

1

Figura 10.3.

**Figura 10.3.** Resultado dos testes de hipótese de regressão linear entre expectativa de

vida e taxa de criminalidade.

Analisando os testes de hipótese entre a expectativa de vida e a taxa de criminalidade

(Figura 10.3), observamos que é razoável assumir que existe uma relação linear entre as

variáveis em questão com um nível de significância de 0, 1%.

**41**





Análise Estatística

Título do trabalho

**Gráfico 11.3.** Gráfico de dispersão com a reta estimada entre expectativa de vida e taxa de

criminalidade*.*

A partir do gráfico de dispersão (Gráfico 11.3), observamos que é razoável assumir que

existe uma relação linear entre as variáveis em questão. Neste sentido, observamos que a

expectativa de vida *diminui* conforme aumenta-se a taxa de criminalidade. Assim, há evidências

de uma relação linear decrescente entre as variáveis, a qual é expressa pela seguinte equação

estimada

푦 = 72, 973 − ( 2, 839 푥 10−1) 푥,

em que 푦 representa a expectativa de vida média dada a taxa de criminalidade 푥 da população.

Nesse ínterim, observa-se dois parâmetros, β0 que representa o valor esperado da

expectativa de vida média quando a taxa de criminalidade é zero e β1 é a mudança na média

dessa expectativa de vida quando aumenta-se uma unidade no valor da taxa de criminalidade.

A adequabilidade da hipótese de que os erros do modelo linear simples são distribuídos

normalmente com variância constante pode ser verificada nos Gráficos 12.3 e 13.3.

**42**





Análise Estatística

Título do trabalho

**Gráfico 12.3.** Gráfico de variância constante entre expectativa

de vida e a taxa de criminalidade

**Gráfico 13.3.** Gráfico de normalidade entre expectativa de vida e a taxa de

criminalidade

Levando-se em conta que a análise bidimensional, apresentou uma correlação negativa

forte (-0,78) entre taxa de criminalidade e expectativa de vida, têm-se com a regressão linear

possuindo hipóteses confirmadas de que os erros do modelo linear simples são distribuídos

normalmente com variância constante uma reiteração de resultados.

**4. Expectativa de vida e porcentagem de estudantes com ensino**

**de segundo grau completo:**

Os resultados dos testes de hipótese para os coeficientes β e β são apresentados na

0

1

Figura 10.4.

**43**





Análise Estatística

Título do trabalho

**Figura 10.4.** Resultado dos testes de hipótese de regressão linear entre expectativa de

vida e a porcentagem de estudantes com segundo grau.

Analisando os testes de hipótese entre a expectativa de vida e a porcentagem de

estudantes que completam o segundo grau (Figura 10.4), observamos que é razoável assumir

que existe uma relação linear entre as variáveis em questão com um nível de significância de

0, 1%.

**Gráfico 11.4.** Gráfico de dispersão com a reta estimada entre expectativa

de vida e porcentagem de estudantes com segundo grau*.*

A partir do gráfico de dispersão (Gráfico 11.4), observamos que a expectativa de vida

aumenta conforme aumenta-se a porcentagem de estudantes com segundo grau completo.

Assim, há evidências de uma relação linear crescente entre as variáveis, a qual é expressa

pela seguinte equação estimada:

**44**





Análise Estatística

Título do trabalho

푦 = 65, 739 + (9, 676 푥 10−2)푥,

em que 푦 representa a expectativa de vida média dada a porcentagem de estudantes com o

segundo grau completo 푥 da população.

Nesse ínterim, observa-se dois parâmetros, β0 que representa o valor esperado da

expectativa de vida média quando a porcentagem de estudantes com o segundo grau completo

é zero e β1 é a mudança na média dessa expectativa de vida quando aumenta-se uma unidade

no valor da porcentagem de estudantes com o segundo grau completo.

A adequabilidade da hipótese de que os erros do modelo linear simples são distribuídos

normalmente com variância constante pode ser verificada nos Gráficos 12.4 e 13.4.

**Gráfico 12.4** Gráfico de variância constante entre expectativa

de vida e porcentagem de estudantes com ensino médio completo.

**Figura 13.4.** Gráfico de normalidade entre expectativa de

vida e porcentagem de estudantes com ensino médio completo.

**45**





Análise Estatística

Título do trabalho

Levando-se em conta que a análise bidimensional, apresentou uma correlação positiva

(0,58) entre porcentagem de estudantes com ensino médio completo e expectativa de vida,

têm-se com a regressão linear possuindo hipóteses confirmadas de que os erros do modelo

linear simples são distribuídos normalmente com variância constante uma reiteração de

resultados.

**5. Expectativa de vida e número de dias com temperaturas abaixo**

**de zero grau Celsius:**

Os resultados dos testes de hipótese para as variáveis β e β são apresentados na

0

1

Figura 10.5.

**Figura 10.5.** Resultado dos testes de hipótese de regressão linear entre expectativa de

vida e o número de dias do ano com temperatura abaixo de zero.

Com base nos resultados dos testes de hipótese conduzidos, verifica-se que, apesar do

teste para o coeficiente β0 permitir a aceitação do modelo linear para um nível de significância

de 0, 1%, o teste para o coeficiente β1 permite a aceitação do modelo linear apenas para um

nível de significância de 10%. Com base nesses resultados, e levando em conta o nível de

significância de 5% fixado para os testes conduzidos, conclui-se que não é razoável assumir

uma relação linear entre as duas variáveis em questão.

Levando-se em conta que na análise bidimensional a taxa de correlação entre o número

de dias do ano com temperatura abaixo de zero e a expectativa de vida indicou uma correlação

baixa entre as duas variáveis (0, 26), os testes de hipótese conduzidos reafirmam a baixa

correlação entre as duas variáveis em questão.

**6. Expectativa de vida e densidade demográfica:**

Os resultados dos testes de hipótese para as variáveis β e β são apresentados na

0

1

Figura 10.6.

**46**





Análise Estatística

Título do trabalho

**Figura 10.6.** Resultado dos testes de hipótese de regressão linear entre expectativa de vida e

densidade populacional.

Analisando os testes de hipótese entre a expectativa de vida e a densidade

populacional (Figura 10.6), observa-se que, assim como no caso do número de dias do ano

com temperatura abaixo de zero, não é razoável assumir que existe uma relação linear entre as

variáveis em questão. Apesar do coeficiente β0 permitir a aceitação do modelo linear para um

nível de significância de 0, 1%, o teste para o coeficiente β1 permite a aceitação do modelo

linear apenas para um nível de significância de 10%, dessa forma, fixado o nível de

significância de 5% para os testes, rejeita-se o modelo linear para as duas variáveis em

questão.

Observa-se também que o coeficiente de correlação obtido na análise bidimensional

das duas variáveis em questão (− 0, 26) é pouco significativo, fato este que reforça a não

adoção do modelo linear e a baixa relação entre as duas variáveis.

**5 CONSIDERAÇÕES FINAIS**

Após a análise dos dados apresentados pela situação problema, no qual desejava-se

explicar a expectativa de vida da população dos cinquenta (50) estados dos Estados Unidos

através da renda per capita, taxa de analfabetismo, taxa de criminalidade, grau de estudos,

dias do ano com temperaturas abaixo de 0°C e densidade populacional, obteve-se os seguintes

resultados relevantes analisados abaixo.

Número de dias do ano com temperaturas abaixo de zero graus celsius e densidade

populacional são fatores que possuem os menores impactos quanto à expectativa de vida

populacional, como visto acima ambos casos não passaram nos testes de hipótese para

verificar uma correlação linear entre cada variável e a expectativa de vida.

A baixa correlação entre renda per capita e a expectativa de vida da população se

contrapõe com a ideia inicial do grupo que, através de uma análise simplista, possuía uma

expectativa de correlação. Contudo, mesmo que ela tenha passado no teste de hipótese para

ser considerada uma regressão linear, outros fatores indicam uma menor correlação entre as

**47**





Análise Estatística

Título do trabalho

variáveis: ela apresentou um coeficiente de correlação baixo de 0,34, apresentou um nível de

significância maior que as outras que também passaram nos testes (de 5%) e teve o gráfico de

variância constante fora de um resultado regular.

Além disso, a taxa de analfabetismo e a porcentagem de estudantes que concluem o

ensino médio possuem semelhante correlação moderada. A primeira possui coeficiente

negativo de -0,59, significando que quanto menor a população de analfabetos no local, maior a

expectativa de vida da mesma. Concomitantemente, a segunda apresenta coeficiente positivo

de 0,58, ou seja, quanto maior a população que possui grau de ensino médio completo, maior a

expectativa de vida local.

Por fim, a maior correlação apresentada entre as características da população local e

sua expectativa de vida foi a taxa de criminalidade do Estado, possuindo um coeficiente

negativo de -0,78. Por conseguinte, quanto menor a taxa de criminalidade, o local em questão

apresenta maior expectativa de vida.

Concomitantemente, ao realizar os testes de hipótese das correlações lineares, feitos

através da regressão linear simples entre as variáveis, é possível observar uma reiteração de

resultados entre a regressão e a análise bidimensional. Dessa forma, explícita-se que esta

análise foi capaz de descrever uma relação entre as características observadas.

Dessa forma, conclui-se que a criminalidade é um fator determinante para analisar a

expectativa de vida de uma população, possuindo uma relação inversamente proporcional que

explica a problemática apresentada neste trabalho e, outrossim, a taxa de analfabetismo e a

porcentagem de estudantes com ensino médio completo auxiliam, também, na interpretação

desta como fatores secundários.

**48**





Análise Estatística

Título do trabalho

**REFERÊNCIAS BIBLIOGRÁFICAS**

BUSSAB, Wilton de O.; MORETTIN, Pedro A. **Estatística básica**. Saraiva, 2010

**49**

