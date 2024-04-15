## DrugAnalytics


Thiago Rocha Amaral, thiago.amaral@sga.pucminas.br

Bernardo Costa Lima Bentes, bclbentes@sga.pucminas.br

Rafael Mendes de Lacerda, rafael.lacerda.1463293@sga.pucminas.br

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
| Idade | A idade dos usuários em média | Númerico |




###    Descrição de dados
###    Dados Númericos:
-
-
-
-
-
###    Dados Qualitativos:
-Qual droga é a mais utilizada 
- Quem utiliza mais droga, o homem ou a mulher ?
- Qual droga faz as pessoas irem buscar ajuda nos hospitais
- Qual droga é a mais (viciante)

Utilize a análise descritiva baseada em estatística de primeira ordem para descrever os dados.
Como descrever dados numéricos: média, desvio padrão, mínimo, máximo, quartis, histograma, etc.
Como descrever dados qualitativos (categóricos): moda (valor mais frequente), quantidade de valores distintos (categorias), distribuição das categorias (histograma), etc.


## Preparação dos dados

A preparação dos dados consiste dos seguintes passos:

> - Seleção dos atributos
> - Tratamentos dos valores faltantes ou omissos: remoção, substituição, indução, etc.
> - Tratamento dos valores inconsistentes: conversão, remoção de dados duplicados, remoção ou tratamento de ouliers.
> - Conversão de dados: p. ex. numérico para categórico, categórico para binário, etc.


## Indução de modelos

### Modelo 1: Algoritmo

Substitua o título pelo nome do algoritmo que será utilizado. P. ex. árvore de decisão, rede neural, SVM, etc.
Justifique a escolha do modelo.
Apresente o processo utilizado para amostragem de dados (particionamento, cross-validation).
Descreva os parâmetros utilizados. 
Apresente trechos do código utilizado comentados. Se utilizou alguma ferramenta gráfica, apresente imagens
com o fluxo de processamento.

### Modelo 2: Algoritmo

Repita os passos anteriores para o segundo modelo.


## Resultados

### Resultados obtidos com o modelo 1.

Apresente aqui os resultados obtidos com a indução do modelo 1. 
Apresente uma matriz de confusão quando pertinente. Apresente as medidas de performance
apropriadas para o seu problema. 
Por exemplo, no caso de classificação: precisão, revocação, F-measure, acurácia.

### Interpretação do modelo 1

Apresente os parâmetros do modelo obtido. Tentre mostrar as regras que são utilizadas no
processo de 'raciocínio' (*reasoning*) do sistema inteligente. Utilize medidas como 
o *feature importances* para tentar entender quais atributos o modelo se baseia no
processo de tomada de decisão.


### Resultados obtidos com o modelo 2.

Repita o passo anterior com os resultados do modelo 2.

### Interpretação do modelo 2

Repita o passo anterior com os parâmetros do modelo 2.


## Análise comparativa dos modelos

Discuta sobre as forças e fragilidades de cada modelo. Exemplifique casos em que um
modelo se sairia melhor que o outro. Nesta seção é possível utilizar a sua imaginação
e extrapolar um pouco o que os dados sugerem.


### Distribuição do modelo (opcional)

Tende criar um pacote de distribuição para o modelo construído, para ser aplicado 
em um sistema inteligente.


## 8. Conclusão

Apresente aqui a conclusão do seu trabalho. Discussão dos resultados obtidos no trabalho, 
onde se verifica as observações pessoais de cada aluno.

Uma conclusão deve ter 3 partes:

   * Breve resumo do que foi desenvolvido
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




