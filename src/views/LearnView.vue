<template>
  <div class="h-screen bg-red-400">
    <h1 class="font-bold text-2xl">{{}}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return { a: 1 }
  },
  methods: {
    changeNumber(value) {
      return ` ${value} Toman`
    }
  },
  filters:{

  }
}
</script>
