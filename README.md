# wahib-essences
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Perfume Shop</title>
</head>
<body>
    <header>
        <h1>Perfume Shop</h1>
    </header>
    
    <section class="product">
        <img src="perfume1.jpg" alt="Perfume 1">
        <h2>Floral Elegance</h2>
        <p>A captivating blend of floral notes.</p>
        <p class="price">$49.99</p>
        <button>Add to Cart</button>
    </section>

    <section class="product">
        <img src="perfume2.jpg" alt="Perfume 2">
        <h2>Mystic Woods</h2>
        <p>A mysterious fragrance with woody undertones.</p>
        <p class="price">$59.99</p>
        <button>Add to Cart</button>
    </section>

    <!-- Add more product sections as needed -->

    <footer>
        <p>&copy; 2024 Perfume Shop</p>
    </footer>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #f2f2f2;
    padding: 20px;
    text-align: center;
}

.product {
    margin: 20px;
    padding: 10px;
    border: 1px solid #ddd;
    text-align: center;
}

.product img {
    max-width: 100%;
    height: auto;
    margin-bottom: 10px;
}

.price {
    color: #007BFF;
    font-weight: bold;
}

button {
    background-color: #007BFF;
    color: #fff;
    padding: 8px 16px;
    border: none;
    cursor: pointer;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}

