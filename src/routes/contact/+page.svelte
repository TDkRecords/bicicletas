<script>
</script>

<svelte:head>
    <title>Bicicletas | Contacto</title>
</svelte:head>

<main class="container py-5">
    <div class="text-center mb-4">
        <h1><i class="fas fa-envelope"></i> Contáctanos</h1>
        <p>¿Tienes preguntas? ¡Estamos aquí para ayudarte!</p>
    </div>

    <div class="row">
        <div class="col-md-6 mb-4">
            <h3><i class="fas fa-map-marker-alt"></i> Nuestra Ubicación</h3>
            <p>Av. Principal 123, Ciudad, País</p>
            <h3><i class="fas fa-phone"></i> Teléfono</h3>
            <p>+123 456 7890</p>
            <h3><i class="fas fa-envelope"></i> Correo Electrónico</h3>
            <p>info@bicitienda.com</p>
            <h3><i class="fas fa-clock"></i> Horarios</h3>
            <p>Lunes - Viernes: 9:00 AM - 6:00 PM</p>
            <p>Sábado: 10:00 AM - 2:00 PM</p>
        </div>

        <div class="col-md-6">
            <h3><i class="fas fa-comments"></i> Envíanos un mensaje</h3>
            <form>
                <div class="mb-3">
                    <label for="name" class="form-label">Nombre</label>
                    <input
                        type="text"
                        class="form-control"
                        id="name"
                        placeholder="Tu nombre"
                        required
                    />
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label"
                        >Correo Electrónico</label
                    >
                    <input
                        type="email"
                        class="form-control"
                        id="email"
                        placeholder="Tu correo"
                        required
                    />
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Mensaje</label>
                    <textarea
                        class="form-control"
                        id="message"
                        rows="4"
                        placeholder="Escribe tu mensaje"
                        required
                    ></textarea>
                </div>
                <button type="submit" class="btn btn-primary w-100"
                    >Enviar <i class="fas fa-paper-plane"></i></button
                >
            </form>
        </div>
    </div>
</main>
