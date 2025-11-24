# Classificacao Morfologica de Galaxias
Este projeto de Deep Learning se concentra na classificação morfológica de galáxias utilizando o dataset Galaxy10 DECaLS. O objetivo é comparar o desempenho de diferentes arquiteturas de Redes Neurais Convolucionais (CNNs) — desde modelos customizados até a aplicação de Transfer Learning com modelos pré-treinados (ResNet-50).

Escolha do Dataset:
Antes de iniciar os experimentos, é fundamental decidir qual porção dos dados será utilizada:

Dataset Completo: Utiliza o dataset Galaxy10 DECaLS inteiro, ideal para obter maior precisão, mas com maior custo computacional e tempo de treinamento.

10% do Dataset: Utiliza um subconjunto menor, adequado para testes rápidos, otimização inicial de hiperparâmetros (como visto nos experimentos com Keras Tuner) e ambientes com recursos limitados.

Essa escolha deve ser feita logo no início do notebook, na seção "# Carregamento do Dataset (Escolher entre dataset inteiro ou 10%)".
