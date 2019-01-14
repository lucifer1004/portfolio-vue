<template>
  <div class="apollo"><ApolloExample /></div>
</template>

<script lang="ts">
import Vue from 'vue'
import ApolloExample from '@/components/ApolloExample.vue'

export default Vue.extend({
  name: 'apollo',
  components: {
    ApolloExample,
  },
})
</script>
