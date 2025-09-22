<template>
  <v-container class="my-8">
    <v-row justify="center">
      <v-col cols="12">
        <h2 class="text-center mb-6">北海道のおすすめスポット</h2>
      </v-col>

      <v-col cols="12" md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://t4.ftcdn.net/jpg/01/20/55/67/240_F_120556749_oG8I7eFczWtCPm5w1fYIfp1NVm2cc1BG.jpg"
            height="200px"
          ></v-img>
          <v-card-title>札幌テレビ塔</v-card-title>
          <v-card-text>
            札幌市の中心、大通公園にそびえる「札幌テレビ塔」は、1957年に完成した高さ147.2メートルのランドマークです。展望台からは四季折々の大通公園を一望でき、雪まつりやイルミネーションの時期には特に美しい景観を楽しめます。夜にはライトアップも行われ、昼夜で異なる表情を見せるのも魅力。観光や散策の合間に立ち寄りたい札幌の代表的スポットです。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col cols="12" md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://t3.ftcdn.net/jpg/02/49/79/86/240_F_249798621_AIcEvARXeJC8MDLRge1V8V620VpMOOSP.jpg"
            height="200px"
          ></v-img>
          <v-card-title>旭川動物園</v-card-title>
          <v-card-text>
         北海道・旭川市にある「旭山動物園」は、日本最北の動物園として知られ、動物本来の行動を引き出す「行動展示」で全国的に有名です。ホッキョクグマのダイナミックな泳ぎや、ペンギンの散歩など、臨場感あふれる展示は子どもから大人まで楽しめます。動物たちの生き生きとした姿を間近で感じられる、北海道観光で外せない人気スポットです。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col cols="12" md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://t4.ftcdn.net/jpg/02/91/38/97/240_F_291389777_cuGvQhUPXd7BC6vJd7L4pkKbjPoImTeF.jpg"
            height="200px"
          ></v-img>
          <v-card-title>富良野</v-card-title>
          <v-card-text>
            北海道のほぼ中心に位置する「富良野」は、美しい自然と四季折々の風景が楽しめる人気エリアです。特に夏のラベンダー畑は一面が紫色に染まり、絶景として多くの観光客を魅了します。冬はスキーリゾートとしても知られ、パウダースノーを満喫できるスポットに。ドラマの舞台にもなったこの地は、北海道の魅力を存分に感じられる場所です。
          </v-card-text>
        </v-card>
      </v-col>
<v-col cols="12" class="text-center mt-8">
        <v-btn
          color="primary"
          large
          rounded
          @click="$router.push('/HokkaidoPlan')" 
        >
          2泊3日のモデルプラン
        </v-btn>
      </v-col>
       

    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HokkaidoPlanView",
};
</script>
