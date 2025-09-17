<template>
  <v-container class="my-8">
    <v-row justify="center">
      <v-col cols="12">
        <h2 class="text-center mb-6">韓国のおすすめスポット</h2>
      </v-col>

      <v-col md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://cdn.pixabay.com/photo/2014/04/17/05/16/namdaemun-326138_1280.jpg"
            height="200px"
          ></v-img>
          <v-card-title>明洞</v-card-title>
          <v-card-text>
            明洞（ミョンドン）は、ソウルを代表する繁華街で、ショッピングとグルメの両方を楽しめる人気スポットです。コスメショップやファッションブランドが立ち並び、最新の韓国トレンドを体感できます。屋台グルメも充実しており、トッポッキやホットクなど食べ歩きも魅力のひとつ。夜になるとネオンが輝き、多くの観光客や地元の若者でにぎわいます。韓国らしい活気を存分に味わえる、訪れる価値のあるエリアです。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col  md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://images.pexels.com/photos/2848492/pexels-photo-2848492.jpeg"
            height="200px"
          ></v-img>
          <v-card-title> Nソウルタワー</v-card-title>
          <v-card-text>
           Nソウルタワーは、ソウルのランドマーク的存在で、南山の山頂にそびえる人気観光スポットです。高さ約236メートルのタワーからは、ソウルの街並みを360度一望でき、特に夜景はロマンチックで必見。展望台のほか、カフェやレストラン、ギフトショップも充実しており、観光の合間に立ち寄るのにも最適です。カップルに人気の「愛の南京錠」スポットもあり、思い出作りにもおすすめ。ソウル観光では外せない名所です。
          </v-card-text>
        </v-card>
      </v-col>

      <v-col  md="4">
        <v-card class="mx-auto" max-width="344" outlined>
          <v-img
            src="https://cdn.pixabay.com/photo/2022/08/05/05/59/korea-7366040_1280.jpg"
            height="200px"
          ></v-img>
          <v-card-title>昌徳宮（チャンドックン）【世界遺産】</v-card-title>
          <v-card-text>
            昌徳宮（チャンドックン）は、ユネスコ世界文化遺産にも登録されている朝鮮王朝時代の王宮で、ソウルに残る歴史的建築の中でも特に美しいと評判です。自然との調和を重視した造りが特徴で、四季折々の景色が楽しめる「秘苑（ビウォン）」は必見。静かで落ち着いた雰囲気の中、宮殿の壮麗な建物や庭園を散策すれば、まるで王朝時代にタイムスリップしたような感覚を味わえます。歴史と自然が調和する癒しのスポットです。
          </v-card-text>
        </v-card>
      </v-col>
      
 <v-col cols="12" class="text-center mt-8">
        <v-btn
          color="primary"
          large
          rounded
          @click="$router.push('/KoreaPlan')" 
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
