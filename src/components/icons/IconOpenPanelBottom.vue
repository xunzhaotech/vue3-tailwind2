<template>
<svg :height="height" :width="width" viewBox="0 0 32 32" class="fill-current">
 <path d="M28,4H4A2,2,0,0,0,2,6V26a2,2,0,0,0,2,2H28a2,2,0,0,0,2-2V6A2,2,0,0,0,28,4Zm0,2V18H4V6ZM4,26V20H28v6Z"/></svg>
</template>
<script> 
export default
{ name:"IconOpenPanelBottom", 
 props:{ height: { type:  Number, default: 20, }, width: { type:  Number, default: 20, }, } 
}
</script>