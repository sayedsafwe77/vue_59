<template>
    <h1>hello from profile page</h1>
    <!-- <HelloWorld msg="hello mohamed salah"/> -->
    <Category user_name='mohamed salah'/>
    <Category user_name='sayed safwet'/>
</template>
<script>
import HelloWorld from '@/components/HelloWorld.vue'
import Category from '@/components/Category.vue'
export default {
      name: 'Profile',
      components:{
          HelloWorld,
          Category
      }
}
</script>