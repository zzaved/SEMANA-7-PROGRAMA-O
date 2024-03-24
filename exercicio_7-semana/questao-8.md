Classe FormaGeometrica:
    Atributos:
        - cor

    Método Construtor(cor):
        Define o valor do atributo cor com o valor passado como parâmetro.

    Método CalcularArea():
        # Implementação genérica para cálculo de área, a ser sobrescrita pelas subclasses.

Classe retagulo importa FormaGeomatica:
    Atributos:
        -super cor
        -área
        -comprimento
        -altura

    Metodo calcularárea:
        -área recebe comprimento vezes altura

    Metodo Informações retangulo:
        imprima "A área do retangulo é:" + area + "e sua cor é: " + cor"

Classe circulo importa FormaGeomatica:
    Atributos:
        -super cor
        -área
        -raio

    Metodo calcularárea:
        -área recebe 3,14 * (raio * raio);

    Metodo Informações retangulo:
        imprima "A área do circulo é:" + area + "e sua cor é: " + cor"