<template>
  <div class="main">
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
      <div class="cart">Cart</div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.main{
    display: grid;
   grid-template-columns: auto auto auto auto;
    background-color: orange;
    gap: 10px;
    padding: 10px;
}
.cart{
    display: flex;
    justify-items: center;
    align-items: center;
    background-color: white;
    width: 100px;
    height: 120px;
    
}
</style>