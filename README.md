# Regressão Bell Geograficamente Ponderada

## O que é um Modelo de Regressão Geograficamente Ponderado (GWR)?

A **Regressão Geograficamente Ponderada (GWR)** é uma técnica de modelagem espacial que permite examinar a variação espacial nas relações entre variáveis. Ao contrário da regressão linear clássica, que assume que as relações entre as variáveis são constantes em todo o espaço, a GWR estima modelos de regressão para cada local ou região específica, levando em conta as variações geográficas. Isso torna a GWR útil para análise de dados geoespaciais, onde a estrutura espacial pode influenciar o comportamento das variáveis.

## Distribuição Bell

A **Distribuição Bell** é uma nova distribuição de probabilidade para dados de contagem, caracterizada por ser **uniparamétrica** e por acomodar o fenômeno da **superdispersão**. Superdispersão ocorre quando a variabilidade dos dados é maior do que o esperado em modelos tradicionais de contagem, como a distribuição de Poisson. A distribuição Bell é projetada para lidar com esse fenômeno, proporcionando uma modelagem mais precisa de dados que apresentam uma dispersão excessiva.

## Arquivos Disponíveis

- **GWR Bell.r**: Contém o script R utilizado para construir o modelo de **Regressão Bell Geograficamente Ponderada**. Este script implementa o código necessário para analisar os dados e gerar os resultados do modelo.
  
- **Zonas_AC_09_11_Estrat_Tatico2.xls**: Contém os dados de **acidentes** nas zonas de tráfego de Fortaleza, Ceará, utilizados para a análise da regressão geograficamente ponderada.

- **tabmicro_es_cs.xls**: Contém os dados das **frotas de caminhões** do estado do Espírito Santo, que são empregados em conjunto com os dados de acidentes para a construção do modelo de regressão.

## Como Usar

1. Certifique-se de ter o **R** instalado em sua máquina.
2. Abra o arquivo `GWR Bell.r` no RStudio ou outro editor R de sua preferência.
3. Carregue os dados de `Zonas_AC_09_11_Estrat_Tatico2.xls` e `tabmicro_es_cs.xls` no script.
4. Execute o código para construir e analisar o modelo de regressão Bell geograficamente ponderado.
5. Examine os resultados e ajuste os parâmetros conforme necessário para sua análise.
