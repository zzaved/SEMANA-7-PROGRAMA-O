Seu objetivo é determinar em quantos minutos o carro levará para completar uma determinada distância, levando em consideração uma velocidade inicial e uma taxa de aceleração constante. No entanto, você deseja garantir que o carro não exceda uma velocidade máxima nem que a corrida demore mais do que um tempo máximo. Implemente a lógica dessa simulação em pseudocódigo.

Função calcularPercusso

    ATRIBUTOS
    velocidadeInicial; 
    velocidadeMaxima;
    velocidade = velocidadeInicial;
    aceleracao; 
    distancia;
    tempoMaximo;
    tempo = 0;
    
    Enquanto distancia > 0 && tempo <= tempoMaximo:
        velocidade = velocidade + aceleracao * tempo;
        
        Se velocidade > velocidadeMaxima:
            velocidade = velocidadeMaxima;
        
        distanciaPercorrida = velocidade * tempo;
        distancia = distancia - distanciaPercorrida;
        
        tempo =+ 1;
        
    Se tempo > tempoMaximo:
        imprimir "o tempo máximo foi excedido"
        
    Senão
        imprimir tempo