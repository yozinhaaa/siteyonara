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
Use o código com cuidado.2. O Código CSS (style.css)html<!-- O arquivo style.css abaixo trava a tela e remove qualquer rolagem -->
Use o código com cuidado.css/* Trava a tela para impedir rolagem */
html, body {
    width: 100%;
    height: 100vh;
    margin: 0;
    padding: 0;
    overflow: hidden;
    font-family: 'Georgia', serif;
}

.capa-chocolate {
    position: relative;
    width: 100%;
    height: 100vh;
    background-image: url('https://unsplash.com'); 
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}

.filtro-escuro {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(44, 24, 16, 0.7);
    z-index: 1;
}

.conteudo-capa {
    position: relative;
    z-index: 2;
    color: #fff6eb;
    max-width: 700px;
    padding: 0 20px;
}

.tagline {
    font-size: 0.9rem;
    text-transform: uppercase;
    letter-spacing: 4px;
    color: #d4af37;
    font-weight: bold;
    display: block;
    margin-bottom: 15px;
}

.conteudo-capa h1 {
    font-size: 3.5rem;
    font-weight: bold;
    line-height: 1.2;
    margin-bottom: 15px;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.6);
}

.conteudo-capa p {
    font-family: 'Segoe UI', sans-serif;
    font-size: 1.15rem;
    margin-bottom: 25px;
    color: #e8d8c8;
}

.selo-contato {
    font-family: 'Segoe UI', sans-serif;
    display: inline-block;
    padding: 10px 24px;
    background-color: rgba(212, 175, 55, 0.15);
    border: 1px solid #d4af37;
    color: #d4af37;
    font-size: 0.95rem;
    letter-spacing: 1px;
    border-radius: 20px;
}

@media (max-width: 768px) {
    .conteudo-capa h1 {
        font-size: 2.2rem;
    }
    .conteudo-capa p {
        font-size: 0.95rem;
    }
}

