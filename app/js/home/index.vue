<template lang="html">
    <div :class="$style.home">
        <Heador/>
        <Hsilder/>
        <Novice/>
        <Brorow/>
        <Money/>
        <Product/>
        <Life/>
        <Footer/>
        <Navbar/>
    </div>
</template>

<script>
import Heador from './../public/header.vue'
import Hsilder from './hslider.vue'
import Novice from './novice.vue'
import Brorow from './brorow.vue'
import Money from './money.vue'
import Product from './product.vue'
import Life from './life.vue'
import Footer from './../public/footer.vue'
import Navbar from './../public/navbar.vue'
export default {
  components:{
    Heador,
    Hsilder,
    Novice,
    Brorow,
    Money,
    Product,
    Life,
    Footer,
    Navbar
  }
}
</script>

<style lang="scss" module>
.home{
  background:#dedcdc;
}
</style>
