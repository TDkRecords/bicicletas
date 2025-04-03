<script>
    let isLogin = true;
</script>

<svelte:head>
    <title>Bicicletas | {isLogin ? "Login" : "Registro"}</title>
</svelte:head>

<main class="container d-flex justify-content-center align-items-center vh-100">
    <div class="card p-4 shadow" style="max-width: 400px; width: 100%;">
        <h2 class="text-center mb-3">
            <i class="fas fa-bicycle"></i>
            {isLogin ? "Iniciar Sesión" : "Registro"}
        </h2>
        <form>
            {#if !isLogin}
                <div class="mb-3">
                    <label for="name" class="form-label">Nombre</label>
                    <input
                        type="text"
                        id="name"
                        class="form-control"
                        placeholder="Tu nombre"
                        required
                    />
                </div>
            {/if}
            <div class="mb-3">
                <label for="email" class="form-label">Correo Electrónico</label>
                <input
                    type="email"
                    id="email"
                    class="form-control"
                    placeholder="correo@ejemplo.com"
                    required
                />
            </div>
            <div class="mb-3">
                <label for="password" class="form-label">Contraseña</label>
                <input
                    type="password"
                    id="password"
                    class="form-control"
                    placeholder="Tu contraseña"
                    required
                />
            </div>
            <button type="submit" class="btn btn-primary w-100">
                {isLogin ? "Iniciar Sesión" : "Registrarse"}
            </button>
        </form>
        <div class="text-center mt-3">
            <a href="/" on:click|preventDefault={() => (isLogin = !isLogin)}>
                {isLogin
                    ? "¿No tienes cuenta? Regístrate"
                    : "¿Ya tienes cuenta? Inicia sesión"}
            </a>
        </div>
    </div>
</main>
