<template>
  <section>
    <div class="container mx-auto px-5 py-[120px] flex flex-col items-center">
      <h2 class="capitalize text-center text-4xl font-bold mb-14">xizmatlar</h2>
      <div class="flex flex-col items-center max-w-[850px] w-[100%] mx-auto">
        <div v-for="item in items" class="flex items-center mb-20 last:mb-15">
          <img class="mr-16" src="../assets/img/image1.jpg" alt="">
          <div>
            <h3 class="font-bold text-2xl capitalize mb-6">{{ item.title }}</h3>
            <p class="text-base text-[#444] ">{{ item.text }}</p>
          </div>
        </div>
      </div>
      <Button />
    </div>
  </section>  
</template>

<script>
import Button from './Button'
export default {
  name: 'App',
  data() {
    return {
      items: [
        {id: 0, title: 'hijoma', text: 'Imom Termiziy Abdulloh ibn Abbos raziyallohu anhumodan rivoyat qilgan hadisda rasululloh sallallohu alayhi va sallam dedilar: «Sizlar hijoma qiladigan kunlaringizning eng yaxshisi 17, 19 va 21-kunlardir» (bu kunlar hijrij-kamariy hisobdagi oylar kunlaridir).'},
        {id: 1, title: 'Manual terapiya', text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla ac metus placerat, pellentesque enim ac, rhoncus lectus. Maecenas et posuere lorem. Fusce sed massa sit amet elit viverra hendrerit.'},
        {id: 2, title: 'Zuluk bilan davolash', text: 'Girudoterapiya (lot. hirūdō — «zuluk» va qad. yun. θεραπεία — «davolash») — ma’lum kasalliklarni dorivor zuluklar (Hirudo medicinalis) yordamida davolash usuli. Fizioterapevtik muolaja, muqobil tibbiyotga oid sanaladi. Bunday zuluklar ushbu kichik sinf chuvchalchanglariga oid yagona tur hisoblanadi, qolganlari shifobaxsh ta’sir ko’rsatmaydi.'},
        {id: 3, title: 'Tabiiy dori vositalari', text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla ac metus placerat, pellentesque enim ac, rhoncus lectus. Maecenas et posuere lorem. Fusce sed massa sit amet elit viverra hendrerit.'},
      ]
    }
  },
  components: {
    Button
  }
}

</script>

<style>

</style>