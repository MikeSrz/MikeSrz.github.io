<template>
<section class="mx-auto max-w-5xl px-4 py-6 sm:px-6 lg:px-8">
    <h2 class="text-2xl font-semibold text-slate-900 dark:text-slate-100">Proyectos: </h2>
    <div id="Codibalto" class="my-6">
        <h3 class="text-2xl font-medium text-slate-800 dark:text-slate-200">CodiBalto</h3>
        <h4>
            Python | FastApi | Docker | JWT | Auth | Vue | Pinia | Tailwind | Vite | MySQL | Redis | Crypto Api
        </h4>
        <div class="mt-6 flex flex-col gap-8 lg:flex-row lg:items-start">
            <div class="lg:w-2/3 space-y-6">
                <p class="text-slate-600 dark:text-slate-400">
                    Codibalto es una aplicación web que sirve de vault de contraseñas y notas seguras, con la capacidad de generar contraseñas seguras, auditarlas 
                    y cifrarlas mediante un procedimiento Zero-Knowledge utilizando la CryptoWeb Api para su almacenamiento seguro.
                    Para este proyecto, implementé la arquitectura de backend utilizando FastApi, asegurando la seguridad de los datos mediante JWT y Auth, y para gestionar el challenge de sesión, implementé un servidor Redis.
                    El Frontend fue desarrollado con Vue, Pinia y Tailwind, además de usar el lenguaje TypeScript para manejar los tipos de CryptoWeb Api de forma segura. 
                    Además, dockericé toda la aplicación para facilitar su despliegue en entornos de desarrollo y producción.
                </p>
                <a
                    href="https://github.com/MikeSrz/CODIBALTO-WEB"
                    target="_blank"
                    class="inline-flex items-center justify-center rounded-md bg-slate-800 px-4 py-2 text-sm font-semibold text-white shadow-sm transition hover:bg-slate-900 focus:outline-none focus:ring-2 focus:ring-slate-500 focus:ring-offset-2 dark:bg-slate-800 dark:hover:bg-slate-900"
                >
                    Ver en GitHub
                </a>
            </div>
            <div class="lg:w-1/3">
                <img src="@/assets/codibalto.png" alt="CodiBalto" class="w-full rounded-xl object-cover shadow-md" />
            </div>
        </div>
    </div>
    <p>

    </p>
</section>
</template>
<script>
</script>