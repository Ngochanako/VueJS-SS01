<template>
    <div>
        <h2>Thông tin cá nhân</h2>
        <ul>
            <li>Họ và tên:{{ obj.fullName }} </li>
            <li>giới tính:{{ obj.gender }} </li>
            <li>Ngày sinh:{{ obj.dateOfBirth }} </li>
            <li>Email:{{ obj.email }} </li>
            <li>Địa chỉ:{{ obj.address }} </li>
        </ul>
    </div>
</template>

<script setup>
const obj={
    fullName: 'Nguyễn Văn A',
    gender:'Male',
    dateOfBirth:"20/12/2015",
    email:"abc@abc.com",
    address:"HN"
}
</script>

<style>

</style>