<template>
  <v-container class="my-8">
    <v-row justify="center">
      <v-col cols="12">
        <h2 class="text-center mb-6">大阪のおすすめスポット</h2>
      </v-col>

      <v-col md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://as2.ftcdn.net/v2/jpg/14/73/04/95/1000_F_1473049553_c3ABJUQF6uXjou9KwwdmyKC9VwAsi1jd.jpg"
            height="200px"
          ></v-img>
          <v-card-title>大阪万博</v-card-title>
          <v-card-text>
            2025年に大阪・夢洲で開催される「大阪万博（大阪・関西万博）」は、世界中の知恵と技術が集まる未来型イベントです。最先端の科学技術や環境・医療分野の展示に加え、各国のパビリオンでは多彩な文化や食も体験できます。会場全体がテーマパークのように彩られ、子どもから大人まで楽しめるスポットとして注目されています。観光や学びを兼ねた特別な体験を味わえる、日本を代表する一大イベントです。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col  md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://as1.ftcdn.net/v2/jpg/11/76/70/10/1000_F_1176701002_OOTSgbtqWMr8jdngQKNqCmh5tuh2sioS.jpg"
            height="200px"
          ></v-img>
          <v-card-title>新世界</v-card-title>
          <v-card-text>
           大阪の下町情緒あふれる観光エリア「新世界」は、レトロな雰囲気と活気あふれる街並みが魅力のスポットです。シンボルである通天閣からは大阪の街を一望でき、夜のネオン街も見どころ。周辺には串カツ店やたこ焼きの名店が立ち並び、食べ歩きも楽しめます。庶民的な活気と大阪らしい人情に触れられる、観光でも外せない定番の人気エリアです。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col  md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://as2.ftcdn.net/v2/jpg/02/64/30/87/1000_F_264308766_9LPiZWazBnUFCOZ4nntQ6Xo1U4wGXrvW.jpg"
            height="200px"
          ></v-img>
          <v-card-title>大阪城</v-card-title>
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
          @click="$router.push('/OsakaPlan')" 
        >
          1泊2日のモデルプラン
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
