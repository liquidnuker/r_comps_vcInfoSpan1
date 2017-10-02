<template>
  <div>
  
  <!-- vcInfoSpan101 -->
  <h2 class="item-id">vcInfoSpan101</h2>
  <div class="row">
    <div class="col-sm-3">39</div>
    <div class="col-sm-9">
      <vcInfoSpan101 />
    </div>
  </div>

  <!-- vcInfoSpan102 -->
  <h2 class="item-id">vcInfoSpan102</h2>
  <div class="row">
    <div class="col-sm-3">39</div>
    <div class="col-sm-9">
      <vcInfoSpan102 />
    </div>
  </div>

  <!-- vcInfoSpan103 -->
  <h2 class="item-id">vcInfoSpan103</h2>
  <div class="row">
    <div class="col-sm-3">39</div>
    <div class="col-sm-9">
      <vcInfoSpan103 />
    </div>
  </div>

  </div>
</template>
<script>
const vcInfoSpan101 = () => import ('./vcInfoSpan101.vue');
const vcInfoSpan102 = () => import ('./vcInfoSpan102.vue');
const vcInfoSpan103 = () => import ('./vcInfoSpan103.vue');
  export default {
    data () {
      return {    
      }
    },
    components: {
      vcInfoSpan101: vcInfoSpan101,
      vcInfoSpan102: vcInfoSpan102,
      vcInfoSpan103: vcInfoSpan103
    },
    mounted: function () {
      // console.log("Home.vue mounted");
    }
  }
</script>