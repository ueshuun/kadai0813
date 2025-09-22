<template>
  <v-container class="my-8">
    <v-row justify="center">
      <v-col cols="12">
        <h2 class="text-center mb-6">ハワイのおすすめスポット</h2>
      </v-col>

      <v-col md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://t4.ftcdn.net/jpg/02/93/57/29/360_F_293572963_M05gvwXcV8QKHKKclwLrtbPLR9apd4mp.webp"
            height="200px"
          ></v-img>
          <v-card-title>ダイヤモンドヘッド</v-card-title>
          <v-card-text>
            ダイヤモンドヘッドは、オアフ島を代表する人気スポットで、ワイキキから気軽にアクセスできる火山クレーターです。標高232メートルの頂上へは片道約30分ほどのハイキングで到着でき、初心者でも挑戦しやすいのが魅力。頂上からはワイキキビーチやホノルルの街並み、真っ青な海が一望でき、特に朝日は感動的です。ハワイらしい絶景を体いっぱいに感じられるおすすめの場所です。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col  md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://ruimaeda.com/wp-content/uploads/cache/2000_2018-12-06_16-11-04_730/274870745.jpg"
            height="200px"
          ></v-img>
          <v-card-title>ワイキキビーチ</v-card-title>
          <v-card-text>
           ワイキキビーチは、ハワイを象徴する世界的に有名なビーチで、透き通る海と白い砂浜が魅力です。全長約3kmにわたって続くビーチはリゾートホテルやショップが立ち並び、ショッピングやグルメも同時に楽しめます。海水浴やサーフィン、サンセット鑑賞などアクティビティも豊富で、初心者向けのサーフィンスクールも充実。昼は明るく開放的な雰囲気、夜はロマンチックな夜景と、多彩な魅力が詰まった人気スポットです。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col  md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://cdn.pixabay.com/photo/2022/07/23/16/05/shopping-mall-7340181_1280.jpg"
            height="200px"
          ></v-img>
          <v-card-title>アラモアナセンター</v-card-title>
          <v-card-text>
            アラモアナセンターは、ホノルルにある世界最大級のオープンエア・ショッピングモールで、ハワイ旅行で外せない人気スポットです。約350以上のショップやレストランが集まり、ハイブランドからローカルショップまで幅広く揃っています。フードコートでは多彩なグルメが楽しめ、買い物の合間に一息つくのにも最適。アクセスもワイキキからバスやトロリーで便利で、一日中楽しめるショッピング&グルメスポットです。
          </v-card-text>
        </v-card>
      </v-col>
      <v-col cols="12" class="text-center mt-8">
        <v-btn
          color="primary"
          large
          rounded
          @click="$router.push('/HawaiiPlan')" 
        >
          2泊3日のモデルプラン
        </v-btn>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HawaiiView",
};
</script>
