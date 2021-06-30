<template>
  <div class='community_list'>
    <nuxt-link v-for='(com, i) in community' :index='i'class="community"to="/FreFre">
     <img class="com_img"v-bind:src='com.img'>
     <div class="title_show_cover">
       <div class="title_show">{{com.jp}}</div>
       <div class="title_show">{{com.en}}</div>
     </div>
    </nuxt-link>
  </div>
</template>

<script>
export default {
  data(){
    return{
      community:[
        {jp:'全員参加コミュニティ',en:'Compulsory Community',img:require('@/assets/image/com_1.png')},
        {jp:'ガンダムについて話し合おう！',en:"Let's talk about Gundom!",img:require('@/assets/image/com_2.jpg')},
        {jp:'富士山の情報交換コミュニティ',en:'Fuji Information Community',img:require('@/assets/image/com_3.png')},
        {jp:'和食グルメの会',en:'Japanese Food Group',img:require('@/assets/image/com_4.jpg')},
        {jp:'日本語を楽しく勉強しよう！',en:"Let's Enjoy Studyinh Japanese",img:require('@/assets/image/com_5.png')},
        {jp:'和菓子大好き',en:'I love wagashi',img:require('@/assets/image/com_6.jpg')},
        {jp:'アニメ',en:'Anime',img:require('@/assets/image/com_7.jpg')}
      ]
    }
  },
  methods: {
    com_get(id) {
      return community[id];
    }
  }
}
</script>