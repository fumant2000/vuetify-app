<template>
    <v-toolbar flat app prominent>
        <v-app-bar-nav-icon color="grey" @click="drawer = !drawer"></v-app-bar-nav-icon>
        <v-toolbar-title class="text-uppercase grey--text">
            <span class="font-weight-light">Todo</span>
            <span>SEDS</span>
        </v-toolbar-title>
        <v-btn flat color="grey">
            <span>Sign Out</span>
            <v-icon
          icon="mdi-logout"
          end
        ></v-icon>
        </v-btn>
        <v-navigation-drawer
        v-model="drawer" app class="blue">
      </v-navigation-drawer>

    </v-toolbar>
</template>
<script >
export default {
    data(){
        return{
            drawer: false
        }
    }

}
</script>
