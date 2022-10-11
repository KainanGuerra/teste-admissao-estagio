Teste simples como dito na proposta, consegui desenvolve-lo com certa facilidade,
por conta da minha familiarida com a linhagem e as estruturas 
de repetição e decisão.
Parametros de comparação (%, ==) e conectores lógicos (||, &&) foram aplicados de imediato.
As únicas dificuldades encontradas durante o processo foram rapidamente solucionadas, 
como por exemplo, utilizar o comando continue ao inves de return/break no final de cada if ou else.

// Code Right Bellow //

function fizzBuzz(){
    for (let i = 1; i<=100; i++){

        if (i%3==0 && i%5==0){
            console.log(i + " - FizzBuzz")
            continue;
        }
        else if (i%3 == 0 ){
          console.log(i + " - Buzz")
            continue;
        }
        else if (i%5 == 0){
            console.log(i + " - Fizz")
            continue;
        }
        else{
            continue;
        }
    }
  
}
fizzBuzz();
