<template> 
<div>{{text}}</div>
</template>


<script>
export default {
    data(){
        return {
            text: 'test'
        }
    },
    mounted(){
        console.log('mounted test')
    },
    
}
</script>