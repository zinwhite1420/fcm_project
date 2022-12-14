<template>
  <v-app>
    <v-app-bar title="FCM PROJECT" color="green">
    </v-app-bar>
    <v-main>
      <PushList></PushList>
    </v-main>
  </v-app>
</template>

<script>

import PushList from "@/components/PushList";
export default {
  name: 'App',

  components: {
    PushList

  },

  data: () => ({
    //
  }),
}
</script>
