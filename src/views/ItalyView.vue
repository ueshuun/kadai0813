<template>
  <v-container class="my-8">
    <v-row justify="center">
      <v-col cols="12">
        <h2 class="text-center mb-6">イタリアのおすすめスポット</h2>
      </v-col>

      <v-col md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://t3.ftcdn.net/jpg/02/82/38/10/360_F_282381041_O7uUYn2MgQHcltBSnRnVf2daOZDR9nmO.webp"
            height="200px"
          ></v-img>
          <v-card-title>コロッセオ【世界遺産】</v-card-title>
          <v-card-text>
           コロッセオは、ローマを象徴する世界最大級の円形闘技場で、西暦80年に完成しました。古代ローマ時代には剣闘士の試合や見世物が行われ、5万人以上の観客を収容できたといわれています。現在も外観の迫力は圧倒的で、当時の建築技術や壮大な歴史を感じられるスポットです。内部を見学すれば、アリーナや地下施設の構造を間近に体験でき、古代ローマの栄華に触れることができます。歴史ファン必見の世界遺産です。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col  md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://t3.ftcdn.net/jpg/02/11/64/82/240_F_211648237_6qTJsvxLSmQd8nE6lUH2HTLLd3MQ0N4w.jpg"
            height="200px"
          ></v-img>
          <v-card-title>ベネチア</v-card-title>
          <v-card-text>
           ベネチアは、イタリア北東部に位置する水の都で、世界的に有名な観光地です。大小100以上の島々が運河で結ばれ、美しい橋や歴史的建築が街を彩ります。サン・マルコ広場やドゥカーレ宮殿など見どころが多く、ゴンドラに揺られながら眺める街並みはまさに幻想的。夕暮れ時には運河に映る建物が輝き、ロマンチックな雰囲気に包まれます。芸術・建築・グルメと多彩な魅力を持つ、まさに一度は訪れたい夢の都市です。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col  md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://t4.ftcdn.net/jpg/02/53/72/81/240_F_253728100_OdY0dWCgGz3Ug5T0kBU0wWTHIpgkusj9.jpg"
            height="200px"
          ></v-img>
          <v-card-title>ピサの斜塔</v-card-title>
          <v-card-text>
            ピサの斜塔は、イタリア・トスカーナ地方にある世界的に有名な建造物で、その独特な傾きで知られています。1173年に建設が始まり、地盤の軟弱さから徐々に傾きが生じましたが、それが現在では大きな魅力となっています。高さ約55メートルの塔には294段の階段があり、上まで登るとピサの街並みやカンポ広場の美しい景観を一望できます。ユニークな外観と歴史を併せ持つ、まさにイタリア観光のハイライトです。
          </v-card-text>
        </v-card>
      </v-col>
      <v-col cols="12" class="text-center mt-8">
        <v-btn
          color="primary"
          large
          rounded
          @click="$router.push('/ItalyPlan')" 
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
