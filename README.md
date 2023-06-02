# projeto_IAC
Projeto de introdução à arquitetura de computadores

Assim que coisas estejam feitas, riscá-las, ~~tipo assim~~

## To Do:
- Procurar imagens, videos e efeitos sonoros
- Função que decrementa 3% de energia a cada 3 segundos
- Função que pausa o jogo
- Função que inicia o jogo
- Função que acaba o jogo
- Função que dispara a sonda para cada direção diferente
- Função que decrementa a energia por 5% a cada disparo da sonda
- Função que aumenta a energia por cada asteróide minerado (25%)
- Função que verifica o número de asteróides no ecrã (se for menor que 4 spawna outro)
- Função que spawna asteróides aleatóriamente (25% minerável e 75% não)
- Função que deteta colisões (sonda e asteróides, asteróides e nave)
- Função que muda as cores da nave (podiamos fazer a cena da bateria, mudar as cores dos botões alternadamente e cada vez que recebe energia de um asteróide minerável pisca com uma cor azul, como se tivesse a fazer "power up")
- Função que move os asteróides
- Função que muda as imagens de fundo

## Boas práticas
Vai crescendo enquanto falamos com os profs
- Funções que são accionadas com teclado têm de ser ver a tecla dentro delas
- Não desenhamos linhas do objecto que estão para lá dos limites do ecrã


## Detalhes de implementação
Vou ser maluco e vou tentar usar processos. Quero o desafio e os conceitos vao ser importante para Sistemas Operativos - Zé
### Estado do Jogo
- variável de estado que dita se estamos em pausa, ínicio ou stop no jogo. e.g. (0, 1, 2) para (inicio, jogo e pausa)

### Teclado
- guardar valor da tecla em memória
- por todas as funções à procura do valor do teclado