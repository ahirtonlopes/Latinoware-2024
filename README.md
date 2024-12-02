# Latinoware-2024

Este repositório contém materiais e exemplos práticos da palestra "No PhD Required: Rumo a IA Generativa", onde discutimos como cientistas e não-cientistas podem iniciar a criação de IAs generativas utilizando o Keras.

O objetivo da palestra foi desmistificar os conceitos por trás de modelos generativos, mostrando, através de uma demonstração prática, como os **Autoencoders Variacionais (VAEs)** podem ser utilizados para gerar novas amostras de dados semelhantes a um conjunto de dados original. 

## Estrutura do Repositório

- `Demo_Variational_Autoencoders.ipynb`: Este notebook contém o exemplo prático utilizado durante a palestra. Nele, mostramos:
  - Os fundamentos teóricos dos Autoencoders Variacionais (VAEs) e sua utilização em tarefas de geração de dados.
  - Implementação passo a passo de um VAE em Keras, com explicações sobre cada etapa do processo.
  - Visualização e análise dos resultados, incluindo a criação de novas amostras baseadas nos dados de entrada.

## Descrição da Demo

Nesta demonstração, usamos o Keras para construir e treinar um **VAE** com o objetivo de gerar dados em um espaço latente controlado. Alguns dos principais tópicos abordados incluem:

1. **Codificação Variacional**: Explicação sobre como a codificação dos dados é feita no espaço latente, permitindo que a rede aprenda representações compactas e interpretáveis.
2. **Reparametrização e Sampling**: Detalhes sobre como o VAE lida com a variância no espaço latente e amostra novas representações para a geração de dados.
3. **Reconstrução e Geração de Novas Amostras**: Como o VAE reconstrói os dados de entrada e gera novos exemplos, aproximando-se da distribuição original dos dados.

## Requisitos

Para executar o notebook, você precisará dos seguintes pacotes:
- `tensorflow`
- `keras`
- `numpy`
- `matplotlib`

## Como usar

1. Clone este repositório:

   ```bash
   git clone https://github.com/ahirtonlopes/DevFest-Triangulo.git
   cd DevFest-Triangulo
   ```
