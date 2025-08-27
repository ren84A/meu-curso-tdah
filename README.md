# meu-curso-tdah
No nosso curso "Descomplicando o TDAH", você encontrará um guia prático e acessível para entender e lidar com os desafios do TDAH no dia a dia. Chega de se sentir sobrecarregado! Nosso objetivo é fornecer as ferramentas e estratégias que realmente funcionam, de forma clara e objetiva.   .
DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descomplicando o TDAH - Cursos Acessíveis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #5a189a;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 2em 0;
        }
        .course-card {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 2em;
            text-align: center;
        }
        .price {
            font-size: 2em;
            color: #e63946;
            margin: 0.5em 0;
            font-weight: bold;
        }
        .cta-button {
            display: inline-block;
            background-color: #5a189a;
            color: #fff;
            padding: 15px 25px;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .cta-button:hover {
            background-color: #7b2cbf;
        }
    </style>
</head>
<body>

    <header>
        <h1>Descomplicando o TDAH</h1>
        <p>Aprenda a gerenciar o TDAH com nossos cursos práticos e acessíveis.</p>
    </header>

    <div class="container">
        <div class="course-card">
            <h2>Nosso curso exclusivo: **TDAH na Prática**</h2>
            <p>Descubra estratégias e ferramentas para lidar com o TDAH no dia a dia, desde a organização pessoal até técnicas de foco e produtividade.</p>
            <p class="price">Apenas R$25!</p>
            <a href="#" class="cta-button">Inscreva-se Agora</a>
        </div>
    </div>

</body>
</html>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descomplicando o TDAH - Cursos Acessíveis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #5a189a;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 2em 0;
        }
        .course-card {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 2em;
            text-align: center;
        }
        .price {
            font-size: 2em;
            color: #e63946;
            margin: 0.5em 0;
            font-weight: bold;
        }
        .cta-button {
            display: inline-block;
            background-color: #5a189a;
            color: #fff;
            padding: 15px 25px;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
            cursor: pointer;
        }
        .cta-button:hover {
            background-color: #7b2cbf;
        }
        /* Nova seção de pagamento */
        #payment-section {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 2em;
            margin-top: 2em;
            display: none; /* Inicia escondida */
            text-align: center;
        }
        #payment-section h3 {
            color: #5a189a;
        }
        #payment-section img {
            max-width: 200px;
            margin: 1em 0;
            border: 1px solid #ddd;
        }
        .copy-paste-code {
            background-color: #eee;
            padding: 10px;
            border-radius: 5px;
            word-break: break-all;
            cursor: pointer;
            margin-top: 1em;
        }
    </style>
</head>
<body>

    <header>
        <h1>Descomplicando o TDAH</h1>
        <p>Aprenda a gerenciar o TDAH com nossos cursos práticos e acessíveis.</p>
    </header>

    <div class="container">
        <div class="course-card">
            <h2>Nosso curso exclusivo: **TDAH na Prática**</h2>
            <p>Descubra estratégias e ferramentas para lidar com o TDAH no dia a dia, desde a organização pessoal até técnicas de foco e produtividade.</p>
            <p class="price">Apenas R$25!</p>
            <a id="enroll-button" class="cta-button">Inscreva-se Agora</a>
        </div>

        <div id="payment-section">
            <h3>Pague com Pix</h3>
            <p>Escaneie o QR Code abaixo ou utilize o código "Copia e Cola" para realizar o pagamento de R$25.</p>

            
            <p>Ou utilize o código "Copia e Cola":</p>
            <div id="copy-paste-code" class="copy-paste-code" title="Clique para copiar">
                <span id="pix-code-text">06029645986</span>
            </div>
            <small>Após o pagamento, o acesso ao curso será liberado em alguns minutos.</small>
        </div>
    </div>
    
    <script>
        const pixKey = "06029645986";
        const coursePrice = "25.00";

        document.getElementById('enroll-button').addEventListener('click', function() {
            document.getElementById('payment-section').style.display = 'block';
            this.style.display = 'none'; // Esconde o botão de inscrição
        });

        // Simula a geração de um código Pix Copia e Cola.
        // Em um site real, essa lógica seria mais complexa e
        // se comunicaria com uma API de pagamento.
        const pixCode = `***CHAVE PIX A SUA DIREITA ${pixKey} valor=${coursePrice}&...`;
        document.getElementById('pix-code-text').textContent = pixCode;
        
        // Adiciona funcionalidade de copiar o código ao clicar
        document.getElementById('copy-paste-code').addEventListener('click', function() {
            const textToCopy = document.getElementById('pix-code-text').textContent;
            navigator.clipboard.writeText(textToCopy).then(() => {
                alert('Código Pix copiado!');
            }).catch(err => {
                console.error('Erro ao copiar: ', err);
            });
        });
    </script>

</body>
</html>
https://cursotdahonline.com.br/