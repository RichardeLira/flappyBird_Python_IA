 <h1 align="center">Flappy Bird com machine learning em Python</h1>
 
 ## Descrição do Projeto
<p align="center">Jogo muito famoso criado em 2014 por sua simplicidade e dificuldade. Nesse projeto foi implementado o jogo utilizado machine learning com aprendizado por reforço</p>

A ideia fundamental do projeto é utilizar uma rede neural para a máquina aprender a jogar. Para isso foi necessário recriar o jogo utilizando-se da biblioteca pygame. Após a criação do jogo, utilizei a biblioteca NEAT para integrar a rede neural ao game. Configurando a rede neural através de parâmentos em um arquivo "config" onde foi feito a definição de variações de pesos da rede, quantidade de indivíduos por geração, mutação e outros fatores. Após isso, dentro do jogo passei os parâmentos fundamentais para que a IA conseguisse aprender a jogar como altura em pixel de cima a baixo em relação ao pássaro e distância para o próximo cano. Com essas informações, utilizando-se da tecnica de aprendizado por reforço foi possível que a rede neural aprendesse a jogar o jogo em poucas gerações. 
