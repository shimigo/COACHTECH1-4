<template>
  <div>
    <h2>ItemDeatil.vue</h2>
    <p>{{ itemId }}</p>
  </div>
</template>

<script>
export default {
  props: ['itemId']
}
</script>