<template>
  <div>
    <div class="img-container">
      <img src="https://images.unsplash.com/photo-1608408843596-b3119736057c?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=2695&q=80" alt="" style="width: 100%;">
      <h1 class="center-title">Diary of Sam</h1>
    </div>
    <latest/>
    <travel/>
    </div>
</template>

<script>
import latest from "~/components/latest";
import travel from "~/components/travel";

export default {
  components: {
    latest,
    travel
  }
}
</script>
<style>
  .img-container{
    position: relative;
  }
  .center-title{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-family: Dancing Script;
    color: #EBE8E8;
  }
</style>
