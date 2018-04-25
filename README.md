# SOLUÇÃO: Record Linkage Comparison Patterns Data Set 

O problema que é abordado neste repositorio é [este](https://googleweblight.com/i?u=https://archive.ics.uci.edu/ml/datasets/record%2Blinkage%2Bcomparison%2Bpatterns&hl=pt-BR).

## Soluções existentes  
Uma das soluções existentes para esse problema esta presente no artigo [Murat Sariyar, Andreas Borg, Klaus Pommerening: Controlling false
match rates in record linkage using extreme value theory. Journal of Biomedical Informatics, 2011 (in press).](https://core.ac.uk/download/pdf/82391569.pdf)  

O problema foi solucionado de 3 formas diferentes:

* **Decision Tree**

* **KNN**

* **Neural Network**

Cada uma das soluções possuem seus próprios contextos, dependências e 
nootebooks. É possível verificá-las em em suas pastas.
>>>>>>> 34acd1f83b331524fbd4611600d7a3b748df3597

## Dados

Os dados do problema estão [aqui](https://googleweblight.com/i?u=https://archive.ics.uci.edu/ml/datasets/record%2Blinkage%2Bcomparison%2Bpatterns&hl=pt-BR).

Baixe o *data set* e coloque seu conteúdo na pasta:

`data`

Extraia todos os dados para esta pasta.

* Todos os arquivos `.csv` são ignorados no `.gitignore` pois o *dataset* 
contém mais de 200MB de tamanho.

## Ambiente

Para verificar a solução siga este [tutorial](https://github.com/SkyNetRecruits/Documentacao/blob/master/documentacaoSolucao/ambiente.md) para instalar seu virtualenv de python.

Após ter seu ambiente de desenvolvimento configurado execute o seguinte comando:

`pip install -r requirements.txt`

## Documentação

A documentação e interpretação do problema está [aqui](https://github.com/SkyNetRecruits/Documentacao).

## Referências

### Decision Tree

### KNN

### Neural Network
A principal referência para a solução do problema foi a documentação do [scikit-learn](http://scikit-learn.org/stable/modules/neural_networks_supervised.html)

Os seguintes links também foram úteis:

* [wildml](http://www.wildml.com/2015/09/implementing-a-neural-network-from-scratch/)

* [Tips on Practical Use](http://scikit-learn.org/stable/modules/neural_networks_supervised.html#mlp-tips)

* [Beginner's Guide](https://www.springboard.com/blog/beginners-guide-neural-network-in-python-scikit-learn-0-18/)

* [train_test_split](http://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html)
