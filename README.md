<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shopping Cart</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Shopping Cart</h1>
        <table>
            <thead>
                <tr>
                    <th>Product</th>
                    <th>Price</th>
                    <th>Quantity</th>
                    <th>Total</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Product 1</td>
                    <td>$10.00</td>
                    <td><input type="number" value="1" min="1"></td>
                    <td>$10.00</td>
                </tr>
                <tr>
                    <td>Product 2</td>
                    <td>$15.00</td>
                    <td><input type="number" value="1" min="1"></td>
                    <td>$15.00</td>
                </tr>
                <tr>
                    <td>Product 3</td>
                    <td>$20.00</td>
                    <td><input type="number" value="1" min="1"></td>
                    <td>$20.00</td>
                </tr>
            </tbody>
        </table>
        <div class="total">
            <h2>Total: $45.00</h2>
        </div>
        <button class="checkout">Checkout</button>
    </div>
</body>
</html>
