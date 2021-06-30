<template>
  <div class="frefre_header">
    <nav>
      <v-card class="overflow-hidden">
        <v-app-bar
          absolute
          color="white"
          elevate-on-scroll
          scroll-target="#scrolling-techniques-7"
          max-height="56px"
          style="position:fixed;"
        >

          <nuxt-link class="header_icon"to="/">
            <v-toolbar-title class="title">FreFre</v-toolbar-title>
          </nuxt-link>
          <v-spacer></v-spacer>

          <nuxt-link class="header_icon"to="/signin">
            <v-btn icon>
              <v-icon>mdi-account</v-icon>
            </v-btn>

            <div class="text">
              <div class="jp">会員登録</div>
              <div class="en">Sign in</div>
            </div>
          </nuxt-link>

          <nuxt-link class="header_icon"to="/login">
            <v-btn icon>
              <v-icon>mdi-application-import</v-icon>
            </v-btn>
            <div class="text">
              <div class="jp">ログイン</div>
              <div class="en">Login</div>
            </div>
          </nuxt-link>

        </v-app-bar>
      </v-card>
    </nav>
  </div>
</template>