<template>
  <div class="community">
    <img class="com_img"v-bind:src='com.img'>
    <div class="title_show_cover">
      <div class="title_show">{{com.jp}}</div>
      <div class="title_show">{{com.en}}</div>
    </div>
  </div>
</template>
<script>
export default {
    props: ['com']
}
</script>