<template>
  <v-container class="my-8">
    <v-row justify="center">
      <v-col cols="12">
        <h2 class="text-center mb-6">京都のおすすめスポット</h2>
      </v-col>

      <v-col cols="12" md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://t4.ftcdn.net/jpg/05/81/75/39/240_F_581753968_jtnwxHAx3Ezg4HlRxzNKSJEKazVICawX.jpg"
            height="200px"
          ></v-img>
          <v-card-title>清水寺【世界遺産】</v-card-title>
          <v-card-text>
          京都を代表する名所「清水寺」は、世界遺産にも登録される歴史ある寺院です。東山の中腹に位置し、舞台造りの本堂からは四季折々の京都市街を一望できます。桜や紅葉の名所としても有名で、訪れるたびに異なる景観を楽しめるのが魅力です。境内には音羽の滝や多くの重要文化財が点在し、京都観光には欠かせない定番スポットです。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col cols="12" md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://64.media.tumblr.com/5084eb6dc9b812bdec7a59c99a44ac24/tumblr_o20od5J4nP1t4k8xoo1_1280.jpg"
            height="200px"
          ></v-img>
          <v-card-title>金閣寺【世界遺産】</v-card-title>
          <v-card-text>
          京都を代表する観光名所「金閣寺（鹿苑寺）」は、舎利殿が黄金に輝く美しい寺院です。鏡湖池に映り込むその姿は四季を通じて幻想的で、雪化粧や紅葉に包まれた風景は特に人気があります。足利義満ゆかりの寺として歴史的にも重要で、日本文化の象徴ともいえる存在です。国内外から多くの観光客が訪れる京都必見のスポットです。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col cols="12" md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://t3.ftcdn.net/jpg/07/52/76/02/240_F_752760242_K6wOSaTVZy8Q4NYaypsIjOZ7oDEFlt9l.jpghttps://t3.ftcdn.net/jpg/07/52/76/02/240_F_752760242_K6wOSaTVZy8Q4NYaypsIjOZ7oDEFlt9l.jpg"
            height="200px"
          ></v-img>
          <v-card-title>京都タワー</v-card-title>
          <v-card-text>
           京都駅前にそびえる「京都タワー」は、高さ131メートルを誇る京都のランドマーク。展望室からは市内全域を一望でき、晴れた日には比叡山や大阪方面まで見渡せます。夜にはライトアップされ、昼と夜で異なる魅力を楽しめるスポットです。館内にはお土産ショップや大浴場もあり、観光や旅行の拠点として人気を集めています。
          </v-card-text>
        </v-card>
      </v-col>
       
<v-col cols="12" class="text-center mt-8">
        <v-btn
          color="primary"
          large
          rounded
          @click="$router.push('/KyotoPlan')" 
        >
          1泊2日のモデルプラン
        </v-btn>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "KyotoView",
};
</script>
