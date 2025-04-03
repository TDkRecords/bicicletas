<script>
    import "$lib/app.css";
</script>

<nav class="navbar navbar-expand-lg bg-primary sticky-top">
    <div class="container-fluid">
        <a class="navbar-brand text-light fw-bold" href="/">BICICLETAS</a>
        <button
            class="navbar-toggler bg-light"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
        >
            <span class="navbar-toggler-icon"></span>
        </button>
        <div
            class="collapse navbar-collapse justify-content-end align-items-center"
            id="navbarNav"
        >
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link text-light" aria-current="page" href="/">
                        INICIO
                        <i class="fa-solid fa-house"></i>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-light" href="/store">
                        PRODUCTOS
                        <i class="fa-solid fa-bag-shopping"></i>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-light" href="/about">
                        ACERCA DE
                        <i class="fa-solid fa-circle-info"></i>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-light" href="/contact">
                        CONTACTO
                        <i class="fa-solid fa-user-tie"></i>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-light" href="/login">
                        INGRESAR
                        <i class="fa-solid fa-right-to-bracket"></i>
                    </a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<style>
    .navbar {
        background-color: #004080 !important; /* Azul oscuro principal */
    }
    .navbar-nav .nav-link {
        transition: color 0.3s ease-in-out;
    }
    .navbar-nav .nav-link:hover {
        color: #ffd700 !important; /* Amarillo dorado al pasar el cursor */
    }
</style>
