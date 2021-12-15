
# MACHINE LEARNING EM DRUG DISCOVERY
![banner](https://github.com/vichShir/imersao-dados-desafio-final/blob/main/Imagens/banner.png) <br>
Projeto de Data Science para auxiliar no processo de descoberta de novos medicamentos com Machine Learning.

Projeto desenvolvido a partir do [Desafio Final Imersão Dados da Alura](https://github.com/alura-cursos/imersao-dados-desafio-final).

## 😵 Problema:
**Drug Discovery** é uma área interdisciplinar importante para o **descobrimento de novos fármacos** que buscam **aliviar sintomas** ou **tratamento de doenças**. Torna-se essencial, principalmente, pela atual conjuntura vivenciada pela pandemia do Coronavírus, que se tenta, justamente, buscar por esses **medicamentos**. <br>
O **Mechanism of Action (MoA)**, termo inglês para Mecanismo de Ação, de um composto pode se referir aos seus **efeitos**, assim podemos monitorar se houve a sua **ativação ou não**. Isso pode **contribuir** na ajuda na **descoberta de novos fármacos**, a partir de uma **determinada assinatura**, como **expressão gênica**, **viabilidade celular** etc.

## 🎯 Objetivos:
1. Prever se um **Mecanismo de Ação (MoA) foi** ativado.
2. Prever se um **Mecanismo de Ação (MoA) não foi** ativado.

## 📚 Conteúdo:
**1. Entendendo o Problema**<br>
**2. Coleta dos Dados**<br>
**3. Processamento e Organização dos Dados**<br>
**4. Análise Exploratória**<br>
**5. Desenvolvimento de Modelos e Algoritmos**<br>
**6. Visualização dos Dados**<br>
**7. Tomada de Decisão**<br>

## 🎲 Entendendo a estrutura dos dados:
O dataset de **experimentos** é composto, principalmente pelas informações gerais do registro, que são o id, tratamento, tempo, dose e droga, juntamente com as expressões gênicas (g-x) e as viabilidades celulares (c-x). Pequena amostra abaixo:
index| id	        | tratamento| tempo	| dose	| droga	    | g-0    | c-99
-----|--------------|-----------|-------|-------|-----------|--------|--------
0	 | id_000644bb2	| com_droga	| 24	| D1	| b68db1d53	| 1.0620 | 0.4176
1	 | id_000779bfc	| com_droga	| 72	| D1	| df89a8e5a	| 0.0743 | 0.7371
2	 | id_000a6266a	| com_droga	| 48	| D1	| 18bb41b2c	| 0.6280 | 0.6931
3	 | id_0015fd391	| com_droga	| 48	| D1	| 8c7f86626	| -0.5138| -0.8154
4	 | id_001626bd3	| com_droga	| 72	| D2	| 7cbed3131	| -0.3254| 0.7125

E o dataset de **resultados** é composto pelos Mecanismos de Ação e marcações se foram ativados ou não (1 ou 0, respectivamente). Pequena amostra abaixo:
index| id	          | 5-alpha_reductase_inhibitor	  | 11-beta-hsd1_inhibitor	  | acat_inhibitor	
-----|----------------|-------------------------------|---------------------------|----------------
0	 | id_000644bb2	  | 0	                          | 0	                      | 0	              
1	 | id_000779bfc   | 0	                          | 0	                      | 0	              
2	 | id_000a6266a   | 0	                          | 0	                      | 0	              
3	 | id_0015fd391   | 0	                          | 0	                      | 0	              
4	 | id_001626bd3   | 0	                          | 0	                      | 0	             

## 📖 Referências:
   * DESCONHECIDO. Drug discovery: passado, presente e futuro. Disponível em: https://docs.google.com/document/d/10EhrQBChlyYIcff3to7PrCQi5HcNk2r-zd2ZCKPtcz8/edit. Acesso em: 6 maio 2021.
   * DESCONHECIDO. Expressão gênica: o caminho da informação biológica. Disponível em: https://docs.google.com/document/d/1TR-Q1cb2k_-S_MZC-60PMN2CbVGZbLMKT0Lr_didPY0/edit. Acesso em: 6 maio 2021.
   * NATURE PORTFOLIO. Drug discovery. Disponível em: https://www.nature.com/subjects/drug-discovery. Acesso em: 7 maio 2021.
   * NATURE PORTFOLIO. Mechanism of action. Disponível em: https://www.nature.com/subjects/mechanism-of-action. Acesso em: 7 maio 2021.
   * WIKIPÉDIA. Expressão génica. Disponível em: https://pt.wikipedia.org/wiki/Express%C3%A3o_g%C3%A9nica. Acesso em: 7 maio 2021.
   * MAY, Olivia L.. Determining Cell Vitality​. Disponível em: https://www.caymanchem.com/news/determining-cell-vitality. Acesso em: 7 maio 2021.
