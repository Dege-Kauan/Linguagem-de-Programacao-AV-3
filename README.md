# Projeto: Formas Geométricas em Python

## Vídeo de Apresentação

Confira a apresentação do projeto no YouTube:
[Apresentação do Projeto](https://youtu.be/b8bXdNf64F8)

## Descrição

Este projeto foi desenvolvido como parte da avaliação do curso, com o objetivo de aplicar conceitos de **Programação Orientada a Objetos (POO)**. O projeto implementa um sistema para calcular a área e o perímetro de formas geométricas, como retângulos e circunferências, utilizando classes, métodos, atributos, herança, polimorfismo e encapsulamento.

## Estrutura do Projeto

O projeto está organizado da seguinte maneira:

- **`formaGeometrica.py`**: Este arquivo contém a classe abstrata `FormaGeometrica`, que define a estrutura comum para as classes que representam formas geométricas. A classe define três métodos abstratos: `calcularArea`, `calcularPerimetro` e `exibirDados`, que são implementados nas subclasses.
  
- **`retangulo.py`**: Contém a implementação da classe `Retangulo`, que herda de `FormaGeometrica`. Nesta classe, são definidos os atributos privados `lado1` e `lado2`, além dos métodos específicos para calcular a área e o perímetro de um retângulo.

- **`circunferencia.py`**: Contém a implementação da classe `Circunferencia`, que também herda de `FormaGeometrica`. Nesta classe, o atributo privado `raio` é usado para calcular a área e o perímetro de uma circunferência.

- **`main.py`**: Este arquivo é responsável por criar os objetos das classes `Retangulo` e `Circunferencia`, e exibir os resultados no terminal, utilizando o método `exibirDados`.

## Conceitos de POO Aplicados

- **Classes**: O projeto contém diversas classes, incluindo uma classe abstrata (`FormaGeometrica`) e classes concretas (`Retangulo` e `Circunferencia`).
- **Atributos**: Cada classe possui seus atributos específicos, como `lado1`, `lado2`, e `raio`, que são definidos como atributos privados com a convenção de dois underscores (`__`).
- **Métodos**: Foram implementados métodos para calcular a área, perímetro e exibir os dados de cada forma geométrica.
- **Encapsulamento**: O projeto utiliza atributos privados e o decorador `@property` para controlar o acesso a esses atributos.
- **Herança**: As classes `Retangulo` e `Circunferencia` herdam da classe `FormaGeometrica`, aproveitando os métodos abstratos definidos nela.
- **Polimorfismo**: As classes `Retangulo` e `Circunferencia` implementam os mesmos métodos abstratos de formas diferentes, demonstrando o conceito de polimorfismo.
