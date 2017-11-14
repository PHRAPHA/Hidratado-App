# Hidratado-App
Aplicativo para disciplina de Internet III do Curso de Comunicação em Mídias Digitais

Colocar todos os assets necessários para conclusão de sua página.
Dividir em coisas necessárias e coisas possíveis. 
No grupo de coisas necessárias colocaremos o que precisamos para terminar a tela.
No grupo de coisas possíveis colocaremos o que poderemos fazer se tivermos tempo.


------------------------------------------TELAS---------------------------------------------------------

TELA 1 - Raphael

DESIGN
Necessárias:
Tabs
  Div Copos
    Copo CSS ou Png
    Active Button para encher copos ou fazer surgir copos 
  Div Status do Personagem
    4 Rostos diferentes do Boneco (Triste[D], Semitriste[SD], SemiFeliz[SH], Feliz[H])
    4 Frases diferentes para cada estado do boneco

Possíveis:
Div Copos
  Css Animation água subindo
Div Status do Personagem
  4 Corpos diferentes para cada personagem
Botão Fab para encher os copos

PROGRAMAÇÃO
var Copos;

Atuar na Div Copos
function Copos{
  On click btnCopos {
      $("#DivCopos).recebe("divOutroCopo"); //Aparecer um novo copo para o usuário
      Copos++; // Contador de quantos copos o usuário tomou
  };
}

Atuar na Div Status do Personagem
function Status-user{
  Se (Copos == 1){
      $(div frase-user).recebe(<p>nome-user ", Você só tomou um copo, você está desidratado!"  </p>)
  }
  ... continua para 2 copos, 3 copos, 4 copos
}
  
  

TELA 2 - isabela
Necessárias:
Possíveis:



TELA 3 - João Pedro
Necessárias:
Possíveis:



LEGENDA:
D = Desidratado
SD = Semidesidratado
SH = Semihidratado
H = Hidratado

IDS/Class PADRÃO:
Botão Fab = btnFab (Class)

VARIÁVEIS PADRÃO:

var Copos (Contador de copos tomados)

---------------------------------------------TELAS EXTRAS, SE DER --------------------------------------------------------
