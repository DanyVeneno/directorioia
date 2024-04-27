---
title: "detail-1"
layout: "../../layouts/Layout.astro"
---

<section transition:animate="slide"  class='flex gap-7 justify-center items-center flex-wrap text-white px-8% py-20'>
   <img class='rounded-xl' src="/images/tomeai.webp" alt="google" />
   <div class='flex flex-col gap-4'>
   <h2 class='text-transparent bg-clip-text bg-gradient-to-br from-indigo-600 from-10% via-primary via-30% to-green-600 font-semibold'>Tome.app</h2>
   <h4>Tome.app es una plataforma de investigación y presentación</h4>
   <p class='max-w-md'>Tome.app es una plataforma de investigación y presentación impulsada por inteligencia artificial (IA), dirigida a equipos de ventas y marketing [!AI Presentation Maker - Tome [tome.app]]. Se anuncia como una alternativa a las presentaciones de diapositivas tradicionales.</p>
   <button class='w-20 h-7 border-gray-50 border-2 rounded-md flex justify-center items-center hover:bg-blue-900 transition'><a href="https://tome.app/" target="_blank">Ir al Sitio</a></button>
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
