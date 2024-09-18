<template>
  <div>
    <h4>Họ và tên:{{ formatName(user) }}</h4>
  </div>
</template>

<script setup>
  const user={
    firstName:'Nguyễn Văn',
    lastName:"A"
  }
  const formatName=(user)=>{
    return `${user.firstName} ${user.lastName}`
  }
</script>

<style>

</style>