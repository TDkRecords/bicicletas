<script>
    import { page } from "$app/stores";
    import Footer from "../Components/Footer.svelte";
    import Navbar from "../Components/Navbar.svelte";

    // Definir las imágenes para cada ruta
    const bannerImages = {
        "/": "banner-home.jpg",
        "/store": "banner-store.jpg",
        "/about": "banner-about.jpg",
        "/contact": "banner-contact.jpg",
        "/login": "banner-login.jpg",
        "/register": "banner-register.jpg",
    };
</script>

<div class="container-fluid w-100 h-100 bg-primary">
    <div
        class="d-flex justify-content-center align-items-center"
        style={`height: 245px; background-size: cover; background-position: center; background-image: url('/images/${bannerImages[$page.url.pathname] || "banner-default.jpg"}');`}
    >
        <h1 class="text-white text-shadow">BICICLETAS</h1>
    </div>
</div>

<Navbar />

<slot />

<Footer />

<style>
    .text-shadow {
        text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.5);
    }
</style>
