# One Billion Row Challenge - Módulo 9 de Engenharia da Computação

## Descrição do Desafio

A última atividade ponderada do módulo 9 de Engenharia da Computação é resolver o One Billion Row Challenge. Essa tarefa consiste em escrever um programa para recuperar valores de medição de temperatura de um arquivo de texto e calcular a temperatura mínima, média e máxima por estação meteorológica. No entanto, há um desafio adicional: o arquivo possui 1.000.000.000 de linhas. O arquivo de texto tem uma estrutura simples com um valor de medição por linha, seguido pela estação meteorológica e a temperatura, separados por ponto e vírgula. O programa deve imprimir os valores mínimos, médios e máximos por estação, ordenados alfabeticamente.

## Solução em Go
A solução para este desafio foi implementada utilizando a linguagem de programação Go. O código realiza as seguintes etapas:↳

1. Abertura e leitura do arquivo: O programa abre o arquivo de texto fornecido e lê cada linha.
2. Parseamento das linhas: Cada linha é parseada para extrair a estação meteorológica e a temperatura.
3. Cálculo das estatísticas: As temperaturas são agrupadas por estação e, em seguida, são calculadas as temperaturas mínima, média e máxima para cada estação.
4. Impressão por estação em ordem alfabética: Por fim, as estatísticas são impressas por estação, ordenadas alfabeticamente.


## Registro