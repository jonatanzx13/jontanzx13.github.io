<html><head><base href="https://fotospromax.com/">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Fotos Pro Max - Inicio</title>
<style>
    body, html {
        margin: 0;
        padding: 0;
        font-family: 'Roboto', sans-serif;
        background-color: #f0f2f5;
        color: #333;
    }
    .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
    }
    header {
        background-color: #1a237e;
        color: white;
        padding: 1em;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .logo {
        font-size: 1.8em;
        font-weight: bold;
        font-family: 'Montserrat', sans-serif;
        letter-spacing: 1px;
    }
    nav ul {
        list-style-type: none;
        padding: 0;
        display: flex;
    }
    nav ul li {
        margin-left: 20px;
    }
    nav ul li a {
        color: white;
        text-decoration: none;
        font-weight: bold;
        transition: color 0.3s ease;
    }
    nav ul li a:hover {
        color: #ffab40;
    }
    .hero {
        background-image: url('https://picsum.photos/1200/400');
        background-size: cover;
        background-position: center;
        height: 400px;
        display: flex;
        align-items: center;
        justify-content: center;
        text-align: center;
        color: white;
        text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    }
    .hero-content h1 {
        font-size: 3em;
        margin-bottom: 20px;
    }
    .hero-content p {
        font-size: 1.2em;
        margin-bottom: 30px;
    }
    .cta-button {
        background-color: #4CAF50;
        color: white;
        padding: 10px 20px;
        text-decoration: none;
        border-radius: 5px;
        font-weight: bold;
        transition: background-color 0.3s ease;
    }
    .cta-button:hover {
        background-color: #45a049;
    }
    .features {
        display: flex;
        justify-content: space-between;
        margin-top: 50px;
    }
    .feature {
        flex-basis: 30%;
        background-color: white;
        padding: 20px;
        border-radius: 8px;
        box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        text-align: center;
    }
    .feature i {
        font-size: 3em;
        color: #1a237e;
        margin-bottom: 20px;
    }
    .gallery {
        margin-top: 50px;
    }
    .gallery h2 {
        text-align: center;
        margin-bottom: 30px;
    }
    .photo-grid {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
        gap: 20px;
    }
    .photo-item {
        position: relative;
        overflow: hidden;
        border-radius: 8px;
        box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        transition: transform 0.3s ease;
    }
    .photo-item:hover {
        transform: scale(1.05);
    }
    .photo-item img {
        width: 100%;
        height: 250px;
        object-fit: cover;
    }
    .photo-overlay {
        position: absolute;
        bottom: 0;
        left: 0;
        right: 0;
        background-color: rgba(0,0,0,0.7);
        color: white;
        padding: 10px;
        transform: translateY(100%);
        transition: transform 0.3s ease;
    }
    .photo-item:hover .photo-overlay {
        transform: translateY(0);
    }
    footer {
        background-color: #1a237e;
        color: white;
        text-align: center;
        padding: 20px 0;
        margin-top: 50px;
    }
    @media (max-width: 768px) {
        .features {
            flex-direction: column;
        }
        .feature {
            margin-bottom: 20px;
        }
    }
</style>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>
<body>
    <header>
        <div class="logo">Fotos Pro Max</div>
        <nav>
            <ul>
                <li><a href="/">Inicio</a></li>
                <li><a href="/buscar">Buscar</a></li>
                <li><a href="/albums">Álbumes</a></li>
                <li><a href="/perfil">Mi Perfil</a></li>
            </ul>
        </nav>
    </header>

    <div class="hero">
        <div class="hero-content">
            <h1>Captura, Comparte, Inspira</h1>
            <p>Descubre un mundo de fotografía y creatividad en Fotos Pro Max</p>
            <a href="/registro" class="cta-button">Únete Ahora</a>
        </div>
    </div>

    <div class="container">
        <section class="features">
            <div class="feature">
                <i class="fas fa-camera"></i>
                <h3>Sube tus Fotos</h3>
                <p>Comparte tus mejores momentos con nuestra comunidad de fotógrafos.</p>
            </div>
            <div class="feature">
                <i class="fas fa-users"></i>
                <h3>Conéctate</h3>
                <p>Encuentra inspiración y conecta con otros apasionados de la fotografía.</p>
            </div>
            <div class="feature">
                <i class="fas fa-magic"></i>
                <h3>Edita y Mejora</h3>
                <p>Utiliza nuestras herramientas de edición para llevar tus fotos al siguiente nivel.</p>
            </div>
        </section>

        <section class="gallery">
            <h2>Fotos Destacadas</h2>
            <div class="photo-grid">
                <div class="photo-item">
                    <img src="https://picsum.photos/400/300?random=1" alt="Paisaje montañoso">
                    <div class="photo-overlay">
                        <p>Montañas al Atardecer</p>
                    </div>
                </div>
                <div class="photo-item">
                    <img src="https://picsum.photos/400/300?random=2" alt="Retrato urbano">
                    <div class="photo-overlay">
                        <p>Vida en la Ciudad</p>
                    </div>
                </div>
                <div class="photo-item">
                    <img src="https://picsum.photos/400/300?random=3" alt="Naturaleza salvaje">
                    <div class="photo-overlay">
                        <p>Fauna Salvaje</p>
                    </div>
                </div>
                <div class="photo-item">
                    <img src="https://picsum.photos/400/300?random=4" alt="Arquitectura moderna">
                    <div class="photo-overlay">
                        <p>Líneas Modernas</p>
                    </div>
                </div>
                <div class="photo-item">
                    <img src="https://picsum.photos/400/300?random=5" alt="Macro fotografía">
                    <div class="photo-overlay">
                        <p>Detalles Ocultos</p>
                    </div>
                </div>
                <div class="photo-item">
                    <img src="https://picsum.photos/400/300?random=6" alt="Playa tropical">
                    <div class="photo-overlay">
                        <p>Paraíso Tropical</p>
                    </div>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2023 Fotos Pro Max. Todos los derechos reservados.</p>
    </footer>

    <script>
        // Lazy loading for images
        document.addEventListener("DOMContentLoaded", function() {
            var lazyImages = [].slice.call(document.querySelectorAll("img.lazy"));

            if ("IntersectionObserver" in window) {
                let lazyImageObserver = new IntersectionObserver(function(entries, observer) {
                    entries.forEach(function(entry) {
                        if (entry.isIntersecting) {
                            let lazyImage = entry.target;
                            lazyImage.src = lazyImage.dataset.src;
                            lazyImage.classList.remove("lazy");
                            lazyImageObserver.unobserve(lazyImage);
                        }
                    });
                });

                lazyImages.forEach(function(lazyImage) {
                    lazyImageObserver.observe(lazyImage);
                });
            }
        });

        // Simple animation for features
        const features = document.querySelectorAll('.feature');
        features.forEach((feature, index) => {
            setTimeout(() => {
                feature.style.opacity = '0';
                feature.style.transform = 'translateY(20px)';
                feature.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
                setTimeout(() => {
                    feature.style.opacity = '1';
                    feature.style.transform = 'translateY(0)';
                }, 100 * index);
            }, 500);
        });
    </script>
</body>
</html>
