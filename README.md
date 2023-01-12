# MODELO-MACHINE-LEARNING-DE-UM-TROCADOR-DE-CALOR-TIPO-PLACA-VIA-MODELO-GERADO-NO-ASPEN_TCC

Métodos de otimização matemática tendem a ser cada vez mais aplicados, tanto pela 
maior capacidade dos computadores, quanto pelo maior conhecimento do 
comportamento dos sistemas e consequente conhecimento das variáveis a serem 
modificadas, para obter uma resposta otimizada. Na busca de oportunidades de 
melhorias em processos químicos como prever fluxo mássica de correntes de 
refrigeração na indústria de bebidas, passou-se a empregar comumente a inteligência 
artificial e machine learning (ML) que são utilizados nessa indústria desde os anos 80, 
pois são modelos suficientemente rigorosos e rápidos para ativar os dispositivos de 
controle de forma eficaz. Logo, este trabalho tem objetivo final de construir um modelo 
matemático utilizando machine learning que calcule a vazão mássica da corrente de 
entrada de etanol (fluido de refrigeração) no trocador de calor de placas na cervejaria.
A partir de medições de temperatura, pressão e vazão das correntes reais dos 
trocadores de calor da empresa (AMBEV), desenvolveu-se um modelo em Aspen 
HYSYS®, para representar o comportamento desses trocadores. A partir de uma 
malha de entradas, utilizou-se o modelo para simular as saídas. Essas saídas foram 
utilizadas para construir um modelo empírico que representasse o processo. Três 
tipos de modelos empíricos foram utilizados para o aprendizado supervisionado: 
regressão linear, perceptron de múltiplas camadas e árvore de decisão. Para otimizar 
e avaliar os modelos, os dados foram separados em validação cruzada e teste. O
modelo árvore de decisão conseguiu prever melhor a vazão mássica da corrente 
Etanol com desvio padrão de 1,92 × 10−08 e 0 𝐾𝑔/𝑠, para os respectivos trocadores de
calor
