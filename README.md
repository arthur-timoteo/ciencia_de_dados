# Trabalho da Disciplina Ciência de dados

## Descrição
- Lemos o arquivo esea_meta_demos.part1.csv (adicionado à este repositório) indicando o separador e o tipo de codificação;
- Remover a coluna 'file' e renomeamos o nome das demais colunas;
- Removemos os registros com os timer 'Team 1', 'Team 2' e '--to be determined--' para evitar um viés errado do classificador;
- Convertemos os registros das colunas 'lado_vencedor' e 'round_tipo' para int;
- Apresentamos as informações do dataset;
- Apresentamos uma lista agrupada pelos timer com a contagem de número de round vencidos;
- Apresentamos a listagem anterior em um gráfico de pizza, mas agora com a porcentagem do número de vitórias no geral;
- Apresentamos um histograma relacionado ao time 'Team Kinguin', foi o time que mais venceu, no gráfico apresentamos a distribuição de frequência das vitórias desse time em cada mapa jogado;
- Apresentamos uma Boxplot sobre as colunas '$CounterTerrorist' e '$Terrorist';
- Convertemos os registros das colunas 'time_vencedor' e 'mapa' para int;
- Quebramos os dados em conjunto de teste e de treino;
- Criamos um classificador com o modelo de Regressão Logistica, o objetivo é classificar se o lado que vencerá o round é 'Terrorist' ou 'CounterTerrorist';
- Treinamos o classificador, verificamos seu desempenho e apresentamos seus coeficientes;

## Universidade 

Universidade Nove de Julho

## Professor

Prof. Dr. José Eduardo Storopoli

```
Storopoli (2020, March 2). Ciência de Dados com Python: pandas, matplotlib, scikit-learn e tensorflow: Ciência de Dados. Disponível em: https://storopoli.io/ciencia-de-dados
```

## Dataset

CS:GO Competitive Matchmaking Data

```
https://www.kaggle.com/skihikingkevin/csgo-matchmaking-damage/metadata
```

## Licença

Este obra está licenciado com uma Licença [Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)