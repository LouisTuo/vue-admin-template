<template>
    
    <div>
      <!-- <div>Hello World </div> -->
      <my-additon></my-additon>
       <my-subtraction></my-subtraction>
    </div>

</template>
<script>
// 引入组件
import additon from '../../components/demo/addition.vue';
import subtraction from '../../components/demo/subtraction.vue';


export default {
    data() {
        return{};
    },
    // 注册组件
    components:{
        "my-subtraction":subtraction,
        "my-additon":additon
    }

}
</script>