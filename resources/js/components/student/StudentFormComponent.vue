<template>
    <div>
       <el-card class="box-card">
         <div slot="header" class="clearfix">
            <el-page-header @back="goBack" :content="'Category - ${scope}'">
            </el-page-header>
    <span>Card name</span>
        </div>
</el-card>

        form!!
    </div>
</template>

<script>
    export default {
        name:'student-form-component',
        mounted() {
            console.log('Student Form Component mounted')
        }
    }
</script>
