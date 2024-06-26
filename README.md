<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rev Rims</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            color: white;
            display: flex;
            justify-content: center;
            padding: 1rem 0;
        }
        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 2rem;
            display: none;
        }
        .container.active {
            display: block;
        }
        .product, .cart-item {
            border: 1px solid #ccc;
            margin: 1rem;
            padding: 1rem;
            text-align: center;
        }
        .product img, .cart-item img {
            max-width: 100%;
            height: auto;
        }
        .product h2, .cart-item h2 {
            font-size: 1.5rem;
        }
        .product p, .cart-item p {
            margin: 1rem 0;
        }
        .add-to-cart, .remove-from-cart, .checkout {
            background-color: #28a745;
            border: none;
            color: white;
            cursor: pointer;
            padding: 0.5rem 1rem;
        }
        .add-to-cart:hover, .remove-from-cart:hover, .checkout:hover {
            background-color: #218838;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 1rem 0;
            text-align: center;
            margin-top: 2rem;
        }
        .homepage-image {
            display: block;
            margin: 2rem auto;
            max-width: 100%;
            height: auto;
        }
        .billing-form {
            display: none;
            margin-top: 2rem;
        }
        .billing-form.active {
            display: block;
        }
        .billing-form input, .billing-form textarea {
            display: block;
            width: 100%;
            margin: 0.5rem 0;
            padding: 0.5rem;
		.product {
             border: 1px solid #ccc;
             margin: 1rem;
             padding: 1rem;
             text-align: center;
             width: 300px; 
             display: inline-block; 
             vertical-align: top; 
        }

        .product img {
             max-width: 100%;
             height: auto;
             max-height: 200px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Rev Rims</h1>
    </header>
    <nav>
        <a href="#" onclick="showPage('home')">Home</a>
        <a href="#" onclick="showPage('products')">Products</a>
        <a href="#" onclick="showPage('cart')">Cart</a>
        <a href="#" onclick="showPage('checkout')">Checkout</a>
    </nav>
    <div id="home" class="container active">
        <h2>Welcome to Rev Rims: Where Every Revolution Begins!</h2>
        <p>At Rev Rims, we're not just about wheels; we're about igniting your passion for the road, one revolution at a time. 
		Step into our world where speed, style, and precision craftsmanship collide to elevate your driving experience to new heights.</p>
        <img src="HomepageJerome.jpg" class="homepage-image">
    </div>
    <div id="products" class="container">
        <h2>Products</h2>
        <div class="product">
            <img src="EVO II.jpg">
            <h2>Desmond RegaMaster EVO II</h2>
			<p>The Desmond RegaMaster EVO II wheels, are an ultra-lightweight forged wheel that is familiar to circuits. This is a classic aluminum wheel that is loved not only in Japan but now by users all over the world.</p>
            <p>Price: ₱80000</p>
            <button class="add-to-cart" data-name="Desmond RegaMaster EVO II" data-price="80000">Add to Cart</button>
        </div>
        <div class="product">
            <img src="ce28.jpg">
            <h2>Rays Volk Racing CE28 </h2>
			<p>The CE28SL is a premium high-performance wheel boasting a stylish design. This wheel is ideal for sports car enthusiasts who want to upgrade their vehicles.</p>
            <p>Price: ₱67000</p>
            <button class="add-to-cart" data-name="Rays Volk Racing CE28 " data-price="67000">Add to Cart</button>
        </div>
        <div class="product">
            <img src="rpf1.jpg">
            <h2>Enkei RPF1</h2>
			<p>The twin spokes on the Enkei RPF1 achieve better stress dispersion on curves, hard braking, and extreme race driving. 
			CENTER DESIGN: Enkei’s pocket design around the bolt circles increases rigidity and keeps the wheel cooler during aggressive race driving. MAT PROCESS: Shaping by the MAT process reduces wheel weight by 10%-15%.</p>
            <p>Price: ₱74000</p>
            <button class="add-to-cart" data-name="Enkei RPF1" data-price="74000">Add to Cart</button>
        </div>
        <div class="product">
            <img src="mf10.jpg">
            <h2>Mugen MF10</h2>
			<p>The classic competition-grade Mugen wheel "MF", the return MF10 wheels combines the visual experience with the design style of the MUGEN body to meet the high-intensity requirements of track competition. 
			The return of Mugen MF10 for the Civic Type R FK8! The price listed is for a set of 4 wheels. Limited Quantity. DREAM IT. BUILD IT. RACE IT.</p>
            <p>Price: ₱157000</p>
            <button class="add-to-cart" data-name="Mugen MF10" data-price="40">157000</button>
        </div>
        <div class="product">
            <img src="te37.jpg">
            <h2>Rays Volk Racing TE37</h2>
			<<p>The TE37 is a groundbreaking product that sets the standard for what a performance wheel should be. It is Rays' first one-piece forged aluminum wheel, launched under its flagship Volk Racing line.</p>
            <p>Price: ₱120000</p>
            <button class="add-to-cart" data-name="Rays Volk Racing TE37" data-price="120000">Add to Cart</button>
        </div>
        <div class="product">
            <img src="ns2.jpg">
            <h2>Sparco NS2</h2>
			<p>The Racing Sparco NS-II Viper were one of the most popular JDM Wheels in the late 90’s. The Racing Sparco NS-II Viper feature 2 piece welded construction, and a very popular mesh design. 
			The Racing Sparco NS-II Viper were produced by Crimson Inc but manufactured by Enkei Wheels in Japan. </p>
            <p>Price: ₱143000</p>
            <button class="add-to-cart" data-name="Sparco NS2" data-price="143000">Add to Cart</button>
        </div>
    </div>
    <div id="cart" class="container">
        <h2>Shopping Cart</h2>
        <ul id="cart-items" style="list-style: none; padding: 0;">
        </ul>
        <p>Total: $<span id="cart-total">0</span></p>
        <button class="checkout" onclick="showPage('checkout')">Proceed to Checkout</button>
    </div>
    <div id="checkout" class="container">
        <h2>Checkout</h2>
        <form class="billing-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="address">Address:</label>
            <textarea id="address" name="address" required></textarea>
            <p>Total: $<span id="checkout-total">0</span></p>
            <button class="checkout" onclick="completePurchase()">Complete Purchase</button>
        </form>
    </div>
    <footer>
        <p>&copy; 2024 Rev Rims</p>
    </footer>
    <script>
        const pages = {
            home: document.getElementById('home'),
            products: document.getElementById('products'),
            cart: document.getElementById('cart'),
            checkout: document.getElementById('checkout')
        };

        function showPage(page) {
    for (let key in pages) {
        pages[key].classList.remove('active');
    }
    pages[page].classList.add('active');
}

    function calculateCheckoutTotal() {
    const checkedOutItems = document.querySelectorAll('.cart-item');
    let checkoutTotalAmount = 0;
    checkedOutItems.forEach(item => {
        const price = parseFloat(item.querySelector('p').textContent.split('$')[1]);
        checkoutTotalAmount += price;
    });
    return checkoutTotalAmount.toFixed(2);
}

    document.addEventListener('DOMContentLoaded', () => {
      const cartItems = document.getElementById('cart-items');
      const cartTotal = document.getElementById('cart-total');
      const checkoutTotal = document.getElementById('checkout-total');
      let total = 0;

    document.querySelectorAll('.add-to-cart').forEach(button => {
        button.addEventListener('click', () => {
            const name = button.getAttribute('data-name');
            const price = parseFloat(button.getAttribute('data-price'));

            const listItem = document.createElement('li');
            listItem.className = 'cart-item';
            listItem.innerHTML = `<h2>${name}</h2><p>Price: $${price}</p><button class="remove-from-cart" data-price="${price}">Remove</button>`;
            cartItems.appendChild(listItem);

            total += price;
            cartTotal.textContent = total.toFixed(2);
            checkoutTotal.textContent = total.toFixed(2);

            listItem.querySelector('.remove-from-cart').addEventListener('click', () => {
                cartItems.removeChild(listItem);
                total -= price;
                cartTotal.textContent = total.toFixed(2);
                checkoutTotal.textContent = total.toFixed(2);
            });
        });
    });

    document.querySelector('.billing-form').addEventListener('submit', (e) => {
        e.preventDefault();
        const checkoutTotalAmount = calculateCheckoutTotal();
        alert(`Order placed successfully! This page says the total is: $${checkoutTotalAmount}`);
        cartItems.innerHTML = '';
        cartTotal.textContent = '0';
        checkoutTotal.textContent = '0';
        showPage('home');
    });

    // Function to handle completion of purchase
    function completePurchase() {
        alert('Purchase Complete!');
        // Additional actions you may want to perform after purchase completion
    }
});

</body>
</html>
