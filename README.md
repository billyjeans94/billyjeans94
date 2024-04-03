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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dark Necessities</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Dark Necessities</h1>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Productos</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="banner">
            <h2>Descubre tu estilo oscuro</h2>
            <p>Explora nuestra colección de ropa gótica y alternativa</p>
            <a href="#" class="btn">Ver colección</a>
        </section>
        <section class="featured-products">
            <h2>Productos destacados</h2>
            <div class="product">
                <img src="product1.jpg" alt="Producto 1">
                <h3>Nombre del Producto</h3>
                <p>$XX.XX</p>
            </div>
            <!-- Repite este bloque para más productos destacados -->
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Dark Necessities. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

main {
    padding: 20px;
}

.banner {
    text-align: center;
    padding: 50px 0;
    background-color: #222;
    color: white;
}

.featured-products {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    grid-gap: 20px;
}

.product {
    border: 1px solid #ddd;
    padding: 10px;
    text-align: center;
}

.btn {
    display: inline-block;
    background-color: #333;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
