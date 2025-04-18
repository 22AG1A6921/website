<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tasty Bites Restaurant</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" />
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
        }

        .hero {
            background: url('https://dcassetcdn.com/design_img/500681/172298/172298_3580047_500681_image.jpg') center/cover no-repeat;
            height: 90vh;
            color: yellow;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        .hero h1 {
            font-size: 4rem;
            font-weight: bold;
            text-shadow: 2px 2px 8px #000;
        }

        .menu-item img {
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
        }

        footer {
            background-color: #222;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        .lead {
            color: black;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            font-size: 25px;
        }
    </style>
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
        <div class="container">
            <a class="navbar-brand" href="#">Tasty Bites</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#menu">Menu</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <div class="hero">
        <div>
            <h1>Welcome to </h1></br></br></br></br></br></br></br></br></br></br></br></br>
            <p class="lead">Delicious Food & Great Atmosphere</p>
        </div>
    </div>
    <section id="menu" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Our Menu</h2>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="menu-item">
                        <img src="https://img.freepik.com/premium-photo/delicious-melted-cheese-pizza-being-served_777078-98192.jpg" class="img-fluid mb-2" alt="Pizza" />
                        <h5>Cheesy Pizza</h5>
                        <p>$12 - Classic Italian style pizza with fresh toppings.</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="menu-item">
                        <img src="https://wallpaperaccess.com/full/1312729.jpg" class="img-fluid mb-2" alt="Burger" />
                        <h5>Grilled Burger</h5>
                        <p>$10 - Juicy grilled burger with secret sauce.</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="menu-item">
                        <img src="https://images4.alphacoders.com/943/943258.jpg" class="img-fluid mb-2" alt="Pasta" />
                        <h5>Italian Pasta</h5>
                        <p>$11 - Creamy Alfredo pasta with parmesan.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="about" class="bg-light py-5">
        <div class="container text-center">
            <h2>About Us</h2>
            <p class="lead">At Tasty Bites, we bring you the most authentic flavors with fresh ingredients and love. Come for the food, stay for the experience.</p>
        </div>
    </section>
    <section id="contact" class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Contact Us</h2>
            <form class="row g-3">
                <div class="col-md-6">
                    <input type="text" class="form-control" placeholder="Your Name" required />
                </div>
                <div class="col-md-6">
                    <input type="email" class="form-control" placeholder="Your Email" required />
                </div>
                <div class="col-12">
                    <textarea class="form-control" rows="4" placeholder="Your Message"></textarea>
                </div>
                <div class="col-12 text-center">
                    <button class="btn btn-primary px-5" type="submit">Send Message</button>
                </div>
            </form>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Tasty Bites. All rights reserved.</p>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
