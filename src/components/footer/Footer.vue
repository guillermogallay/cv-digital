<template>
    <v-footer
        color="black"
        class="text-center">
          <v-card-text>
            <a 
                v-for="icon in icons"
                :key="icon.id"
                :href="icon.link"
                target="_blank"
                class="ma-2 text-decoration-none"> 
                    <v-icon color="white">{{icon.name}}</v-icon>
            </a> 
          </v-card-text>

          <v-card-text class="white--text">
            {{ dateNow }} — By Guillermo Gallay
          </v-card-text>
    </v-footer>
</template>

<script src="./footer.js"></script>