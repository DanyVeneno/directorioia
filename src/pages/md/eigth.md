---
title: "detail-5"
layout: "../../layouts/Layout.astro"
---

<section transition:animate="slide"  class='flex gap-7 justify-center items-center flex-wrap text-white px-8% py-20'>
   <img class='rounded-xl' src="/images/img2.webp" alt="camiseta" />
   <div class='flex flex-col gap-4'>
   <h2 class='text-transparent bg-clip-text bg-gradient-to-br from-indigo-600 from-10% via-primary via-30% to-green-600 font-semibold'>Suno A.I.</h2>
   <h4>Suno AI es una herramienta que utiliza inteligencia artificial</h4>
   <p class='max-w-md'>
Suno AI es una herramienta que utiliza inteligencia artificial para crear música [Imagen de Suno AI].  A través de un proceso que analiza grandes cantidades de datos musicales (big data), Suno AI puede generar canciones completas a partir de una descripción de texto que tú le des.  Eso significa que puedes indicarle el estilo de música (pop, rock, etc.), el sentimiento de la canción (feliz, triste, etc.), e incluso algunas palabras clave que te gustaría que incluya en la letra, y Suno AI se encargará de crear la melodía, la armonía, la letra e incluso la voz.</p>
   <button class='w-20 h-7 border-gray-50 border-2 rounded-md flex justify-center items-center hover:bg-blue-900 transition'><a href="https://suno.com/" target="_blank">Ir a Sitio</a></button>
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
