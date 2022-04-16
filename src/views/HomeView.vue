<template>
  <router-link :to="{name: 'ItemDetail', params: {itemId: id}}">ItemDetail.vueへ</router-link>
</template>
<script>
export default {
  data(){
    return {
      id: 'a84ddc62-e70d-c5bc-3be2-bde775cbd6b6'
    }
  }
}
</script>