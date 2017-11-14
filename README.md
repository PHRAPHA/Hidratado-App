# Hidratado-App
Aplicativo para disciplina de Internet III do Curso de Comunicação em Mídias Digitais



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
 +
  Necessárias:
 +
 +design
 +infos em cards material design;
 +barra de progresso hidratação;
 +rostinhos triste/regular/satisfeito/feliz
 +
 +programação
 +frase que muda com o total de copos bebidos pelo usuario (voce bebeu x copos);
 +informação dos cards muda de acordo com o total de copos do usuario.
 +
  Possíveis:
  
  
  TELA 3 - João Pedro
 +
  Necessárias:
 +Ícones das conquistas;
 +Descrições das conquistas;
 +Mecanismo de contagem de copos bebidos pelo usuário;
 +Ícones de quantidade de água bebida (copo, balde, piscina, etc).
 +
 +Possíveis:
 +Uso do cache para armazenamento de dados;
 +Uso de Javascript para determinar qual sera o icone e frase apresentado para o usuario;
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
