inteiro idade, i,  maioridade=0, menoridade=0
    para (i=1; i<=5; i++){

    escreva("Digite a idade do jogador: ")
    leia(idade)

    se (i==1){
      maioridade=idade
      menoridade=idade
    }
    
    senao{
        se(idade>maioridade){
      maioridade=idade
      
      }
    se (idade<menoridade){
      menoridade=idade
      
    }
    }
    
  }
 escreva("jogador mais velho", maioridade,  "jogador mais novo", menoridade)
