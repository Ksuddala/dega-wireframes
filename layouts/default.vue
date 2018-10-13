<template>
  <v-container pa-0 fluid>
  <v-layout row wrap ma-0> 
    <v-flex xs12 sm12 md>
  <v-app >
   <AppHome />
   <v-navigation-drawer
     :mini-variant.sync="mini"
      :clipped="clipped"
      :disable-resize-watcher="true"
      permanent
      fixed
      hide-overlay
      app
      width="200"

     
      
      
    >
    <v-toolbar flat>
      <v-list>
        <v-list-tile>
          
          <v-list-tile-title class="title">
            DEGA 
            
          </v-list-tile-title>


            
          </v-list-tile-action>
        </v-list-tile>
      </v-list>
    </v-toolbar>

      <v-list>
        <v-list-tile
          router
          :to="item.to"
          :key="i"
          v-for="(item, i) in items"
          exact

        >

        
          <v-list-tile-action>
            <v-icon color ="black" v-html="item.icon"></v-icon>

          </v-list-tile-action>
          <v-list-tile-content>
            <v-list-tile-title v-text="item.title"></v-list-tile-title>
          </v-list-tile-content>
        
        </v-list-tile>
      </v-list>
    </v-navigation-drawer>
    
    <v-toolbar flat color="transparent" dark fixed app :clipped-left="clipped">
      <toolbar-side-icon></toolbar-side-icon>
      <v-toolbar-side-icon  @click="drawer = !drawer" ></v-toolbar-side-icon>
      
<v-toolbar-title class ="display-2" v-text="title"></v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        icon 
        @click.stop="rightDrawer = !rightDrawer"
      >
        
      </v-btn>
     </v-toolbar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    
    <v-footer :fixed="fixed" app>
      <span>&copy; 2018</span>
    </v-footer>
    </v-app>
  </v-flex>
  </v-layout>
</v-container>
</template>
<script>
  import AppHome from '~/components/AppHome'
export default {
    components: {
      AppHome
    },
    data () {
      return {
        clipped: false,
        drawer: null,
        fixed: false,
        items: [
          { icon: 'home', title: 'Home', to: '/' },
          { icon: 'people', title: 'About Us', to: '/About Us' },
          { icon: 'inbox', title: 'Lists', to: '/Lists' },
          { icon: 'duo', title: 'Videos', to: '/Videos' }
        ],
        mini: false,
        right: true,
        rightDrawer: false,
        title: 'DEGA'
      }
    }
}
</script>

