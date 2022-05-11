<template>
  <v-container
    fluid
    class="d-flex justify-center">
    <v-col
        cols="12"
        sm="11" 
        md="9"
        lg="7">
      <Header />
      <v-card
        tile 
        color="#f8f9fa">
        <v-row>
          <v-col
            cols="12"
            xs="12"
            sm="5" 
            class="text-justify"
            align="center">
            <SideBar />
          </v-col>
          <v-divider 
            vertical 
            class="d-none d-sm-block">
          </v-divider>
          <v-col
            cols="12"
            xs="12"
            sm="6" >
            <Content />
          </v-col>
        </v-row>
        <Footer />
      </v-card>
    </v-col>
  </v-container>
</template>

<script src="./CvDigital.js"></script>

