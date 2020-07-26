<template>
  <div>
    <slot></slot>
  </div>
</template>

<script>
export default {
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  div{
    border:1px rgb(155, 155, 155) solid;
    box-shadow:1px 1px 5px rgb(0, 0, 0);
    padding:30px;
    background-image: linear-gradient(to left, #aa3333 , #cf6e7b);
    margin:30px auto;
    text-align:center;
  }

  div:hover{
/* transition: 2s ease-in; */
     border:1px rgb(155, 155, 155) solid;
    box-shadow:1px 1px 20px rgb(0, 0, 0);
   background-image: linear-gradient(to left, #cf6e7b , #aa3333);
    padding:30px;
    margin:30px auto;
    text-align:center;
  }
</style>
