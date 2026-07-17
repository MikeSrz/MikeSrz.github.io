<template>
  <section class="mx-auto max-w-5xl px-4 py-8 sm:px-6 lg:px-8">
    <div class="space-y-5 text-center">
      <h1 class="text-4xl text-white">Michael Suárez Botero</h1>
      <h3>Junior Backend Developer</h3>
      <img src="@/assets/profile.png" alt="Profile Picture" class="profile-image" />
      <p class="mt-2 text-xl text-slate-500 text-left dark:text-slate-400">
        Soy desarrollador backend con experiencia en aplicaciones profesionales como desarrollador fullstack<br>
        He implementado funcionalidades de backend para herramientas financieras, optimización de procesos y corrección de bugs, siempre buscando una mejor experiencia de usuario y mayor eficiencia.<br>
        Entre mis logros está la reducción de hasta un 90 % en tiempos de consulta y la dockerización completa de proyectos para despliegues más rápidos y seguros en entornos de desarrollo.
      </p>
    </div>
    <HomeNav/>
    <Expositor/>
    <Proyectos/>
  </section>
</template>
<script>
import HomeNav from '@/components/HomeNav.vue'
import Expositor from '@/components/Expositor.vue'
import Proyectos from '@/components/Proyectos.vue'
export default {
    name: 'Home',
    components: {
        HomeNav,
        Expositor,
        Proyectos
    }
}
</script>