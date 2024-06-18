# product123
designing a project
//HTML PART
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Product Cards</title>
<link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="container">
    <div class="card">
        <img src="product1.jpg" alt="Product 1">
        <div class="details">
            <h3>White traditional long dress</h3>
            <p>$3.99</p>
            <button class="buy-button">Buy</button>
            <div class="likes">8 likes</div>
        </div>
    </div>
    <!-- Repeat the card structure for other products -->
</div>
</body>
</html>
//CSS PART
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f0f0f0;
}

.card {
    width: 200px;
    background-color: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    overflow: hidden;
    margin: 10px;
}

.card img {
    width: 100%;
    height: auto;
    border-bottom: 1px solid #e0e0e0;
}

.details {
    padding: 10px;
}

h3 {
    margin: 0;
}

p {
    margin: 5px 0;
}

.buy-button {
    background-color: #007bff;
    color: #fff;
    border: none;
    padding: 5px 10px;
    border-radius: 5px;
    cursor: pointer;
}

.likes {
    color: #777;
    font-size: 12px;
}


