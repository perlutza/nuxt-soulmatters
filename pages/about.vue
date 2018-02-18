<template>
<div>
<grid-list>
</grid-list>

<v-card>
     <v-card-title>
         
     </v-card-title>
    <v-card-media>
        
    </v-card-media>
<img src="/images/pw.jpg">
    <v-card-text>
        
    </v-card-text>
    <v-card-actions>
    </v-card-actions>
</v-card>

</div>
    </template>   

<style>
v-card{
    background-color:red;
    width:100%;
    height:auto;
}

v-card-title{
    font-size: 30px;
    text-align: center;
}

v-card-text{
    max-width: 300px;
    height: auto;
    background-color: aqua;
}


</style>

<script>
import GridList from '~/components/GridList.vue'


export default {
  components: {
    GridList
  }
}

</script>