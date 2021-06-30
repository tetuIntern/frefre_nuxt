<template>
  <div>
    <frefre-header />
    <div class="default">
      <nuxt />
    </div>
  </div>
</template>

<script>
import FrefreHeader from '@/components/header.vue';
export default {
  components:{
    FrefreHeader,
  }
}

</script>