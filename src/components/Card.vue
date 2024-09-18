<template>
  <div>
    <div class="card">
       <div class="header">
           <p style="font-weight: 600;">Image</p>
       </div>
       <div style="margin: 20px;">Title</div>
       <button class="button">Add to Cart</button>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>
.card{
    margin-top: 20px;
    width: 300px;
    height: 300px;
    border-radius: 5px;
    border:1px solid rgb(201, 198, 198);
    display: flex;
    flex-direction: column;
    align-items: center;
    
}
.header{
    width: 100%;
    display: flex;
    height: 150px;
    justify-content: center;
    align-items: center;
    background-color: grey;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
}
.button{
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}
</style>