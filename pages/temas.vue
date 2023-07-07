<style>
#csrusel {
  width: 80%;
  height: 100%;
  min-height: 400px;
  overflow: hidden;
  position: relative;
  border-radius: 10px;
}
</style>
<template>
  <div className="flex flex-row justify-center mt-20 mb-20" >
    <div className="carousel rounded-box" id="csrusel">
      <div className="carousel-item w-full" v-for="e in article" :key="e.id">
        <img :src="e.image" className="w-full" alt="Tailwind CSS Carousel component" width="100%" />
      </div>
    </div>
  </div>
</template>
<script >
import imagen1 from '../assets/img/img1.png'
import imagen2 from '../assets/img/img2.png'
import imagen3 from '../assets/img/img3.png'
import imagen4 from '../assets/img/img4.png'
import imagen5 from '../assets/img/img5.png'
import imagen6 from '../assets/img/img6.png'
import imagen7 from '../assets/img/img7.png'
import imagen8 from '../assets/img/img8.png'
import imagen9 from '../assets/img/img9.png'
import imagen10 from '../assets/img/img10.png'
import imagen11 from '../assets/img/img11.png'
import imagen12 from '../assets/img/img12.png'
import imagen13 from '../assets/img/img13.png'
import imagen14 from '../assets/img/img14.png'
import imagen142 from '../assets/img/im15.png'
import imagen15 from '../assets/img/img15.png'
import imagen16 from '../assets/img/img16.png'
import imagen17 from '../assets/img/img17.png'
import imagen18 from '../assets/img/img18.png'
import imagen19 from '../assets/img/img19.png'
import imagen20 from '../assets/img/img20.png'
import imagen21 from '../assets/img/img21.png'
import imagen22 from '../assets/img/img22.png'
import imagen23 from '../assets/img/img23.png'
export default {
  data() {
    return {
      article: [
        {
          id: 1,
          image: imagen1,
        }, {
          id: 2,
          image: imagen2
        }, {
          id: 3,
          image: imagen3
        }, {
          id: 4,
          imagen: imagen4
        }, {
          id: 5,
          image: imagen5
        }, {
          id: 6,
          image: imagen6,
        }, {
          id: 7,
          image: imagen7
        }, {
          id: 8,
          image: imagen8
        }, {
          id: 9,
          imagen: imagen9,
        }, {
          id: 10,
          image: imagen10
        }, {
          id: 11,
          image: imagen11,
        }, {
          id: 12,
          image: imagen12

        }, {
          id: 13,
          image: imagen13
        }, {
          id: 14,
          imagen: imagen14
        }, {
          id: 142,
          image: imagen142
        }, {
          id: 15,
          image: imagen15,
        }, {
          id: 16,
          image: imagen16
        }, {
          id: 17,
          image: imagen17
        }, {
          id: 18,
          imagen: imagen18
        }, {
          id: 19,
          image: imagen19
        }, {
          id: 20,
          image: imagen20
        }, {
          id: 21,
          image: imagen21
        }, {
          id: 22,
          imagen: imagen22
        }, {
          id: 23,
          image: imagen23
        }
      ]
    }
  },

  methods: {

  },
}
</script>
