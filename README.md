# Projeto_Final_Lifting-Integrals-CFTD1D5
Cálculo numérico de correções de dimensões conformes em CFT

## Descrição
Este projeto investiga numericamente as integrais de correlação associadas ao levantamento (lifting) de operadores quirais de twist $\sigma_n^-$ sob a ação de modos fracionários de simetria-R $J_{-k/n}^3$ na Teoria de Campo Conforme D1-D5 (ponto de Orbifold Simétrico).

O objetivo é computar a integral $\mathcal{J}(n,k)$ que determina a correção de dimensão anômala na teoria de perturbação:
$$\Delta_\lambda = \Delta - \lambda^2 \frac{\pi}{2} \mathcal{J}(n,k)$$

## Partes 1 e 2:
- Definimos os coeficientes necessários para a computação da integral de lifting, além de realizar as devidas verificações

## Parte 3:
- A partir de uma EDP das integrais de Dotsenko-Fateev é possível reduzir derivadas de altas ordens em derivadas de ordem 0 e 1. Nessa seção definimos as funções que descrevem essa redução.

## Parte 4:
- Aqui definimos as integrais de Dotsenko-Fateev a partir das hipergeométricas de Gauss, analisando cautelosamente as possiveis divergências e expondo as regularizações.
- Sendo necessária as primeiras derivadas das integrais de DF, implementamos um algoritmo que retorna essa derivada.

## Parte 5:
- Unificamos os resultados anteriores e obtemos a solução geral da integral de correção da dimensão conforme para um dado $k$ e um range de $n$.

## Parte 6:
- Por fim, analisamos os resultados tanto quanto ao seu limite assintotico quanto a um possivel limite de validade da abordagem perturbativa.




Victor Augusto de Souza Alves
Universidade Federal de Pernambuco
Projeto Final de Metodos Computacionais em Física
