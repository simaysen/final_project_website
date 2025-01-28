# final_project_website
Hi-Kod Front-End Atölyesinin bitirme projesi

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Birlikte Güçlüyüz</title>
    <link rel="stylesheet" href="style.css"> 
    <script src="https://kit.fontawesome.com/2644129145.js" crossorigin="anonymous"></script>
    <!-- ✅ Bootstrap CSS (Fix) -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-md navbar-dark" style="background-color: #b12068;">
        <div class="container">
            <a href="#" class="navbar-brand">Birlikte Güçlüyüz</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                <ul class="navbar-nav d-flex flex-row gap-3">
                    <li class="nav-item">
                        <a href="#" class="nav-link btn-custom">Ana Sayfa</a>
                    </li>
                    <li class="nav-item">
                        <a href="Hakkımızda.html" class="nav-link btn-custom">Hakkımızda</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link btn-custom">Vizyonumuz</a>
                    </li>
                    <li class="nav-item">
                        <a href="#" class="nav-link btn-custom">İletişim</a>
                    </li>
                </ul>
            </div>    
        </div>
    </nav>

    <section class="hero">
        <div class="container text-center">
            <div class="icon">
                <a href="https://www.facebook.com/" target="_blank">
                   <i class="fa-brands fa-facebook fa-2x " style="color: #ff66b2"></i>
                </a>
            </div>
            <div class="icon text-center">
                <a href="https://www.instagram.com/" target="_blank">
                    <i class="fa-brands fa-instagram fa-2x" style="color:#ff66b2"></i>
                </a>
            </div>
            <div class="icon text-center">
                <a href="https://mail.google.com/" target="_blank">
                    <i class="fa-regular fa-envelope fa-2x" style="color:#ff66b2"></i>
                </a>
            </div>
            <div class="icon text-center">
                <a href="https://twitter.com/" target="_blank">
                    <i class="fa-brands fa-twitter fa-2x" style="color:#ff66b2"></i>
                </a>
            </div>
        </div>
    </section>

    <!-- ✅ Bootstrap JS (Fix: Added before closing </body>) -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
