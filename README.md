# AOSPHP
só alguns codigos para atitudinal de php



###  <?php

  ##    
    
    $pessoa = [
    
    "nome" => "Kleber",
    "idade" => 26,
    "cidade" => "Palhoca",
    "profissao" => "Youtuber/Vagabundo"//// é meme
     ];



    
    foreach ($pessoa as $atr => $value) {
    if ($atr == "nome") {
        echo "Seu nome é: $value\n";
    }
    if ($atr == "idade") {
        echo "Sua idade é: $value\n";
    }
    if ($atr == "cidade") {
        echo "Ele(a) mora na cidade De : $value\n";
    }
    if ($atr == "profissao") {
        echo "Sua profissão é: $value\nE ele é muito engracado!";
    }
    }

    ////  poderia ter utilizado   extract($pessoa); `
     /////     echo "seu nome é $nome, sua idade é $idade, ele(a) mora na cidade de $cidade sua profissao é $profissao \n  e ele e muito engracado!"  ; `


             ?>








ta me zuando jorge ????? 
/// brinks
mas serio q bagulho tonto    
        
        <?php


       function conta() { 
          for ($i = 1;$i <11; $i++){
           echo $i;
               } 
         }
     echo "os numeros de de 1 a 10:\n";
        conta()
         ?>

                                            
    



           ?>






        
     function ordem() {
    $frutas = array( "limão", "tangerina", "uva", "mamão", "maçã"
        );
    for ($i=0 ;$i<count($frutas); $i++){
    echo ($i + 1) . ". " . $frutas[$i] . "\n";
         }
     }
     ordem()
      ?>

      <?php
     function calcular() {
    $num = readline("insira um numero: ");
    //// obs : $num poderia ser só algo já predefinido , mas isso aí seria chato, tipo $num = 20; 

    if ($num>0) {
        echo "este numero e positivo";
    }
    if ($num<0) {
        echo "este numero e negativo";
    }
    if ($num==0) {
    echo "este numero nao tem valor/nulo";
    }
      }

     calcular()
      ?>
   
   `  






       <?php
     $pessoas = array(
    array(  "nome" => "João",
            "idade" => 19,
            "cidade" => "Campinas"
            ),
    array(  "nome" => "Pedro",
            "idade" => 16,
            "cidade" => "Sumaré"
            ),
    array(  "nome" => "José",
            "idade" => 18,
            "cidade" => "Ribeirão Preto"
            )
      );
     foreach ($pessoas as $pessoa) {

    if ($pessoa["idade"] >= 18) {
        $pode_dirigir = "pode";
    } else {
        $pode_dirigir = "não pode";
    }

    echo $pessoa["nome"] . " é de " . $pessoa["cidade"] . " e tem " . $pessoa["idade"] . " anos, logo, " . $pode_dirigir . " dirigir.\n";
     }

     ?>
