## DrugAnalytics


Thiago Rocha Amaral, thiago.amaral@sga.pucminas.br

Bernardo Costa Lima Bentes, bclbentes@sga.pucminas.br

Iury da Mota Santos, iury.mota@sga.pucminas.br

Artur Braga Mota, artur.braga@sga.pucminas.br

---

## Professor:

Prof. Hugo Bastos de Paula

---

_Curso de Ciência de Dados, Unidade Praça da Liberdade_ 

_Instituto de Informática e Ciências Exatas – Pontifícia Universidade de Minas Gerais (PUC MINAS), Belo Horizonte – MG – Brasil_

---

_**Resumo**. Escrever aqui o resumo. O resumo deve contextualizar rapidamente o trabalho, descrever seu objetivo e, ao final, 
mostrar algum resultado relevante do trabalho (até 10 linhas)._

---


## Introdução

Atualmente, vivemos em um mundo onde as drogas representam um dos principais problemas da sociedade mundial quando se analisa o cenário global. De acordo com o relatório da United Nations Office on Drugs and Crime (UNODC), divulgado em junho de 2023, o número de pessoas que sofrem de transtornos associados ao uso de drogas subiu para 39,5 milhões, um aumento de 45% em 10 anos.

Olhando um pouco mais para o nosso país, o problema é nítido e preocupante, tendo em vista que o Brasil é o segundo maior consumidor de cocaína e seus derivados entre todos os países do mundo, segundo uma pesquisa feita pela Unifesp com dados da Organização Mundial da Saúde (OMS). Esses dados são alarmantes e levantam várias questões sobre o que podemos fazer para melhorar essa perspectiva.

Diante desse cenário, nosso trabalho está focado em desenvolver um sistema inteligente capaz de analisar bancos de dados existentes e oferecer um feedback personalizado de acordo com o interesse do usuário, seja ele uma entidade privada ou pública. O sistema será desenvolvido para análise de grande quantidade de dados, baseando-se em bancos de dados de credibilidade e com uma frequência constante de atualizações dos dados que estarão à disposição do cliente.

A ideia é centralizar os dados em um único lugar para que, por meio deles, medidas mais assertivas possam ser tomadas e para que o índice de eficácia seja o mais próximo do projetado, atacando diretamente problemas relacionados à dependência química que são continuamente vistos nos jornais, noticiários e, principalmente, nas ruas dia após dia.

###    Problema

Com base nas informações apresentadas anteriormente, podemos afirmar com clareza que nosso sistema será uma parte fundamental para resolver o problema do crescimento do número de usuários de drogas no Brasil e no mundo, o qual tem alarmado especialistas e analistas sobre o futuro em relação às drogas. Assim, o sistema será aplicado em empresas que atuem na área de estatística, saúde e segurança, fornecendo a tecnologia necessária e qualificada para que elas tenham auxílio na hora de extrair as informações a partir do máximo de dados disponíveis e correlacionados.

###    Objetivo geral

* Implementar um sistema de inteligência artificial que apoie organizações privadas e governamentais, fornecendo dados precisos e fundamentais para a luta contra o vício em substâncias e a reintegração desses indivíduos na sociedade.

####    Objetivos específicos

* Criar um sistema que opere de forma ágil e eficiente, capaz de apoiar uma variedade de soluções e propostas.
* Assegurar que o sistema possa correlacionar os tópicos pesquisados pelo usuário, oferecendo informações mais abrangentes e análises atualizadas sobre o tema em questão.
* Utilizar dados para gerar conceitos que possam auxiliar na luta contra o vício em substâncias.
* Promover a reintegração eficaz de pessoas viciadas na sociedade através do uso de dados precisos e vitais.

###    Justificativas

O conceito do projeto da DrugAnalytics tem como finalidade identificar um padrão de comportamento em indivíduos que estão ou estiveram inseridos no contexto do mundo das drogas a fim sintonizar alguma solução necessária e precisa para cada caso particular. A motivação por trás de todo o trabalho está em utilizar dos conhecimentos que partem tanto da análise de dados quanto das ferramentas tecnológicas para retornar positivamente para o mundo. O projeto além de funcionar como material de estudo comportamental orientado a partir de dados, também faz sua parte como ação social em ajudar milhares de famílias.

Tendo em vista que a parcela da população mais vulnerável à entrada no mundo das drogas é a porção pobre e periférica, a análise de comportamento dos dados será direcionada majoritariamente a esse público. As bases de dados e informações que o algoritmo utilizará para o seu processamento será o IBGE, UNODC, GOV BR e Health Lake



##    Público alvo
Grupos demográficos específicos: Dependendo do contexto, o público-alvo pode incluir grupos demográficos específicos, como adolescentes, jovens adultos, idosos, pessoas de baixa renda, minorias étnicas, etc. Estes grupos podem ser mais suscetíveis ao uso de certas drogas ou enfrentar desafios únicos relacionados ao uso de drogas.

Profissionais de saúde: Médicos, enfermeiros, farmacêuticos e outros profissionais de saúde podem ser um público-alvo importante, especialmente se a pesquisa se concentrar em políticas de prescrição, tratamento de dependência ou prevenção de overdose.

Profissionais da área de saúde mental: Psicólogos, psiquiatras, assistentes sociais e outros profissionais de saúde mental podem estar interessados em pesquisas sobre o uso de drogas e seu impacto na saúde mental.

Policiais e agentes de aplicação da lei: Se a pesquisa se concentrar em questões legais relacionadas às drogas, o público-alvo pode incluir policiais, agentes de aplicação da lei e funcionários do sistema judiciário.

Educadores e pais: Professores, orientadores escolares, pais e outros responsáveis pela educação de jovens podem ser um público-alvo importante para pesquisas sobre prevenção do uso de drogas e intervenções precoces.

Tomadores de decisão políticos: Políticos, legisladores e formuladores de políticas podem se beneficiar de pesquisas sobre drogas para informar a criação de leis e regulamentos relacionados ao uso de drogas, tratamento de dependência e prevenção.

Pesquisadores e acadêmicos: Outros cientistas e pesquisadores na área da saúde, ciência social e campos relacionados podem ser um público-alvo para estudos sobre drogas, especialmente aqueles que buscam avançar o conhecimento científico sobre o tema.

## Análise exploratórida dos dados

###    Dicionário de dados
Base de dados 1: GOV BR

Base de Dados 2: Kaggle

| Atríbuto | Descrição | Tipo de dado |
| --- | --- | --- |
| Necessidade |Observa o quanto o indivíduo sente a necessidade do uso numa escala de "1" a "10" | Númerico |
| Frequência | Observa a frequência do uso da substância | Númerico |
| Relações | Observa a relação do uso com as relações pessoais/profissionais do indivíduo | Númerico |
| Dificuldade | Observa as dificuldades e desafios para a superação do vício | Númerico |
| Sexo | O sexo dos usuários | Textual |
| Faixa etária | A idade dos usuários em média | Númerico |
| Renda | Classificação em relação a renda | Númerico |
| Influencia/Maturidade | Atributo que observa se a idade do individuo foi um determinante para o uso ou nao. | Númerico |
| Escolaridade | Atributo que observa se a escolaridade é um fator excludente no uso de drogas, analisando se indivíduos com diferentes níveis de educação têm propensões variadas para o consumo de substâncias ilícitas. | Númerico |
| Etnia | Atributo que observa se a etnia é um fator influente no uso de drogas, analisando se indivíduos de diferentes origens étnicas têm propensões variadas para o consumo de substâncias ilícitas. | Númerico |
| Região | Região onde há maior número de usuários | Textual |
| Assistência | Quantas vezes o usuário ja recebeu auxílio de ajuda especializada | Numérico |
| Nscore | Indivíduos com pontuação alta em neuroticismo têm maior probabilidade do que a média de serem mal-humorados e de experimentar sentimentos como ansiedade, preocupação, medo, raiva, frustração, inveja, ciúme, culpa, humor deprimido e solidão. | Númerico |
| Escore | Uma pessoa com pontuação alta em extroversão em um teste de personalidade é a vida da festa. Gostam de estar com as pessoas, de participar de reuniões sociais e são cheios de energia. | Númerico |
| Oscore | Uma pessoa com um alto nível de abertura para experiências em um teste de personalidade gosta de experimentar coisas novas. Eles são imaginativos, curiosos e de mente aberta. Indivíduos com baixa abertura à experiência preferem não tentar coisas novas. Eles têm a mente fechada, são literais e gostam de ter uma rotina. | Númerico |
| Ascore | Uma pessoa com alto nível de agradabilidade em um teste de personalidade geralmente é calorosa, amigável e diplomática. Geralmente têm uma visão otimista da natureza humana e se dão bem com os outros. | Númerico |
| Cscore | Uma pessoa com pontuação alta em consciência geralmente possui um alto nível de autodisciplina. Esses indivíduos preferem seguir um plano, em vez de agir espontaneamente.  | Númerico |
| Impulsive | Na psicologia, a impulsividade (ou impulsividade) é uma tendência a agir por capricho, exibindo um comportamento caracterizado por pouca ou nenhuma premeditação, reflexão ou consideração das consequências.Se você descreve alguém como impulsivo, quer dizer que ele faz as coisas de repente, sem pensar primeiro nelas com cuidado.  | Númerico |




###    Descrição de dados
###    Dados Númericos:

- pessoas a cada mil habitantes em situição de vicio
- expectativa de vida média de um usuário
- Sexo: masculino ou feminino
- Faixa etária: faixa etária dos usuários
 
 
###    Dados Qualitativos:
-Droga mais utilizada
- droga homem ou mulher
- droga hospital
- droga vicio
- Localidade: área da cidade onde usuários vivem


| Atríbuto | Descrição | Tipo de dado |
| --- | --- | --- |
| Frequência | Observa a frequência do uso da substância | Númerico |
| Sexo | O sexo dos usuários | Textual |
| Faixa etária | A idade dos usuários em média | Númerico |
| Renda | Classificação em relação a renda | Númerico |
| Escolaridade | Atributo que observa se a escolaridade é um fator excludente no uso de drogas, analisando se indivíduos com diferentes níveis de educação têm propensões variadas para o consumo de substâncias ilícitas. | Númerico |
| Etnia | Atributo que observa se a etnia é um fator influente no uso de drogas, analisando se indivíduos de diferentes origens étnicas têm propensões variadas para o consumo de substâncias ilícitas. | Númerico |
| Região | Região onde há maior número de usuários | Textual |





|     Comparação entre idade e a frequência de uso de ecstasy. |  Comparação entre idade e a frequência de uso de Alcool. |
| --- | --- |
|![Comparação entre idade e a frequência de uso de ecstasy.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Idade%20frequencia%20de%20uso.png?raw=true](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Idade%20frequencia%20de%20uso.png?raw=true)) | ![Comparação entre idade e a frequência de uso de Alcool.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Alcool%20e%20idade.png?raw=true) |
|  |  |
|     Comparação entre gênero e a frequência de uso de ecstasy. |     Comparação entre gênero e a frequência de uso de Alcool. | 
|  |  |
| ![Comparação entre gênero e a frequência de uso de ecstasy.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Genero%20e%20frequencia%20de%20uso.png?raw=true) | ![Comparação entre gênero e a frequência de uso de Alcool.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Alcool%20e%20genero.png?raw=true) |
|  |  |
|     Comparação entre educação e a frequência de uso de ecstasy. |    Comparação entre educação e a frequência de uso de Alcool. | 
|  |  |
| ![Comparação entre educação e a frequência de uso de ecstasy.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Educacao%20e%20frequencia%20de%20uso.png?raw=true) | ![Comparação entre educação e a frequência de uso de Alcool.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Alcool%20e%20educacao.png?raw=true) |
|  |  |
###    Comparação entre países e a frequência de uso de ecstasy.
![Comparação entre países e a frequência de uso de ecstasy.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Pais%20e%20frequencia%20de%20uso.png?raw=true)

###    Comparação entre etnias e a frequência de uso de ecstasy.
![Comparação entre etnias e a frequência de uso de ecstasy.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Etnias%20e%20a%20frequencia%20de%20uso.png?raw=true)

###    Relação entre o neuroticismo e o Consumo de Alcool.
![Relação entre o neuroticismo e o consumo de Alcool.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Rnc.png?raw=true)

- Baixa Concentração: 2º e 3° linhas
- Leve Concentração: 4° linha 
- Alta Concentração: 1°, 5°, 6° e 7° linhas
- (alta quantidade de dados nas linhas 4, 5 e 6)

###    Relação entre a extroversão e o Consumo de Alcool.
![Relação entre a extroversão e o consumo de Alcool.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Ena.png?raw=true)

- Baixa Concentração: 2º, 3° e 4° linhas
- Leve Concentração: 1°, 5°, 6° e 7° linhas 
- Alta Concentração: Nenhuma
- (alta quantidade de dados nas linhas 5, 6 e 7)

###    Relação entre o Oscore e o Consumo de Alcool.
![Relação entre o Oscore e o consumo de Alcool.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Oscore.png?raw=true)

- Baixa Concentração: 2º, 3° e 4° linhas
- Leve Concentração: 1°, 5°, 6° e 7° linhas 
- Alta Concentração: Nenhuma
- (alta quantidade de dados nas linhas 5, 6 e 7)

###    Relação entre o Ascore e o Consumo de Alcool.
![Relação entre o Ascore e o consumo de Alcool.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Ascore.png?raw=true)

- Baixa Concentração: 2º, 3° e 4° linhas
- Leve Concentração: 1° linha
- Alta Concentração: 5°, 6° e 7° linhas
- (alta quantidade de dados nas linhas 5, 6 e 7)

###    Relação entre a Cscore e o Consumo de Alcool.
![Relação entre a Cscore e o consumo de Alcool.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Cscore.png?raw=true)

- Baixa Concentração: 2º, 3° e 4° linhas
- Leve Concentração: 1° linha
- Alta Concentração: 5°, 6° e 7° linhas
- (alta quantidade de dados nas linhas 1, 5, 6 e 7)

###    Relação entre a Impulsive e o Consumo de Alcool.
![Relação entre a Impulsive e o consumo de Alcool.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Impulsive.png?raw=true)

- Baixa Concentração: Todas as linhas
- Leve Concentração: Nenhuma
- Alta Concentração: Nenhuma
- (quantidade de dados muito espalhadas em todas as linhas)


## Preparação dos dados

## Seleção dos atributos

| Atríbuto | Descrição | Tipo de dado |
| --- | --- | --- |
| Nscore | Indivíduos com pontuação alta em neuroticismo têm maior probabilidade do que a média de serem mal-humorados e de experimentar sentimentos como ansiedade, preocupação, medo, raiva, frustração, inveja, ciúme, culpa, humor deprimido e solidão. | Númerico |
| Escore | Uma pessoa com pontuação alta em extroversão em um teste de personalidade é a vida da festa. Gostam de estar com as pessoas, de participar de reuniões sociais e são cheios de energia. | Númerico |
| Oscore | Uma pessoa com um alto nível de abertura para experiências em um teste de personalidade gosta de experimentar coisas novas. Eles são imaginativos, curiosos e de mente aberta. Indivíduos com baixa abertura à experiência preferem não tentar coisas novas. Eles têm a mente fechada, são literais e gostam de ter uma rotina. | Númerico |
| Ascore | Uma pessoa com alto nível de agradabilidade em um teste de personalidade geralmente é calorosa, amigável e diplomática. Geralmente têm uma visão otimista da natureza humana e se dão bem com os outros. | Númerico |
| Cscore | Uma pessoa com pontuação alta em consciência geralmente possui um alto nível de autodisciplina. Esses indivíduos preferem seguir um plano, em vez de agir espontaneamente.  | Númerico |
| Impulsive | Na psicologia, a impulsividade (ou impulsividade) é uma tendência a agir por capricho, exibindo um comportamento caracterizado por pouca ou nenhuma premeditação, reflexão ou consideração das consequências.Se você descreve alguém como impulsivo, quer dizer que ele faz as coisas de repente, sem pensar primeiro nelas com cuidado.  | Númerico |
| Alcohol | Consumo de Álcool | Númerico |

## Tratamentos dos valores faltantes ou omissos: remoção, substituição, indução, etc.

Durante a analise e exploração dos dados, foi constatado que nao houveram informacoes omissas, campos vazios. Tambem nao foi necessario a primeiro momento a retirada de nenhuma das colunas, sendo todas utilitarias e essenciais para o avanço do trabalho.

![Tratamentos dos valores faltantes ou omissos: remoção, substituição, indução, etc.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Omissos.jpg?raw=true)

- A tabela acima mostra todos os dados utilizados durante o trabalho, entre eles se encontram divididos por três seleções de atributos: 

- Atributos Iniciais: ID, Age, Gender, Education, Country, Ethnicity
- Atributos Criados para Analise Nsscore, Escore, Oscore, Ascore, Cscore, Impulsive
- Os Tipos de Drogas Analisadas: Alcohol, Ecstasy...

## Indução de modelos

### Modelo 1: Regressão linear.

A escolha da regressão linear como Modelo 1 baseou-se na sua capacidade de modelar de forma linear entre as variáveis. Como nosso objetivo é prever o consumo de álcool com base em características individuais, a regressão linear é apropriada, pois permite interpretar o impacto de cada variável independente de forma direta e transparente.

Durante o processo de treinamento, os dados obtidos foram reservados em 20% para dados de teste e 80% para treinamento.


### Modelo 2: GradientBoosting.

A escolha do GradientBoosting como Modelo 2, foi decidida, pela capacidade construtiva a partir de árvores de decisão sequenciais. O objetivo continuou a prever o consumo de x substância  com base nas caracteristicas indivividuais de cada participante inscrito dentro do dataset.


## Resultados

### Resultados obtidos com o modelo 1. (Acurácia da Regressão: 0.3994413407821229)

Utilização do método de regressão linear. Primeira Acurácia do modelo. Relatorio de Classificação. Matriz de confusão.

-Código do modelo de regressão linear

![Algoritmo de regressao.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Algoritmo%20de%20regressao.jpeg%202.jpeg?raw=true)

-Gráfico da Acurácia da Regressão Linear

![Resultados obtidos com o modelo 1.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/Acuracia%202.png?raw=true)

-Acurácia do modelo 1: 0.4

-Relatorio de Classificação.

![Relatorio da classificacao.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Relatorio%20d%20classificacao%5D.jpeg?raw=true)

Precisão: O relatorio junto ao treinamento trouxe uma porcentagem precisa de 41% das instâncias dentro de uma das classificaçoes.

Recall: O relatorio junto ao treinamento trouxe uma porcentagem de 0.92% de acertividade em relação ao conjunto presente verificado.

F-Score: Com 0.57% de acertividade o treinamento mostrou um equilibrio balanceado entre as métricas precisão e recall.

É necessario a maximização de precisão e recall para todas as classes.

-Matriz de Confusão

![Matriz de Confusão](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Matriz%20de%20C.jpeg?raw=true)

É possivel observar que em quase todas as linhas houveram erros de classificação, os valores estão em classes distintas.
A parte com maior exploração dentro desta matriz foi na quarta linha que houveram 136 elementos corretamente classificados em suas classes, onde somente 12 elementos foram inchertados dentro desta classe "usou na ultima semana" incorretamente, pois deveriam pertencer a outra classe.


### Interpretação do modelo 1

Relacionado a interpretação do primeiro modelo, ao obter o resultado de 40% de precisão conseguimos perceber, mesmo que com o percentual baixo de precisão, é possivel extrair comportamentos entre as relações que foram usadas de parametro (Nscore, Escore, Oscore, Ascore, Cscore, Impulsive, Alcool). Em um exemplo específico, como o Nscore, que aborda todo o aspecto neurobiológico do indivíduo, as análises indicam uma correlação significativa entre os dois.


### Resultados obtidos com o modelo 2. (Acurácia do GradientBoosting: 0.83 > Heroin) (Acurácia do GradientBoosting: 0.37 > Alcool) 

Utilização do método de GradientBoosting. Localizar as strings classificatórias e substituí-las por valores numéricos. Cross validation. Segunda Acurácia do modelo. Relatorio de Classificação. 

-Código do modelo de GradientBoosting. 

-Localizar as strings classificatórias e substituí-las por valores numéricos.

![Algoritmo de GradientBoosting.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/cl.jpeg?raw=true)

-Possiveis atributos coorelacionaveis.

![Algoritmo de GradientBoosting.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/colunas.jpeg?raw=true)

-Definindo as variaveis X e Y do modelo.(Target_Heroin).

![Algoritmo de GradientBoosting.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Alvo%20e%20parametros.jpeg?raw=true)

-Definindo as variaveis X e Y do modelo.(Target_Alcool).

![Algoritmo de GradientBoosting.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/Alvo%20e%20parametros%202.jpeg?raw=true)

-Inicializando o modelo.

![Algoritmo de GradientBoosting.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/modelfit.jpeg?raw=true)

-Relatorio de classificação(Alcool).

![Algoritmo de GradientBoosting.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/resultado%20alcool.jpeg?raw=true)

-Relatorio de classificação(Heroin).

![Algoritmo de GradientBoosting.](https://github.com/ICEI-PUC-Minas-PPL-CD/ppl-cd-pcd-sist-int-2024-1-druganalytics/blob/main/docs/imagens/resultado%20heroin.jpeg?raw=true)


### Interpretação do modelo 2

Relacionado a interpretação do segundo modelo, a utilização do método de GradientBoostingao obteve um melhor resultado de precisão em relação ao primeiro modelo utilizado, o percentual de precisão foi significativamente melhor, principalmente olhando para a acurácia da droga Heroin, sendo possivel extrair comportamentos entre as relações que foram usadas de parametro.


## Análise comparativa dos modelos

## Relatorios: 

### Modelo 1: Regressão linear.

| Classe | Precisão | Recall | F1-Score | Support |
| --- | --- | --- | --- | --- |
| Nunca Usou | 0.00 | 0.00 | 0.00 | 5 |
| Usou a Mais de uma Década | 0.00 | 0.00 | 0.00 | 7 |
| Usou na última década | 0.00 | 0.00 | 0.00 | 8 |
| Usou na última semana | 0.41 | 0.92 | 0.57 | 148 |
| Usou no último ano | 0.00 | 0.00 | 0.00 | 37 |
| Usou no último mês | 0.00 | 0.00 | 0.00 | 55 |
| Usou nos últimos dias | 0.23 | 0.07 | 0.11 | 98 |

- Regressão linear "Alcohol":
- Métricas:
- Acurácia: 0.39%

### Modelo 2: GradientBoosting. // Alcohol

| Classe | Precisão | Recall | F1-Score | Support |
| --- | --- | --- | --- | --- |
| Nunca Usou | 1.00 | 0.47 | 0.64 | 34 |
| Usou a Mais de uma Década | 1.00 | 0.74 | 0.85 | 34 |
| Usou na última década | 0.97 | 0.46 | 0.62 | 68 |
| Usou na última semana | 0.94 | 0.31 | 0.47 | 198 |
| Usou no último ano | 0.95 | 0.28 | 0.44 | 287 |
| Usou no último mês | 0.55 | 0.94 | 0.69 | 759 |
| Usou nos últimos dias | 0.70 | 0.49 | 0.58 | 505 |

- GradientBoosting "Heroin":
- Métricas:
- Acurácia: 0.37%

### Modelo 2.1: GradientBoosting. // Heroin

| Classe | Precisão | Recall | F1-Score | Support |
| --- | --- | --- | --- | --- |
| Nunca Usou | 0.91 | 1.00 | 0.95 | 1605 |
| Usou a Mais de uma Década | 0.97 | 0.43 | 0.59 | 68 |
| Usou na última década | 1.00 | 0.32 | 0.48 | 94 |
| Usou na última semana | 1.00 | 0.35 | 0.52 | 65 |
| Usou no último ano | 1.00 | 0.75 | 0.86 | 24 |
| Usou no último mês | 1.00 | 0.94 | 0.97 | 16 |
| Usou nos últimos dias | 1.00 | 1.00 | 1.00 | 13 |

- GradientBoosting "Alcohol":
- Métricas:
- Acurácia: 0.83%

### Análise Comparativa:

Durante a utilização dos modelos e obtendo seus resultados, é possível ver a disparidade relacionada ao processamento de informações ao lidar com algumas classes desbalanceadas como temos neste dataset. O modelo Gradient Boosting, por conseguir capturar diferentes aspectos dos dados, devido, por exemplo, à não linearidade das ações executadas no modelo, consegue modelar relações mais complexas, identificar os erros ao longo das iterações e, assim, otimizar o desempenho do modelo. Desta forma, o modelo de regressão linear é mais simples e direto, não capturando a complexidade do dataset como um todo, sendo inviável sua utilização em um conjunto de dados com tantas variações.


## 8. Conclusão

Ao londo do trabalho, exploramos diferentes perspectivas a respeito dos dados, desde características demograficas ate traços de personalidade, utilizando modelos como regressão linear e GradientBoosting para consguir prever comportamentos relacionados ao consumo de diversas substâncias. Os resultados obtidos, embora desafiadores por haverem algumas falahas durante o processo, apontaram para avanços significativos na compreenção dos fatores que inflenciam o uso de drogas e na capacidade preditiva dos modelos que foram utilizados no trabalho.
Assim, o projeto do DrugAnalytics não apenas mostra um caminho para se lidar com as substâncias, para melhorar políticas públucas ou ações do setor privado, mas também destaca o quão importantes são as abordagens baseadas nos dados, para enfrentar um problema de tamanha complexicidade e porporção como é o das drogas. A análise feita durante o trabalho não está limitada apenas a estáticas, mas sim, propõe um sistema dinâmico e adaptável, o que é essencial para lidar com as diversas possibilidades de cenários quando se trata de um assunto longevo e desafiador como esse.
Portanto, como menção final, o projeto abre novas possibilidades de pesquisa e coleta de dados e informações, mas não está apenas vinculado a isso, reforçando a necessidade da colaboração entre a ciência de dados e a saúde pública e privada para conseguir melhorar cada vez mais o fornecimento de conhecimento, e para que consequentemente as pessoas responsáveis por essas aréas tenham a disposição dados confiáveis para serem tomadas as melhoes decisões em prol da sociedade. 

Os resultados obtidos pelo sistema:

Vantagens: 

- Precisão na Análise: Atráves dos modelos induzidos como Regressão Linear e Gradient Boosting foi possível processar uma quantidade consideravel de dados de maneira eficiente, não apenas prevendo o consumo de drogas, mas fornecendo análises coerentes para identificar padrões de comportamento e fatores de risco associados.
- Visualização de Dados: A utilização de gráficos e tabelas para apresentar os resultados facilita a interpretação das análises, tornando as informações acessíveis e compreensíveis para diferentes usuários.
- Análises a Partir de Dados Diversificados: A partir da utilização dos scores, foi possível fazer uma avaliação entre as relações das substâncias com aspectos sociais como educação, idade e gênero, enriquecendo as análises com informações relevantes e atualizadas.

Uma conclusão deve ter 3 partes:

	 * Apresenação geral dos resultados obtidos com discussão das vantagens e desvantagens do sistema inteligente
	 * Limitações e possibilidades de melhoria


# REFERÊNCIAS

Como um projeto de sistema inteligente não requer revisão bibliográfica, 
a inclusão das referências não é obrigatória. No entanto, caso você 
tenha utilizado referências na introdução ou deseje 
incluir referências relacionadas às tecnologias, padrões, ou metodologias 
que serão usadas no seu trabalho, relacione-as de acordo com a ABNT.

Verifique no link abaixo como devem ser as referências no padrão ABNT:

http://www.pucminas.br/imagedb/documento/DOC\_DSC\_NOME\_ARQUI20160217102425.pdf

Por exemplo:

**[1]** - _ELMASRI, Ramez; NAVATHE, Sham. **Sistemas de banco de dados**. 7. ed. São Paulo: Pearson, c2019. E-book. ISBN 9788543025001._

**[2]** - _COPPIN, Ben. **Inteligência artificial**. Rio de Janeiro, RJ: LTC, c2010. E-book. ISBN 978-85-216-2936-8._

**[3]** - _CORMEN, Thomas H. et al. **Algoritmos: teoria e prática**. Rio de Janeiro, RJ: Elsevier, Campus, c2012. xvi, 926 p. ISBN 9788535236996._

**[4]** - _SUTHERLAND, Jeffrey Victor. **Scrum: a arte de fazer o dobro do trabalho na metade do tempo**. 2. ed. rev. São Paulo, SP: Leya, 2016. 236, [4] p. ISBN 9788544104514._

**[5]** - _RUSSELL, Stuart J.; NORVIG, Peter. **Inteligência artificial**. Rio de Janeiro: Elsevier, c2013. xxi, 988 p. ISBN 9788535237016._



# APÊNDICES

**Colocar link:**

Do código (armazenado no repositório);

Dos artefatos (armazenado do repositório);

Da apresentação final (armazenado no repositório);

Do vídeo de apresentação (armazenado no repositório).




