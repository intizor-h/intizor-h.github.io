# intizor-h.github.io
Drive Easy Webpage

body
    {
        margin: 0;
        font-family: Arial, sans-serif;
        font-size: 1.2 em;
        background-color: #ebe7dc;
        display: grid;
        grid-template-rows: auto 1fr auto;
        min-height: 100vh;
    }

.main-header
    {
        font-family:  Calibri, sans-serif;
        display: grid;
        grid-template-columns: auto 1fr;
        align-items: center;
        padding: 80px 80px;
        background-color: #ebe7dc;
        border-bottom: 2px solid #ccc;
    }

.logo img
    {
        display: block;
    }

.title
    {
        text-align: left;
        font-size: 2em;
    }

.title h1
    {
        margin: 0;
    }

.page-layout
    {
        display: grid;
        grid-template-columns: 200px 4fr 250px;
        gap: 20px;
        padding: 20px;
        max-width: 1400px;
        margin: 0 auto;
        width: 100%;
        position: relative;
    }

.side-nav
    {
        text-align: center;
        display: flex;
        flex-direction: column;
        gap: 20px;
        width: 100%;
        height: 100%;
    }

.side-nav .nav-item a
    {
        font-size: 1.5em;
        text-decoration: none;
        padding: 8px;
        background-color: #ebe7dc;
        border-radius: 6px;
        text-align: center;
        color: #333;
    }

.side-nav .nav-item a:hover
    {
        background-color: #c7b897;
    }

.main-content
    {
        background: #ebe7dc;
        padding: 20px;
        border-radius: 8px;
        box-shadow: 0 0 0px rgba(0,0,0,0.0);
        width: 100%;
        box-sizing: border-box;
        grid-column: 2;

    }

.products-grid
    {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
        gap: 20px;
        margin-top: 15px;
    }

.product
    {
        text-align: center;
        background: #fffbea;
        padding: 10px;
        border-radius: 8px;
        border: 1px solid #ddd;
    }

.ad-space
    {
        width: 400px;
        height: auto;
        background: #fffdf0;
        padding: 20px;
        border-radius: 8px;
        border: 1px solid #ddd;
        position: sticky;
        top: 20px;
        box-shadow: 0 2px 5px rgb(40, 29, 11);
        grid-column: 3;
        margin-top: 0px;
}

.ad-container
    {
        text-align: center;
    }

.ad-container h3
    {
        margin-top: 0;
        color: #281d0b;
        font-size: 1.2em;
    }

.ad-container p
    {
        margin: 10px 0;
        color: #281d0b;
        font-size: 1 em;
    }

footer
    {
        grid-column: 1 / -1;
        background-color: #ded4c0;
        text-align: center;
        padding: 15px;
        border-top: 2px solid #ccc;
    }

footer p
    {
        margin: 5px 0;
    }

footer li
    {
        display: inline;
        margin: 0 10px;
    }

footer a
    {
        text-decoration: none;
        color: #000000;
    }

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="main-header">
        <div class="logo">
            <img src="DriveEasyLogo.png" alt="Drive Easy Logo" width="130" height="95">
        </div>
        <div class="title">
            <h1>Drive Easy</h1>
        </div>
    </header>
    <div class="page-layout">
        <nav class="side-nav">
            <div class="nav-item"><a href="home.html">Home</a></div>
            <div class="nav-item"><a href="about.html">About Us</a></div>
            <div class="nav-item"><a href="cart.html">Shopping Cart</a></div>
            <div class="nav-item"><a href="products.html">Products</a></div>
            <div class="nav-item"><a href="login.html">Login</a></div>
            <div class="nav-item"><a href="signup.html">Sign Up</a></div>
            <div class="nav-item"><a href="contactUs.html">Contact Us</a></div>
        </nav>
        
        <main class="main-content">
            <h2 align="center">Current Products</h2>
            <div class="products-grid">
                <div class="product">
                    <img src="SeatCover.png" alt="Luxury Faux Leather SUV Seat Cover" width="180" height="180">
                    <h3>Luxury Faux Leather SUV Seat Cover</h3>
                    <p>Price: $130.00</p>
                </div>
                <div class="product">
                    <img src="CarPhoneHolder.jpg" alt="Car Phone Holder" width="180" height="180">
                    <h3>Window Car Phone Holder</h3>
                    <p>Price: $15.00</p>
                </div>
                <div class="product">
                    <img src="CarMat.png" alt="Car Mat" width="180" height="180">
                    <h3>Luxurious Car Mat</h3>
                    <p>Price: $100.00</p>
                </div>
            </div>
        </main>
        <aside class="ad-space">
            <div class="ad-container">
                <h3>Advertisement</h3>
                <p>Your ad could be here!</p>
                <p>Contact us for advertising opportunities</p>
            </div>
        </aside>
    </div>
    <footer>
        <p>Copyright &copy; 2025 Drive Easy</p>
        <li><a href="TermsOfUse.html"> Terms of Use</a></li>
        <li><a href="PrivacyPolicy.html"> Privacy Policy</a></li>
        <li><a href="CookiesPolicy.html"> Cookies Policy</a></li>
        <li><a href="RefundPolicy.html"> Refund Policy</a></li>
    </footer>
</body>

</html>



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Drive Easy - Sign Up</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">

</head>
<body>

<header class="main-header">
    <div class="logo">
        <img src="DriveEasyLogo.png" alt="Drive Easy Logo" width="130" height="95">
    </div>
    <div class="title">
        <h1>Drive Easy</h1>
    </div>
</header>

<div class="page-layout">

    <nav class="side-nav">
        <div class="nav-item"><a href="home.html">Home</a></div>
        <div class="nav-item"><a href="about.html">About Us</a></div>
        <div class="nav-item"><a href="cart.html">Shopping Cart</a></div>
        <div class="nav-item"><a href="products.html">Products</a></div>
        <div class="nav-item"><a href="login.html">Login</a></div>
        <div class="nav-item"><a href="signup.html">Sign Up</a></div>
        <div class="nav-item"><a href="contactUs.html">Contact Us</a></div>
    </nav>


    <main class="main-content">
        <h2 class="text-center mb-4">Create an Account</h2>
        <div class="container">
            <form class="mx-auto" style="max-width: 500px;">
                <div class="mb-3">
                    <label for="username" class="form-label">Username</label>
                    <input type="text" class="form-control" id="username" placeholder="Enter your username" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email address</label>
                    <input type="email" class="form-control" id="email" placeholder="name@example.com" required>
                </div>
                <div class="mb-3">
                    <label for="password" class="form-label">Password</label>
                    <input type="password" class="form-control" id="password" placeholder="Enter password" required>
                </div>
                <div class="mb-3">
                    <label for="confirmPassword" class="form-label">Confirm Password</label>
                    <input type="password" class="form-control" id="confirmPassword" placeholder="Re-enter password" required>
                </div>
                <button type="submit" class="btn btn-primary w-100">Sign Up</button>
            </form>
        </div>
    </main>


    <aside class="ad-space">
        <div class="ad-container">
            <h3>Advertisement</h3>
            <p>Your ad could be here!</p>
        </div>
    </aside>
</div>

<footer>
    <p>Copyright &copy; 2025 Drive Easy</p>
    <li><a href="TermsOfUse.html">Terms of Use</a></li>
    <li><a href="PrivacyPolicy.html">Privacy Policy</a></li>
    <li><a href="CookiesPolicy.html">Cookies Policy</a></li>
    <li><a href="RefundPolicy.html">Refund Policy</a></li>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
