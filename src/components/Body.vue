<template>
  
    <div class="app-content">
        <div class="korea__container">
            <div class="korea__set">
                <Header />
                <Article />
            </div>
            <Caution />
        </div>
    </div>

    <div class="m-korea__container">
      <div class="m-korea__set">
        <MHeader />
        <MArticle />
      </div>
      <MCaution />
    </div>
</template>



<script>
import Header from '../components/common/Header.vue'
import Article from './common/Article.vue'
import Caution from './common/Caution.vue'

import MHeader from './common/M_Header.vue'
import MArticle from './common/M_Article.vue'
import MCaution from './common/M_Caution.vue'


export default {
    methods: {
    },
    components: {
        Header,
        MHeader,
        Article,
        MArticle,
        Caution,
        MCaution
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<!-- <style src="C:\vueTest\test\src\assets\common.css"></style> -->

<style src="../assets/common.css"></style>
