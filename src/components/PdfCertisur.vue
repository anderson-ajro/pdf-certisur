<template>
  <div class="text-center btn">

      <template>
        <v-btn
          color="pink"
        >
          <a href="https://drive.google.com/file/d/1YmPbC0fO_HwESmRuxtOtaElGACcBNg9d/view?usp=sharing" target="_blank">Ver Pdf</a>
        </v-btn>
      </template>

  </div>
</template>
    
<script>
  export default {
    data () {
      return {}
    },
  }
</script>

<style scoped>
a{
text-decoration: none;
color: white !important;
}

.btn{
    height: 100%;
    background-color: #EEE;
    display:flex;
    justify-content: center;
    align-items: center;
}
</style>