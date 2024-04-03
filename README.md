### Hi there 👋

<!--
**billyjeans94/billyjeans94** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dark Necessities</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        header {
            background-image: url('portada.jpg');
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        nav {
            background-color: #333;
            padding: 10px 0;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 10px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        .producto {
            margin: 20px;
            padding: 10px;
            background-color: #f8f8f8;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .producto img {
            max-width: 100%;
            border-radius: 5px;
        }

        button {
            padding: 5px 10px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 3px;
            cursor: pointer;
        }

        button:hover {
            background-color: #555;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dark Necessities</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Inicio</a></li>
            <li><a href="#">Productos</a></li>
            <li><a href="#">Contacto</a></li>
        </ul>
    </nav>
    <main>
        <section class="destacados">
            <h2>Productos Destacados</h2>
            <div class="producto">
                <img src="producto1.jpg" alt="Producto 1">
                <p>Descripción del Producto 1</p>
                <button>Comprar</button>
            </div>
            <div class="producto">
                <img src="producto2.jpg" alt="Producto 2">
                <p>Descripción del Producto 2</p>
                <button>Comprar</button>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Dark Necessities. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
