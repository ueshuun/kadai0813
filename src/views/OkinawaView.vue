<template>
  <v-container class="my-8">
    <v-row justify="center">
      <v-col cols="12">
        <h2 class="text-center mb-6">沖縄のおすすめスポット</h2>
      </v-col>

      <v-col cols="12" md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://as1.ftcdn.net/v2/jpg/09/72/19/30/1000_F_972193032_DT94e6Xwgo4IyZEWkg9eDA8km6RhAeNK.jpg"
            height="200px"
          ></v-img>
          <v-card-title>沖縄美ら海水族館</v-card-title>
          <v-card-text>
            沖縄本島北部の海洋博公園内にある「美ら海水族館」は、世界最大級の水槽を誇る大人気スポット。ジンベエザメやマンタが悠々と泳ぐ姿は迫力満点で、まるで海の中に入り込んだような感覚を味わえます。熱帯魚や深海生物など、多彩な海の世界を楽しめる展示が充実。沖縄観光では外せない必見のスポットです。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col cols="12" md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://t3.ftcdn.net/jpg/04/39/13/74/240_F_439137495_JJvsIue46ERqBcnC094o47g69xSyjqlt.jpg"
            height="200px"
          ></v-img>
          <v-card-title>首里城</v-card-title>
          <v-card-text>
           沖縄の歴史と文化を象徴する「首里城」は、かつて琉球王国の政治・文化の中心地として栄えた名城です。鮮やかな朱色の正殿や独特の建築様式は、沖縄と中国、日本の文化が交わった独自の美を感じさせます。2019年の火災で大きな被害を受けましたが、現在も復元工事が進められており、歴史の歩みと再生の姿を間近に見られる貴重なスポットです。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col cols="12" md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://t3.ftcdn.net/jpg/00/71/14/86/240_F_71148658_q2Nnw7AiT9BJ1XCyEl84yeRKDMsOAC1r.jpg"
            height="200px"
          ></v-img>
          <v-card-title>古宇利島</v-card-title>
          <v-card-text>
            16世紀後半に豊臣秀吉の居城として建てられた「大阪城」。1615年の「大坂夏の陣」で焼失しましたが、徳川幕府によって再建されました。黄金の装飾が輝く天守閣の内部は、8階建ての博物館になっています。大阪城や豊臣秀吉に関する資料や、しゃちほこの原寸大レプリカが展示されています。最上階の回廊式展望台からは、大阪の街並みを360度から眺められます。
          </v-card-text>
        </v-card>
      </v-col>
       <v-col cols="12" class="text-center mt-8">
        <v-btn
          color="primary"
          large
          rounded
          @click="$router.push('/OkinawaPlan')" 
        >
          2泊3日のモデルプラン
        </v-btn>
      </v-col>

    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "OsakaView",
};
</script>
