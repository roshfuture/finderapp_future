<template>
   <v-app>
       <v-conteiner>
         <v-title>
           <v-img src='@/assets/f-logo.png' width="10%" class="mx-auto"></v-img>
           <h1 style="text-align:center" class="mt-5">Finder</h1>
         </v-title>
        <v-card width="1000px" height="800px" class="mx-auto mt-5">
           <v-card-title>
               <h2 class="mx-auto display-1">Finderへようこそ</h2>
           </v-card-title>
           <v-card-text>
               <p class="mt-5" style="text-align:center">Finderは同期とマッチングできるアプリです</p>
           </v-card-text>
           <br>
           <br>
           <br>
           <br>
           <br>
           <br>
           <v-layout wrap>
          <v-flex xs12 sm6 md4 text-center my-5><v-btn width="200px" height="100px" color="light-blue lighten-4" elevation="10">マッチング検索</v-btn></v-flex>
          <v-flex xs12 sm6 md4 text-center my-5><v-btn width="200px" height="100px" color="light-blue lighten-4" elevation="10">同期一覧</v-btn></v-flex>
          <v-flex xs12 sm6 md4 text-center my-5><v-btn width="200px" height="100px" color="light-blue lighten-4" elevation="10">プロフィール画面編集</v-btn></v-flex>
        </v-layout>

         </v-card>
       </v-conteiner>
   </v-app>
</template>
