<template>
<section>
  <AsideLeft />
  <div class="container">
    <h1>
      <img src="https://quant-k.co.kr/img/logo.png" alt="quantk">
    </h1>
    <div>
      <SlideMaq />
    </div>
  </div>
</section>
</template>

<script>
import Vue from 'vue'
import AsideLeft from '@/components/Aside'
import SlideMaq from '@/components/Maqu'

export default {
  name: 'main_page',
  layout:'default',
  data() {
    return {
      activeIndex: '1',
    }
  },
  components: {
    AsideLeft,
    SlideMaq
  },
  computed : {
    
  },
  created(){
    
  },
  watch: {
  },
  methods: {
    handlePaging(pagination){
      
    },
  },
  mounted() {  
    
    
    
  }
}
</script>

<style lang="scss" scoped>

.container {
  box-sizing: border-box;
  padding-left:300px;
  width: 1024px;
  h1 {
    width: 120px;
    img{
      width: 100%;
    }
  }
}


</style>
