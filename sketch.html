let xBolinha = 300;
let yBolinha = 200;
let Diametro = 25;
let raio = Diametro / 2

//Bolinha
let velocidadeXBolinha = 6;
let velocidadeYBolinha = 6;

//Minha Raquete
let xRaquete = 2;
let yRaquete = 150;
let RaqueteComprimento = 10;
let RaqueteAltura = 90;

//Raquete oponente
let xRaqueteOponente = 587;
let yRaqueteOponente = 150;
let VelocidadeYOponente;

//outros
let colidiu = false;

//placar
let MeusPontos = 0;
let PontosOponente = 0;

//sons
let raquete;
let pontos;
let fundo;

function preload(){
  raquete = loadSound("Ping Pong Hit.wav");
  fundo = loadSound("Dance Snare Beat12.wav");
  pontos = loadSound("Collect2.wav")
}

function setup() {
  createCanvas(600, 400);
  fundo.loop();
}

function draw() {
  background("green");
mostraBolinha();
movimentaBolinha();
VerificacaoColisaoBolinha();
MostraRaquete(xRaquete, yRaquete);
MovimentoMinhaRaquete();
colisaoRaqueteBiblioteca(xRaquete, yRaquete);
MostraRaquete(xRaqueteOponente, yRaqueteOponente);
MovimentaRaqueteOponente();
colisaoRaqueteBiblioteca(xRaqueteOponente, yRaqueteOponente);
incluiPlacar();
MarcaPonto();
}

function mostraBolinha(){
  fill(255);
  circle(xBolinha, yBolinha, Diametro);
 }

function movimentaBolinha(){
  xBolinha += velocidadeXBolinha;
  yBolinha += velocidadeYBolinha;
  
 }

function VerificacaoColisaoBolinha(){
   if (xBolinha + raio > width || 
      xBolinha - raio < 0){
    velocidadeXBolinha *= -1
 }
  if (yBolinha + raio > height || 
      yBolinha - raio < 0){
    velocidadeYBolinha *= -1
 }
}

function MostraRaquete(x,y){
  fill(255);
  rect( x, y, RaqueteComprimento, RaqueteAltura);
 }

function MovimentoMinhaRaquete (){
  if (keyIsDown(87)){
    yRaquete -= 10;
  }
   if (keyIsDown(83)){
    yRaquete += 10;
    
  }
}
function verificaColisaoRaquete(){
  if (xBolinha - raio < xRaquete + RaqueteComprimento && yBolinha - raio < yRaquete + RaqueteAltura && yBolinha + raio > yRaquete){
    velocidadeXBolinha *=-1
  raquete.play()
  }
}

function colisaoRaqueteBiblioteca(x , y){
  colidiu = collideRectCircle(x, y, RaqueteComprimento, RaqueteAltura,xBolinha,yBolinha, raio);
  if (colidiu){
    velocidadeXBolinha *=-1
    raquete.play()
  }
}

function MovimentaRaqueteOponente(){
     if (keyIsDown(UP_ARROW)){
    yRaqueteOponente -= 10;
  }
   if (keyIsDown(DOWN_ARROW)){
    yRaqueteOponente += 10;}
 }

function incluiPlacar(){
  stroke(255)
  textSize(16)
  textAlign(CENTER)
  fill(color(255, 140, 0));
  rect(150, 10, 40, 20);
  fill(255);
  text(MeusPontos, 170, 26);
  fill(color(255, 140, 0));
  rect(450, 10, 40, 20);
  fill(255);
  text(PontosOponente,470, 26);
 
}

function MarcaPonto(){
  if (xBolinha > 587){
    MeusPontos += 1;
    pontos.play();
  }
  if (xBolinha < 13){
    PontosOponente += 1;
    pontos.play();
  }
}
