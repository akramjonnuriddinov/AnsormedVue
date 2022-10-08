<template>
  <footer class="bg-[#222] text-white">
    <div class="container mx-auto px-5 py-6 flex justify-between items-center">
      <a class="hover:opacity-80 transition-all" href="#">
        <img src="../assets/img/logo-footer.png" alt="">
      </a>
      <nav>
      <ul class="flex items-center">
        <li class="px-4" v-for="item in items">
          <a class="text-sm font-bold uppercase transition-all text-white hover:text-red-400" href="#">{{item.text}}</a>
        </li>
      </ul>
    </nav>
    </div>
  </footer>
</template>

<script>

export default {
  data() {
    return {
      items: [
        {id: 0, text: 'xizmatlar'},
        {id: 2, text: 'dorilar'},
        {id: 3, text: 'asal'},
        {id: 4, text: 'kontaktlar'},
        {id: 5, text: 'blog'}
      ]
    }
  }
}
</script>