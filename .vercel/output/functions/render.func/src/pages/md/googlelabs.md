---
title: "detail-1"
layout: "../../layouts/Layout.astro"
---

<section transition:animate="slide"  class='flex gap-7 justify-center items-center flex-wrap text-white px-8% py-20'>
   <img class='rounded-xl' src="/images/googlelabs.webp" alt="google" />
   <div class='flex flex-col gap-4'>
   <h2 class='text-transparent bg-clip-text bg-gradient-to-br from-indigo-600 from-10% via-primary via-30% to-green-600 font-semibold'>GoogleLabs</h2>
   <h4>Labs.google  es el hogar de Google para los últimos experimentos</h4>
   <p class='max-w-md'>Labs.google  es el hogar de Google para los últimos experimentos y tecnología de inteligencia artificial (IA). Es un destino que alberga los proyectos de IA audaces y responsables de Google, donde puedes ver y dar forma a las últimas herramientas y experimentos, ver las Lab Sessions más recientes y enterarte de lo que sucede en sus laboratorios.</p>
   <button class='w-20 h-7 border-gray-50 border-2 rounded-md flex justify-center items-center hover:bg-blue-900 transition'><a href="https://labs.google/" target="_blank">Ir al Sitio</a></button>
   <span><a href="/products">Regresar</a></span>
   </div>
   </div>
</section>

<style>
   section{
      width:100%;
      min-height: calc(100vh - 52px)
   }
</style>
