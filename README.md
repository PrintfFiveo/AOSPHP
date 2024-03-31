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

`  poderia ter utilizado   extract($pessoa); `
`   echo "seu nome é $nome, sua idade é $idade, ele(a) mora na cidade de $cidade sua proffisao é $profissao \n  e ele e muito engracado!"  ; `



    
    


