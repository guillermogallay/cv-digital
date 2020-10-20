<template>
  <v-container 
    fluid
    class="d-flex justify-center">
      <v-col
        cols="12" 
        md="8">
          <v-card 
            color="white" 
            tile>
              <CvHeader />
          </v-card>
      </v-col>
  </v-container>
</template>

<script>
  import CvHeader from "@/components/cv-header/CvHeader.vue";

  export default {
    components: {
    CvHeader,
    },
  }
</script>

