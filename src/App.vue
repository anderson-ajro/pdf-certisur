<template>
  <v-app>
    <v-main>
      <PdfCertisur/>
    </v-main>
  </v-app>
</template>

<script>
import PdfCertisur from './components/PdfCertisur';

export default {
  name: 'App',

  components: {
    PdfCertisur,
  },

  data: () => ({
    //
  }),
};
</script>
