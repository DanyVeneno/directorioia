---
title: "detail-1"
layout: "../../layouts/Layout.astro"
---

<section transition:animate="slide"  class='flex gap-7 justify-center items-center flex-wrap text-white px-8% py-20'>
   <img class='rounded-xl' src="/images/img8.webp" alt="camiseta" />
   <div class='flex flex-col gap-4'>
   <h2 class='text-transparent bg-clip-text bg-gradient-to-br from-indigo-600 from-10% via-primary via-30% to-green-600 font-semibold'>Google Cloud A.I.</h2>
   <h4>Herramientas de IA gratuitas de Google Cloud</h4>
   <p class='max-w-md'>Traduce contenido, analiza texto y etiqueta videos con herramientas de IA gratuitas
Ofertas gratuitas para tus casos de uso de IA más comunes, como traducción, análisis de imágenes y videos, voz a texto y mucho más.</p>
   <button class='w-20 h-7 border-gray-50 border-2 rounded-md flex justify-center items-center hover:bg-blue-900 transition'><a href="https://cloud.google.com/use-cases/free-ai-tools" target="_blank">Ir al Sitio</a></button>
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
