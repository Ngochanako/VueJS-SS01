<template>
    <div>
        <h2>Danh sách kết quả</h2>
        <ul>
            <li>{{a}}+{{b}}={{ a+b }}</li>
            <li>{{a}}-{{b}}={{ a-b }}</li>
            <li>{{a}}*{{b}}={{ a*b }}</li>
            <li>{{a}}/{{b}}={{ a/b }}</li>
        </ul>
    </div>
</template>

<script setup>
let a=10;
let b=10;
</script>

<style>

</style>