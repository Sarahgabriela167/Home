<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>MERCADO LIVRE</title>
     <div class="produto">

 <!-- Rodapé + Campo de Busca -->
    <div class="banner">
        <footer style="background-color: #f6f886; padding: 30px; text-align: center; margin-top: 30px;"><p>Bem-vindo ao mercado livre</p> <img src="images/Logotipo_MercadoLivre.png" alt=""></footer>
        <div class="pesquisa">
            <form action="#" method="get">
                <input type="text" name="q" placeholder="O que você está procurando?">
                <button type="submit">Buscar</button>
            </form>
        </div>
    </div>

    <!-- Categorias com Checkboxes -->
    <div class="categorias">
        <h3>Filtrar por Categoria:</h3>
        <label><input type="checkbox"> Categoria 1</label>
        <label><input type="checkbox"> Categoria 2</label>
        <label><input type="checkbox"> Categoria 3</label>
        <label><input type="checkbox"> Categoria 4</label>
        <label><input type="checkbox"> Categoria 5</label>
    </div>

    <!-- Lista de Produtos -->
    <div class="produtos">
        
<div class="produtos">
    <div class="produto">
        <img src="images/Fone de ouvido Jbl.jpg" alt="Fone JBL">
        <p>Fone JBL</p>
        <p>R$ 120,00</p>
        <p class="avaliacao">⭐ 4.4 (3749 avaliações)</p>
        <a href="#" class="botao">Comprar</a>
    </div>

    <div class="produto">
        <img src="images/fone_de_ouvido_infantil1_296_1.png" alt="Fone Infantil">
        <p>Fone Infantil</p>
        <p>R$ 230,00</p>
        <p class="avaliacao">⭐ 4.4 (3749 avaliações)</p>
        <a href="#" class="botao">Comprar</a>
    </div>

    <div class="produto">
        <img src="images/fone de ouvido disney-11134207-7qukw-lk0rxqzoncm5b9.jpg" alt="Fone Disney">
        <p>Fone Disney</p>
        <p>R$ 150,00</p>
        <p class="avaliacao">⭐ 4.4 (3749 avaliações)</p>
        <a href="#" class="botao">Comprar</a>
    </div>

    <div class="produto">
        <img src="images/fone de ouvido da minnie9dz1jKiWL._AC_UF1000,1000_QL80_.jpg" alt="Fone Minnie">
        <p>Fone Minnie</p>
        <p>R$ 170,00</p>
        <p class="avaliacao">⭐ 4.4 (3749 avaliações)</p>
        <a href="#" class="botao">Comprar</a>
    </div>
        </div>
    </div>

    <!-- Rodapé com Contatos -->
    <footer>
        <footer style="background-color: hsl(305, 28%, 83%); padding: 20px; text-align: center; margin-top: 30px;">
    <div style="display: flex; justify-content: center; gap: 30px; flex-wrap: wrap;">
        <p><strong>Telefone:</strong> <a href="tel:+5511999999999">(11) 99999-9999</a></p>
        <p><strong>Email:</strong> <a href="mailto:contato@lojinha2024.com">contato@lojinha2024.com</a></p>
        <p><a href="sobre.html">Sobre a Conta</a></p>
    </div>
    <p style="margin-top: 10px;">Todos os direitos reservados © Lojinha2024</p>
</footer>
        <p><a href="sobre.html">Saiba Mais</a></p>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }

        /* Cabeçalho com logo */
        .cabecalho {
            background-color: white;
            text-align: center;
            padding: 10px;
            box-shadow: 0px 2px 5px rgba(0,0,0,0.1);
        }
        .cabecalho img {
            max-height: 60px;
        }

        /* Menu de navegação */
        .topo {
            background-color: #FFD700;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .topo .logo {
            font-weight: bold;
            font-size: 20px;
        }
        .menu {
            display: flex;
            gap: 15px;
        }
        .menu a {
            text-decoration: none;
            color: black;
            font-weight: bold;
        }
        .menu a:hover {
            text-decoration: underline;
        }

        /* Banner + busca */
        .banner {
            background-color: #FFD700;
            padding: 20px;
            text-align: center;
        }
        .banner img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        .pesquisa input[type="text"] {
            width: 60%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .pesquisa button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        /* Categorias */
        .categorias {
            background-color: #fff;
            padding: 20px;
            margin: 20px;
            border-radius: 8px;
        }
        .categorias label {
            display: block;
            margin-bottom: 10px;
        }

        /* Produtos */
        .produtos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .produto {
            background-color: #fff;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0px 2px 5px rgba(0,0,0,0.1);
        }
        .produto img {
            max-width: 100%;
            height: auto;
        }
        .botao {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background-color: #28a745;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        
        .produtos{
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
        gap: 20px;
        padding: 20px;
        max-width: 1200px;
        margin: 0 auto;
    }
    .produto {
        background-color: #fff;
        padding: 15px;
        border-radius: 8px;
        text-align: center;
        box-shadow: 0px 2px 8px rgba(0, 0, 0, 0.1);
        transition: transform 0.2s, box-shadow 0.2s;
    }
    .produto:hover {
        transform: translateY(-5px);
        box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.2);
    }
    .produto img {
        max-width: 100%;
        height: auto;
        margin-bottom: 10px;
    }
    .produto p {
        margin: 5px 0;
    }
    .botao {
        display: inline-block;
        margin-top: 10px;
        padding: 10px 15px;
        background-color: #3483fa;
        color: white;
        text-decoration: none;
        border-radius: 5px;
    }
    .avaliacao {
        color: #fbc02d;
        font-size: 14px;
    }
        
        
        <div>
</body>
</html>
# Home
3 parte da prova
