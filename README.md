<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width">
        <title>Contato | Barbearia Alura</title>
        <link rel="stylesheet" href="assets/css/reset.css">
        <link rel="stylesheet" href="assets/css/header.css">
        <link rel="stylesheet" href="assets/css/footer.css">
        <link rel="stylesheet" href="assets/css/contato.css">
        <link rel="stylesheet" href="assets/css/medias.css">
        <link rel="stylesheet" href="assets/css/body.css">
        <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
    </head>
    <body>
        <header>
            <a href="#conteudoPrincipal">Pular para o conteúdo principal</a>
            <div class="caixa">
                <h1><img src="assets/img/logo.png" alt="Logo da barbearia Alura"></h1>
                <nav>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="produtos.html">Produtos</a></li>
                        <li><a href="contato.html">Contato</a></li>
                    </ul>
                </nav>
            </div>
        </header>

        <main>
            <form>
                <fieldset>
                    <label for="nome-sobrenome">Nome e Sobrenome</label>
                    <input type="text" id="nome-sobrenome" class="input-padrao" required>

                    <label for="telefone">Telefone</label>
                    <input type="tel" id="telefone" class="input-padrao" placeholder="(XX) XXXXX-XXXX"required>

                    <label for="email">E-mail</label>
                    <input type="email" id="email" class="input-padrao" placeholder="seuemail@seudomínio.com" required>

                    <label for="mensagem">Mensagem</label>
                    <textarea cols="75" rows="10" id="mensagem" class="input-padrao" required></textarea>
                </fieldset>

                <fieldset>    
                    <legend>Como prefere nosso contato?</legend>
                    <label for="radio-email"><input type="radio" name="contato" value="email" id="radio-email">E-mail</label>
                    

                    <label for="radio-telefone"> <input type="radio" name="contato" value="telefone" id="radio-telefone">Telefone</label>
                

                    <label for="radio-whatsapp"><input type="radio" name="contato" value="whatsapp" id="radio-whatsapp" checked>WhatsApp</label>
                </fieldset>

                <fieldset>
                    <legend>Qual horário prefere ser atendido?</legend>
                    <select>
                        <option>Manhã</option>
                        <option>Tarde</option>
                        <option>Noite</option>
                    </select>
                </fieldset>

                <label for="checkbox"><input type="checkbox" class="checkbox" checked id="checkbox"> Gostaria de receber nossas novidades por e-mail?</label>

                <input type="submit" value="Enviar formulário" class="enviar">
            </form>

            <table>
                <thead>
                    <tr>
                        <th>Dia</th>
                        <th>Horário</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Segunda-feira</td>
                        <td>08h às 20h</td>
                    </tr>- 👋 Hi, I’m @mateus11221
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
mateus11221/mateus11221 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

                    <tr>
                        <td>Quarta-feira</td>
                        <td>08h às 20h</td>
                    </tr>
                    <tr>
                        <td>Sexta-feira</td>
                        <td>08h às 20h</td>
                    </tr>
                </tbody>
            </table>
        </main>
        <footer>
            <img src="assets/img/logo-branco.png" alt="Logo da barbearia Alura">
            <p class="Copyright">&copy;Copyright Barbearia Alura - 2021</p>
        </footer>
    </body>
</html>
