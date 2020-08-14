<template>
  <v-app>
    <router-view></router-view>
     <v-img src="@/assets/f-logo.png" width="20%" class="mx-auto"></v-img>
     <v-title class="mx-auto">
       <h2>Finder</h2>
    </v-title>
    <v-card width="400px" class="mx-auto mt-5">
      <v-card-title>
        <h1 class="mx-auto display-1">ログイン</h1>
      </v-card-title>
     <v-card-text>
        <v-form>
          <v-text-field prepend-icon="mdi-account-circle" label="ユーザー名"/>
          <v-text-field prepend-icon="mdi-lock" append-icon="mdi-eye-off" type="password" label="パスワード"/>
          <v-card-actions>
            <v-btn class="info" @click="toTop">ログイン</v-btn>
            <v-btn class="success mx-auto" @click="toNew">新規登録</v-btn>
          </v-card-actions>
        </v-form>
      </v-card-text>
    </v-card>
    <v-text class="mx-auto mt-9">
      <h3>What's Finder?</h3>
    </v-text>
    <v-text class="mx-auto" style="text-align:center">
      <p>同期で交流する機会って、あまりないですよね～<br>
         そんなときにFinder(フィンダー)!!<br>
         同じ趣味を持っている同期、<br>
         大学の専攻が似ている同期、<br>
         出身が同じ同期など<br>
          Finderを使えば、すぐに見つかります！<br>
          みんなでレッツFinder!!</p>
    </v-text>
  </v-app>
</template>

<script>
export default {
  methods: {
    toTop () {
      this.$router.push({ path: 'top' })
    },
    toNew(){
      this.$router.push({ path: 'about'})
      
    }
  }
}
</script>
