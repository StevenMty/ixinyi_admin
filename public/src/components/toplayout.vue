<template>
  <div>
    <div class="top-nav">
      <slot name="top_menu"></slot>
    </div>
    <div class="main-container" >
      <slot name="top_container"></slot>
    </div>
    <div class="footer-container">
      <slot name="top_footer"></slot>
    </div>
  </div>  
</template>
<script>
</script>
<style type="text/css">
  .main-container .view{
    text-align: center;
    background: url('http://blog.xinsay.cn/bk.png');
    padding-bottom: 20px;
  }
  .top-nav{
    margin-bottom: 0px;
  }
  .footer-container{
    position: absolute;
    width: 100%;
  }
</style>