<script>
</script>

<svelte:head>
    <title>Bicicletas | Inicio</title>
</svelte:head>

<div class="container my-3 text-center">
    <h1>
        <i class="fas fa-bicycle"></i> Bienvenido a Nuestra Tienda de Bicicletas
    </h1>
    <p>
        Descubre las mejores bicicletas para todas tus aventuras, desde paseos
        urbanos hasta rutas de montaña.
    </p>

    <div class="row mt-4">
        <div class="col-md-4">
            <i class="fas fa-mountain fa-3x"></i>
            <h3>Bicicletas de Montaña</h3>
            <p>
                Explora terrenos difíciles con nuestras resistentes bicicletas
                de montaña.
            </p>
        </div>
        <div class="col-md-4">
            <i class="fas fa-road fa-3x"></i>
            <h3>Bicicletas de Ruta</h3>
            <p>Velocidad y rendimiento para los amantes del asfalto.</p>
        </div>
        <div class="col-md-4">
            <i class="fas fa-child fa-3x"></i>
            <h3>Bicicletas Infantiles</h3>
            <p>Seguras y divertidas para los más pequeños.</p>
        </div>
    </div>

    <div class="mt-5">
        <h2><i class="fas fa-users"></i> Testimonios de Clientes</h2>
        <p>Lo que dicen nuestros clientes sobre nosotros.</p>
        <blockquote>
            "¡La mejor tienda de bicicletas! Gran variedad y excelente
            servicio." – Juan P.
        </blockquote>
        <blockquote>
            "Encontré la bicicleta perfecta para mi hijo. ¡Muy recomendada!" –
            María G.
        </blockquote>
    </div>

    <div class="mt-5">
        <h2><i class="fas fa-question-circle"></i> Preguntas Frecuentes</h2>
        <div class="accordion" id="faqAccordion">
            <div class="accordion-item">
                <h2 class="accordion-header" id="faq1">
                    <button
                        class="accordion-button"
                        type="button"
                        data-bs-toggle="collapse"
                        data-bs-target="#collapse1"
                        aria-expanded="true"
                        aria-controls="collapse1"
                    >
                        ¿Ofrecen envíos a domicilio?
                    </button>
                </h2>
                <div
                    id="collapse1"
                    class="accordion-collapse collapse show"
                    aria-labelledby="faq1"
                    data-bs-parent="#faqAccordion"
                >
                    <div class="accordion-body">
                        Sí, realizamos envíos a todo el país con tiempos de
                        entrega rápidos y seguros.
                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="faq2">
                    <button
                        class="accordion-button collapsed"
                        type="button"
                        data-bs-toggle="collapse"
                        data-bs-target="#collapse2"
                        aria-expanded="false"
                        aria-controls="collapse2"
                    >
                        ¿Tienen servicio de mantenimiento?
                    </button>
                </h2>
                <div
                    id="collapse2"
                    class="accordion-collapse collapse"
                    aria-labelledby="faq2"
                    data-bs-parent="#faqAccordion"
                >
                    <div class="accordion-body">
                        Sí, ofrecemos mantenimiento preventivo y correctivo para
                        todo tipo de bicicletas.
                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="faq3">
                    <button
                        class="accordion-button collapsed"
                        type="button"
                        data-bs-toggle="collapse"
                        data-bs-target="#collapse3"
                        aria-expanded="false"
                        aria-controls="collapse3"
                    >
                        ¿Aceptan pagos con tarjeta de crédito?
                    </button>
                </h2>
                <div
                    id="collapse3"
                    class="accordion-collapse collapse"
                    aria-labelledby="faq3"
                    data-bs-parent="#faqAccordion"
                >
                    <div class="accordion-body">
                        Sí, aceptamos todas las tarjetas de crédito y débito,
                        así como pagos electrónicos.
                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="faq4">
                    <button
                        class="accordion-button collapsed"
                        type="button"
                        data-bs-toggle="collapse"
                        data-bs-target="#collapse4"
                        aria-expanded="false"
                        aria-controls="collapse4"
                    >
                        ¿Puedo probar una bicicleta antes de comprarla?
                    </button>
                </h2>
                <div
                    id="collapse4"
                    class="accordion-collapse collapse"
                    aria-labelledby="faq4"
                    data-bs-parent="#faqAccordion"
                >
                    <div class="accordion-body">
                        Sí, contamos con un área de pruebas para que puedas
                        experimentar antes de decidirte.
                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="faq5">
                    <button
                        class="accordion-button collapsed"
                        type="button"
                        data-bs-toggle="collapse"
                        data-bs-target="#collapse5"
                        aria-expanded="false"
                        aria-controls="collapse5"
                    >
                        ¿Tienen repuestos y accesorios?
                    </button>
                </h2>
                <div
                    id="collapse5"
                    class="accordion-collapse collapse"
                    aria-labelledby="faq5"
                    data-bs-parent="#faqAccordion"
                >
                    <div class="accordion-body">
                        Sí, contamos con una amplia gama de repuestos y
                        accesorios para bicicletas de todas las marcas.
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
