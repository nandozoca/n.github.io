<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ogunja Pneus - Salvador, Bahia</title>
    <style>
        /* Resetando margens e padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Corpo da página */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }

        /* Cabeçalho */
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 30px;
        }

        header h1 {
            font-size: 3.5em;
        }

        header p {
            font-size: 1.2em;
            margin-top: 10px;
        }

        /* Seção Sobre */
        section#sobre {
            background-color: #fff;
            padding: 60px 20px;
            text-align: center;
            margin: 20px;
            border-radius: 8px;
        }

        section#sobre h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        section#sobre p {
            font-size: 1.2em;
            color: #666;
            line-height: 1.6;
        }

        /* Seção de Serviços */
        section#servicos {
            background-color: #e2e2e2;
            padding: 60px 20px;
            text-align: center;
        }

        section#servicos h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        section#servicos .servico {
            margin: 30px;
            padding: 25px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
            text-align: left;
            display: inline-block;
            width: 30%;
        }

        section#servicos img {
            max-width: 100%;
            border-radius: 8px;
        }

        /* Seção Produtos */
        section#produtos {
            background-color: #fff;
            padding: 60px 20px;
            text-align: center;
            margin: 20px;
            border-radius: 8px;
        }

        section#produtos h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .produto {
            display: inline-block;
            width: 30%;
            margin: 15px;
            padding: 15px;
            background-color: #f4f4f4;
            border-radius: 8px;
            text-align: center;
        }

        .produto img {
            max-width: 80%;
            border-radius: 8px;
            margin-bottom: 15px;
        }

        /* Rodapé */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        footer p {
            font-size: 1em;
        }

        footer a {
            color: #ff4500;
            text-decoration: none;
        }

        footer a:hover {
            color: #e63946;
        }

        /* Botões */
        .botao {
            background-color: #ff4500;
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.1em;
            margin-top: 20px;
        }

        .botao:hover {
            background-color: #e63946;
        }

    </style>
</head>
<body>

    <!-- Cabeçalho -->
    <header>
        <h1>Ogunja Pneus</h1>
        <p>Especializada em pneus, balanceamento e troca de óleo em Salvador - Bahia</p>
    </header>

    <!-- Seção Sobre -->
    <section id="sobre">
        <h2>Sobre a Ogunja Pneus</h2>
        <p>A **Ogunja Pneus** está localizada no coração do **Vale do Ogunjá**, em Salvador, Bahia. Com mais de **10 anos de experiência** no mercado, oferecemos uma ampla gama de serviços automotivos, incluindo **troca de pneus**, **balanceamento**, **troca de óleo** e **conserto de rodas**. Nosso objetivo é garantir a segurança e a satisfação dos nossos clientes, oferecendo sempre **produtos de qualidade** e um **atendimento personalizado**.</p>
        <p>Visite-nos e descubra porque somos a **melhor opção para o seu carro** em Salvador!</p>
    </section>

    <!-- Seção de Serviços -->
    <section id="servicos">
        <h2>Serviços Oferecidos</h2>
        <div class="servico">
            <h3>Troca de Pneus</h3>
            <img src="https://via.placeholder.com/500x300?text=Troca+de+Pneus" alt="Troca de Pneus">
            <p>Oferecemos serviços rápidos e de qualidade para a troca de pneus, com as melhores marcas e preços acessíveis.</p>
        </div>
        <div class="servico">
            <h3>Balanceamento de Pneus</h3>
            <img src="https://via.placeholder.com/500x300?text=Balanceamento+de+Pneus" alt="Balanceamento de Pneus">
            <p>Balanceamento profissional para garantir que seus pneus durem mais e seu carro tenha a melhor performance.</p>
        </div>
        <div class="servico">
            <h3>Troca de Óleo</h3>
            <img src="https://via.placeholder.com/500x300?text=Troca+de+%C3%93leo" alt="Troca de Óleo">
            <p>A troca de óleo é essencial para o bom funcionamento do motor. Realizamos esse serviço com óleos de qualidade.</p>
        </div>
    </section>

    <!-- Seção Produtos -->
    <section id="produtos">
        <h2>Produtos</h2>
        <div class="produto">
            <img src="https://via.placeholder.com/300x200?text=Pneu+Marca+X" alt="Pneu Marca X">
            <h3>Pneu Marca X</h3>
            <p>Durabilidade e segurança garantidas com a Marca X. Ideal para qualquer tipo de veículo.</p>
        </div>
        <div class="produto">
            <img src="https://via.placeholder.com/300x200?text=Pneu+Marca+Y" alt="Pneu Marca Y">
            <h3>Pneu Marca Y</h3>
            <p>Design inovador e resistência para as condições mais desafiadoras.</p>
        </div>
        <div class="produto">
            <img src="https://via.placeholder.com/300x200?text=Pneu+Marca+Z" alt="Pneu Marca Z">
            <h3>Pneu Marca Z</h3>
            <p>Excelente desempenho em estradas e cidades. Garantia de conforto e estabilidade.</p>
        </div>
    </section>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2025 Ogunja Pneus - Todos os direitos reservados. <br>
        <a href="mailto:contato@ogunjapneus.com.br">contato@ogunjapneus.com.br</a> | (71) 1234-5678</p>
        <a href="https://www.google.com/maps/place/Vale+do+Ogunj%C3%A1" class="botao" target="_blank">Como Chegar</a>
    </footer>

</body>
</html>
