# Python för AI - Inlämningsuppgift

## Projekt: Klassificering av Iris-blommor

Detta projekt tränar en enkel maskininlärningsmodell som kan förutsäga vilken art en Iris-blomma tillhör utifrån fyra numeriska mätvärden.

## Problem

Målet är att klassificera Iris-blommor som en av tre arter:

- setosa
- versicolor
- virginica

Detta är ett klassificeringsproblem.

## Dataset

Datasetet är Iris-datasetet från Scikit-learn. Det innehåller 150 observationer och fyra features:

- sepal length (cm)
- sepal width (cm)
- petal length (cm)
- petal width (cm)

## Arbetsflöde

1. Ladda in datasetet.
2. Undersök datat och kontrollera saknade värden.
3. Skapa en visualisering.
4. Dela upp datat i träningsdata och testdata.
5. Standardisera numeriska värden.
6. Träna en logistisk regressionsmodell.
7. Utvärdera modellen med accuracy, precision, recall, F1-score och confusion matrix.

## Modell

Jag använder logistisk regression eftersom det är en enkel och tydlig modell för klassificering. Modellen tränas i en pipeline tillsammans med StandardScaler.

## Resultat och reflektion

Modellen presterar bra på testdatan. Iris-datasetet är tydligt och relativt enkelt, särskilt eftersom petal length och petal width skiljer arterna åt. En begränsning är att datasetet är litet och rent jämfört med verkliga data.

Möjliga förbättringar:

- Testa fler modeller, till exempel beslutsträd eller Random Forest.
- Använda korsvalidering.
- Göra hyperparametertuning.
- Samla in mer data vid verklig användning.
