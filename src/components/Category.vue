<template>
    <h1>hello {{ user_name }}</h1>    
</template>
<script>
export default {
    name: 'Category',
    props:{
        user_name:String
    }
}
</script>