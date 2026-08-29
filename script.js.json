const display = document.getElementById('display');

function adicionarAoDisplay(valor) {
    display.value += valor;
}

function limparDisplay() {
    display.value = '';
}

function calcular() {
    try {
        // eval() avalia a expressão matemática em texto
        display.value = eval(display.value);
    } catch (error) {
        display.value = 'Erro';
        setTimeout(limparDisplay, 1500);
    }
}
