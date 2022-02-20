<template>
    <v-col
        cols="12"
        xs="12"
        sm="5" 
        class="text-justify"
        align="center">
        <section>
            <v-card-title>
                <h4 roboto>SOBRE MÍ</h4>
            </v-card-title>
            <v-card-text>
                <p>
                    Soy una persona muy responsable, puntual y aplicada que 
                    le gusta mucho el desarrollo web, sobre todo el frontend.
                </p>
                <p>
                    Trato de aprovechar al máximo el trabajo en equipo, 
                    siempre estoy abierto a evaluar diferentes puntos de vista 
                    y opiniones con el fin de alcanzar el mejor resultado.
                </p>
                <p>
                    Me considero una persona autodidacta, cuando se presenta algún problema trato de 
                    resolverlo aplicando mis experiencias o investigando para adquirir nuevos conocimientos.
                </p> 
                <p>
                    Mi principal objetivo es seguir mejorando día a día como recurso, 
                    tanto en lo técnico como personal.
                </p> 
            </v-card-text>
        </section>
        <section>
            <v-card-title>
                <h4 roboto>CONTACTO</h4>
            </v-card-title>
            <v-card-text>
                <p>
                    <a 
                        v-for="contacto in contactos"
                        :key="contacto.name"
                        :href="contacto.link"
                        target="_blank"
                        class="text-decoration-none"> 
                        <v-row>
                            <v-col>
                                <v-icon 
                                    color="#212529">
                                    {{contacto.name}}
                                </v-icon>
                                {{contacto.description}}
                            </v-col>
                        </v-row>
                    </a> 
                </p>
            </v-card-text>
        </section>
    
        <section>
            <v-card-title>
                <h4 roboto>HERRAMIENTAS</h4>
            </v-card-title>
            <v-card-text >
                <v-chip 
                    class="ma-2"
                    v-for="herramienta in herramientas"
                    :key="herramienta.id">
                        {{herramienta.name}}
                </v-chip>
            </v-card-text>
        </section>
    </v-col>
</template>

<script src="./SideBar.js"></script>