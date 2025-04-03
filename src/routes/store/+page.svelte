<script>
    let productos = [
        {
            id: 1,
            name: "Bicicleta Montaña",
            description:
                "Ideal para terrenos difíciles y aventuras al aire libre.",
            price: "$120,000",
            date: "24/03/2025",
            image: "https://thispersondoesnotexist.com/",
        },
        {
            id: 2,
            name: "Bicicleta Urbana",
            description: "Perfecta para desplazamientos diarios en la ciudad.",
            price: "$110,000",
            date: "24/04/2025",
            image: "https://thispersondoesnotexist.com/",
        },
        {
            id: 3,
            name: "Bicicleta de Ruta",
            description:
                "Diseñada para velocidad y largas distancias en carretera.",
            price: "$130,000",
            date: "24/05/2025",
            image: "https://thispersondoesnotexist.com/",
        },
    ];
</script>

<svelte:head>
    <title>Tienda | Bicicletas</title>
</svelte:head>

<main class="container">
    <h1 class="text-center my-4">
        <i class="fas fa-bicycle"></i> Nuestra Tienda
    </h1>
    <div class="row justify-content-center">
        {#each productos as producto}
            <div class="col-md-4 col-sm-6 mb-4">
                <div class="card shadow-sm border-0">
                    <img
                        src={producto.image}
                        alt={producto.name}
                        class="card-img-top"
                    />
                    <div class="card-body text-center">
                        <h5 class="card-title">{producto.name}</h5>
                        <p class="card-text">{producto.description}</p>
                        <p class="fw-bold text-success">{producto.price}</p>
                        <button class="btn btn-primary"
                            ><i class="fas fa-cart-plus"></i> Añadir al carrito</button
                        >
                    </div>
                    <div class="card-footer text-muted text-center">
                        Disponible desde: {producto.date}
                    </div>
                </div>
            </div>
        {/each}
    </div>
</main>

<style>
    .card {
        transition: transform 0.3s ease-in-out;
    }
    .card:hover {
        transform: scale(1.05);
    }
    img {
        width: 100%;
        height: 200px;
        object-fit: cover;
    }
</style>
