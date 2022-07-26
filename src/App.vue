<template>
  <v-app>
    <v-main>
      <Login />
    </v-main>
  </v-app>
</template>

<script>
import Login from './components/Login';

export default {
  name: 'App',

  components: {
    Login,
  },

  data: () => ({
    //
  }),
};
</script>
<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
</style>
