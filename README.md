<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chocolatier Premium</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- CAPA FIXA DE TELA ÚNICA -->
    <header class="capa-chocolate">
        <div class="filtro-escuro"></div>
        <div class="conteudo-capa">
            <span class="tagline">Artesanal & Premium</span>
            <h1>O Puro Sabor do Chocolate Real</h1>
            <p>Feito à mão com os melhores grãos de cacau selecionados.</p>
            <div class="selo-contato">Contato: contato@chocolatier.com</div>
        </div>
    </header>

</body>
</html>
Use o código com cuidado.



2. O Código CSS (style.css)

html

<!-- O arquivo style.css abaixo trava a tela e remove qualquer rolagem -->
Use o código com cuidado.



/* Permite rolagem normal e garante altura mínima */
html, body {
    width: 100%;
    min-height: 100vh;
    margin: 0;
    padding: 0;
    font-family: 'Georgia', serif;
}

.capa-chocolate {
    position: relative;
    width: 100%;
    min-height: 100vh; /* Usa min-height em vez de height fixo */
    /* Substituído por um link direto para uma imagem de chocolate */
    background-image: url('https://images.unsplash.com/photo-1511381939415-e44015466834?q=80&w=1600&auto=format&fit=crop'); 
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}