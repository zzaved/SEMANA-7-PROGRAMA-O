Função MultiplicarMatrizes

    ATRIBUTOS
    matrizA
    matrizB
    
    Se tamanho(matrizA) ≠ tamanho(matrizB) então:
        Retornar "As matrizes não podem ser somadas. Elas têm dimensões diferentes."
    Senão:
    
        matrizResultado <- novaMatriz(linhasA, colunasB)
        
        Para i de 0 até linhasA-1 faça:
            Para j de 0 até colunasB-1 faça:
                soma <- 0
                Para k de 0 até colunasA-1 faça:
                    soma <- soma + matrizA[i][k] * matrizB[k][j]
                matrizResultado[i][j] <- soma
        
        Retornar matrizResultado

USO DA FUNCAO
matrizA <- [[1, 2, 3], [4, 5, 6]]
matrizB <- [[7, 8], [9, 10], [11, 12]]

matrizProduto <- MultiplicarMatrizes(matrizA, matrizB)
Escrever("Produto das matrizes:")
ImprimirMatriz(matrizProduto)

