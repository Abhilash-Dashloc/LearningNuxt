<template>
    <button @click="Increment">Increment</button>
    <div>{{ count }}</div>
    <button @click="Decrement">Decrement</button>
</template> 
<script setup> 
const count = ref(0);  

const Increment =()=>{
  count.value++;
}
const Decrement =()=>{
  count.value--;
}
</script>
