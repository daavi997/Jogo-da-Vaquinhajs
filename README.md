# Jogo-da-Vaquinhajs
my first game made with javascript, just a cross street game.I use p5.js web editor to made this game, later i added a colider(p5.colide2d) to improve the colision of the actor with the cars.
And to made the loop of the cars i used a function called "voltaPosicaoInicial" : 
function voltaPosicaoInicialDoCarro(){
    for(let i = 0; i < imagemCarros.length; i++){
        if(passouTodaATela(xCarros[i])){
                xCarros[i] = 600;
        }
    }
}
