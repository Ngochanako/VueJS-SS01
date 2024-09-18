<template>
  <div>
    <table>
        <thead>
            <tr>
                <th>STT</th>
                <th>Họ và tên</th>
                <th>Ngày sinh</th>
                <th>Giới tính</th>
                <th>Địa chỉ</th>
                <th>Hành động</th>
            </tr>
        </thead>
        <tbody>
            <tr v-for="(item, index) in list" :key="item.id">
                <td>{{ index+1 }}</td>
                <td>{{ item.name }}</td>
                <td>{{ item.dateOfBirth }}</td>
                <td>{{ item.gender }}</td>
                <td>{{ item.address }}</td>
                <td style="display: flex;gap:10px">
                    <button>Sửa</button>
                    <button>Xóa</button>
                </td>
            </tr>
        </tbody>
    </table>
  </div>
</template>

<script setup>
const list=[
    {
        id:'1',
        name:'John',
        dateOfBirth:'20/12/2019',
        gender:'nam',
        address:"HN"
    },
    {
        id:'2',
        name:'Elly',
        dateOfBirth:'20/12/2016',
        gender:'nữ',
        address:"HN"
    }
]
</script>

<style>
table,th,td{
    border:1px solid grey;
    border-collapse: collapse;
    padding: 10px;
}
</style>