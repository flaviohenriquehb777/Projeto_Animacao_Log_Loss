# Visualização da Otimização da Log Loss com Animação

Este projeto apresenta uma visualização animada do processo de otimização de uma função de **log loss**, frequentemente utilizada em modelos de classificação probabilística. A animação mostra como o parâmetro `w` é ajustado para minimizar o erro da função, destacando o comportamento da curva de perda e o ponto de mínimo ideal.

## Objetivo

Demonstrar, de forma didática e visual, o processo de otimização de uma função de custo (log loss), que é fundamental no treinamento de modelos de Machine Learning.

A visualização é útil para:
- Entender como os algoritmos ajustam seus parâmetros para reduzir o erro
- Ilustrar o comportamento de funções convexas
- Apresentar o conceito de ponto de mínimo ideal
- Criar materiais educacionais e apresentações

## Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [NumPy](https://numpy.org/) – manipulação de arrays e operações matemáticas
- [Matplotlib](https://matplotlib.org/) – geração de gráficos e animações
- [SciPy](https://scipy.org/) – otimização da função de perda (`minimize_scalar`)
- [Pillow](https://python-pillow.org/) – salvamento da animação como arquivo `.gif`

## Execução

Para rodar o código, basta ter um ambiente Python com as bibliotecas acima instaladas. Um ambiente como Jupyter Notebook ou Jupyter Lab é ideal para visualização interativa.

```bash
pip install numpy matplotlib scipy pillow
