<template>
  <div class="TheIndexCountainer">
    <a href="https://motel411.base.shop/" class="TheIndexCountainer_Heading">Motel 411 Tokyo</a>
  </div>
</template>
<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.TheIndexCountainer{
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.TheIndexCountainer_Heading{
  text-decoration: none;
  display: block;
  color: #000000;
  transition: 0.2s;
  font-size: 20px;
}
.TheIndexCountainer_Heading:hover{
  color: #aaaaaa;
}

</style>


