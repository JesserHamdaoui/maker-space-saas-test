<template template>
  <div>
    <v-navigation-drawer v-model="drawer" app class="indigo">
      <v-toolbar-title>My App</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn text>Home</v-btn>
    <v-btn text>About</v-btn>
    <v-btn text>Contact</v-btn>
    </v-navigation-drawer>
  </div>
</template>

<script>
export default{
Data(){
    return{
        drawer: true
    }
}
}
</script>

<style></style>
