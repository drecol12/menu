<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú de MINIS</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Menú de MINIS</h1>
        <p>¡Descubre el sabor máximo!</p>
    </header>
    <section class="menu">
        <div class="menu-item">
            <h2>DELITRI</h2>
            <ul>
                <li>3 DONITAS - $16k</li>
                <li>8 DONITAS - $7k</li>
                <li>6 DONITAS - $23k</li>
            </ul>
        </div>
        <div class="menu-item">
            <h2>DONICAJA</h2>
            <ul>
                <li>6 DONITAS - $16k</li>
                <li>9 DONITAS - $25k</li>
                <li>12 DONITAS - $33k</li>
            </ul>
        </div>
        <div class="menu-item">
            <h2>PERSONALIZADOS</h2>
            <p>¡Diseña tu propio dulce sueño y sumérgete en un mundo de sabores únicos que solo tú puedes crear!</p>
            <h3>GLASEADO</h3>
            <ul>
                <li>CHOCOLATE CAFÉ</li>
                <li>CHOCOLATE BLANCO</li>
            </ul>
            <h3>TOPPINGS</h3>
            <ul>
                <li>OREO</li>
                <li>M&M</li>
                <li>BARQUILLOS</li>
                <li>GRAGEA DE COLORES</li>
                <li>LLUVIA DE COLORES</li>
                <li>CHIPS DE CHOCOLATE</li>
                <li>GRAGEA PLATEADA</li>
                <li>LLUVIA DE CHOCOLATE</li>
            </ul>
        </div>
    </section>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f7f7f7;
}

header {
    background-color: #ff6347; /* Color tomate para destacar */
    color: white;
    text-align: center;
    padding: 1rem 0;
}

h1 {
    margin: 0;
    font-size: 2.5rem;
}

p {
    margin: 0;
    font-size: 1.2rem;
}

.menu {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 2rem auto;
    max-width: 1200px;
}

.menu-item {
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    margin: 1rem;
    padding: 1.5rem;
    width: 300px;
    transition: transform 0.3s, box-shadow 0.3s;
}

.menu-item:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}

h2, h3 {
    color: #333;
    font-size: 1.8rem;
    border-bottom: 2px solid #ff6347;
    padding-bottom: 0.5rem;
    margin-bottom: 1rem;
}

ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

li {
    font-size: 1.2rem;
    padding: 0.5rem 0;
    color: #555;
}

li:not(:last-child) {
    border-bottom: 1px solid #eee;
}
