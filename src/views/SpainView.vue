<template>
  <v-container class="my-8">
    <v-row justify="center">
      <v-col cols="12">
        <h2 class="text-center mb-6">スペインのおすすめスポット</h2>
      </v-col>

      <v-col md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://t4.ftcdn.net/jpg/01/41/32/23/240_F_141322312_k0KBHFfcs34JepipgmqmUPZjesGtIqvt.jpg"
            height="200px"
          ></v-img>
          <v-card-title>サクラダファミリア</v-card-title>
          <v-card-text>
            サグラダ・ファミリアは、スペイン・バルセロナを象徴する未完成の大聖堂で、建築家アントニ・ガウディの代表作として知られています。1882年に着工され、独創的なデザインと壮大なスケールで世界中の人々を魅了してきました。外観は聖書の物語を表現した彫刻で彩られ、内部は光が差し込む幻想的な空間が広がります。完成を目指して今も建設が続く姿そのものが歴史であり、訪れる人に深い感動を与える必見のスポットです。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col  md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://t4.ftcdn.net/jpg/01/59/44/67/240_F_159446732_2HxRITFbRwxWec68c5sNgOTTd6ET78Az.jpg"
            height="200px"
          ></v-img>
          <v-card-title>マドリード王宮</v-card-title>
          <v-card-text>
           マドリード王宮は、スペイン国王の公式宮殿で、ヨーロッパ最大級の壮麗な王宮として知られています。18世紀に建てられたバロック様式の建築は豪華で美しく、内部には美術品や調度品が数多く展示されています。特に王座の間や鏡の間は圧巻で、当時の王室の華やかな暮らしぶりを垣間見ることができます。現在は儀式や公式行事に利用されつつ一般公開もされており、芸術と歴史を同時に体感できる必見のスポットです。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col  md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://t4.ftcdn.net/jpg/02/63/24/59/240_F_263245931_PnJhAEUymFqLQd8RekEBhwVLTeNIL1Pb.jpg"
            height="200px"
          ></v-img>
          <v-card-title>アルハンブラ宮殿</v-card-title>
          <v-card-text>
            アルハンブラ宮殿は、スペイン南部グラナダに位置するイスラム建築の最高傑作で、ユネスコ世界遺産にも登録されています。13世紀にナスル朝の王によって築かれ、精緻なアラベスク模様や幾何学的な装飾、美しい噴水や庭園が訪れる人々を魅了します。宮殿内の「ライオンの中庭」や「アラヤネスの中庭」では、幻想的な雰囲気に包まれながら当時の栄華を感じられます。芸術と歴史が融合した、スペイン観光に欠かせない名所です。
          </v-card-text>
        </v-card>
      </v-col>
       <v-col cols="12" class="text-center mt-8">
        <v-btn
          color="primary"
          large
          rounded
          @click="$router.push('/')" 
        >
          2泊3日のモデルプラン
        </v-btn>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "SpainView",
};
</script>
