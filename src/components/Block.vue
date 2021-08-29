<template>
  <div class="block">
      Click Me...!
      <p>{{delay}}</p>
  </div>
</template>

<script>
export default {
  props: ['delay']
}
</script>

<style>
    .block {
        width: 400px;
        border-radius: 20px;
        color: white;
        background: #0faf87;
        text-align: center;
        padding: 100px 0;
        margin: 40px auto;
    }
</style>
