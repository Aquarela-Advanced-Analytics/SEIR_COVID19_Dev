# SEIR_COVID19_Dev - Português - Brasil

## Objetivo

1. Tornar o acesso ao modelo matemático de infecção acessível aos gestores de saúde e ao público em geral da língua portuguesa. 
2. Apresentar de forma fácil e dinâmica as projeções das infecções, modos de reduzí-las e comparar com a capacidade de assistência médica nas regiões.
3. Adicionar visualizações relativas aos estados e até municípios brasileiros. 


O código que produz a interface e a funcionalidade do Shiny App está em arquivos
* **server.R**
* **ui.R**

Os arquivos usados nas seções explicativas do aplicativo são
* **SEIR.Rmd**
* **www/Parameters.nb.html**


Todas as funções que realmente executam o modelo e processam os parâmetros estão no arquivo **code/functions.R**

Se você deseja executar o código para produzir as mesmas saídas que o Shiny, mas sem lidar com a estrutura do aplicativo, é possível usar os scripts R
* **runSpread.R**
* **runInterventions.R**
* **runCapacity.R**

Ao experimentar novas estruturas ou plotagens de modelo, é muito mais fácil trabalhar com scripts, em vez de diretamente com o aplicativo. Se você estiver adicionando um novo recurso, adicione-o através do arquivo functions.R e um novo script, para que outros possam testá-lo facilmente. Depois que a solução de problemas estiver concluída, podemos descobrir como integrar-ao aplicativo. 


# Referências 
Esse projeto é baseado no trabalho do pessoal de Harvard - mais informações neste [link](https://github.com/Aquarela-Advanced-Analytics/SEIR_COVID19_Dev.git)
