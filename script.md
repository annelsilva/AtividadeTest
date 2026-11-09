// BUG DE PERFORMANCE: JavaScript travando a Main Thread (CPU Intensive)
console.log("Iniciando scripts do site...");

// Loop desnecessário que atrasa o carregamento (Low Performance Score)
function simularCargaPesada() {
    let inicio = Date.now();
    while (Date.now() - inicio < 2000) {
        // Bloqueia a thread por 2 segundos intencionalmente
    }
}

simularCargaPesada();
console.log("Script carregado com sucesso!");
