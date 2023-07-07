<script >
import imgen from '../assets/img/majestuosa-arquitectura-famosa-catedral-paris-generada-ia.jpg'
export default {
  data() {
    return {
      article: [
        {
          id: 1,
          title: 'Introducción ',
          description: 'Bienvenido a nuestra página dedicada a explorar y comprender las estructuras, donde encontrará información detallada sobre una amplia variedad de estructuras, desde edificios y puentes hasta antenas y torres de comunicación. Veremos cómo estas estructuras se diseñan y construyen de tal manera que puedan soportar cargas, resistir fuerzas externas y cumplir su propósito funcional. También aprenderás por qué es tan importante entender cómo funcionan estas estructuras y cómo tus conocimientos pueden tener un impacto significativo en las diferentes áreas o la importancia de saber cómo funcionan las estructuras físicas. Comprender cómo funcionan las estructuras físicas es vital por varias razones. ',
          image: imgen,
        },
        {
          id: 2,
          title: 'Puntos Clave',
          description: 'La seguridad: las estructuras son elementos fundamentales de nuestra vida diaria: desde los edificios en los que vivimos y trabajamos hasta los puentes que cruzamos, es importante que estas estructuras sean seguras y estables. Conocer su funcionamiento nos permite evaluar y predecir su rendimiento en diferentes situaciones, como terremotos, vientos fuertes o cargas inesperadas, lo que nos ayuda a garantizar la seguridad de las personas que las utilizan. Un diseño eficiente. Comprender las estructuras también es importante para diseñar nuevos proyectos de manera eficiente y rentable. Saber cómo funcionan nos permite optimizar el uso de materiales, reducir los costos de construcción y minimizar el impacto ambiental.',
          image: '/images/stock/photo-1494232410401-ad00d5433cfa.jpg',
          video: 'https://www.youtube.com/embed/P2rhnfLlWIU?controls=0',
        }
      ]
    }
  },

  methods: {

  },


}
</script>
<template>
  <div class="card lg:card-side bg-base-200 shadow-xl h-auto m-10 border border-bg-primarys" v-for="item in article" :key="item.id">
    <div class="card-body ">
      <h2 class="card-title mx-auto">{{ item.title }}</h2>
      <div class=" flex flex-row flex-wrap w-auto h-auto">
        <p class="flex flex-wrap  h-auto">{{ item.description }}</p>
        <div v-if="item.video" class="mx-auto w-1/2">
          <figure class="px-10 pt-10 mx-auto w-full">
            <div class="w-1/1 h-auto">
              <iframe :src="item.video" title="YouTube video player" frameborder="0" width="100%" height="300px"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                allowfullscreen></iframe>
            </div>
          </figure>
        </div>
        <div v-else class="mx-auto">
          <figure class="px-10 pt-10 mx-auto w-1/2"><img :src="item.image" alt="Album"  width="70%" height="100%"/></figure>
        </div>
      </div>
    </div>
  </div>

 
</template>