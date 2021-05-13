![Drug Discovery Image](https://ak.picdn.net/shutterstock/videos/13204946/thumb/1.jpg)

# Projeto Final da Terceira Imersão Dados da Alura
---

Olá! Neste repositório faremos a análise exploratória de dados referentes a um modelo preditivo da ação de compostos químicos em mecanismo de ativação genéticos e celulares. Abaixo irei detalhar o escopo deste projeto, falarei um pouco sobre os dados, e como pretende utilizálos.

## Os dados
---

Nesse projeto,iremos utilizar dados fornecidos em uma competição no [kaggle](https://www.kaggle.com/c/lish-moa) pelo [Laboratory innovation science de Harvard](https://lish.harvard.edu/) relativo a *drug discovery*, referente a descoberta de novos medicamentos através de mecanismos de ativação em genes e células.

## O Objetivo
---

Este projeto tem como objetivo a análise exploratória dos dados e a criação de um modelo de machine learning para classificação caso o composto tenha ativado ou não o gene/célula. 

## Como será feito
---

Inicialmente faremos a análise exploratório dos dados, sua contextualização e tratamento, de modo a entender melhor o dataset a ser trabalhado e possibilitando a análise estatística e criação do modelo de machine learning. Para o modelo de classificação com machine learning, usaremos o 'Decision Tree Classifier' e o 'Random Forest', ambos da biblioteca Scikit-learn. Em ambos casos, compararemos o resultado do modelo criado com um modelo "dummy", que é uma base comparativa que basicamente irá predizer a classificação utilizando a classe mais frequente.


## Resultados
---

Após aplicação dos modelos foram obtidos os seguintes resultados de acurácia:

*DecisionTreeClassifier               -> 62,7 %

*DummyClassifier                      -> 60,7 %

*RandomForestClassifier               -> 68.1 %

*DummyClassifier                      -> 60,7 % 

## Conclusões
---

Vemos que através de ajustes de parâmetros e de modelos somos capazes de aperfeiçoar os modelos de classificação, obtendo um resultado melhor do que o base.Porém, ainda temos uma acurácia baixa para o objetivo de exploração de novos compostos químicos, necessitanndo novos modelos estatísticos para obtermos um melhor resultado.
