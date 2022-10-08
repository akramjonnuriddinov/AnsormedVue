<template>
  <div>
    <nav>
      <ul class="flex items-center">
        <li class="px-4" v-for="item in items">
          <a class="text-sm font-bold uppercase transition-all text-slate-800 hover:text-red-400" href="#">{{item.text}}</a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'App',
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

<style>

</style>