# Acrecimo-Juros


function incrementarJuros(valor, percentualJuros) {
    const valorDeAcrecimo =(percentualJuros / 100) * valor;
    return valor + valorDeAcrecimo;
}

console.log(incrementarJuros(60, 10));

