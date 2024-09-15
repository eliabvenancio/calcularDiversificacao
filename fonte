// Desafios JavaScript na DIO têm funções "gets" e "print" acessíveis globalmente:
//- "gets" : lê UMA linha com dado(s) de entrada (inputs) do usuário;
//- "print": imprime um texto de saída (output), pulando linha.

function calcularDiversificacao() {
    const portfolioStr = gets();

    // Converte a string de entrada para um array de números
    const valores = portfolioStr.split(',').map(Number);

    // Calcula o valor total do portfólio
    const valorTotal = valores.reduce((acc, valor) => acc + valor, 0);

    //Calcula a porcentagem de cada investimento em relação ao total
    const porcentagens = [];
    for(var i = 0; i < valores.length; i++) {
        porcentagens[i] = ((valores[i] / valorTotal) * 100).toFixed(2)+"%";
    
  }
   

    // Imprime o array de porcentagens
    print(porcentagens);
}

calcularDiversificacao();