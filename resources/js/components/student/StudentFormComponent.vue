<template>
    <div>
       <el-card class="box-card">
         <div slot="header" class="clearfix">
            <el-page-header @back="goBack" :content="'Category - ${scope}'">
            </el-page-header>
    <span>Card name</span>
</el-card>
    </div>
    <div>
        form
    </div>
</template>

<script>
    export default {
        name:'student-form-component',
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
