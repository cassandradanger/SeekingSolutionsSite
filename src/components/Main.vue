<template>
  <div class="main">
    <img class="marv" src="../assets/marv.png"/>
    <div class="description">
        <h3>Marv Siekman, CFP<span class="r">®</span></h3>
        <p>Business Planning Consultant</p>
        <p>320.894.5015</p>
        <p><a href="mailto:marv@seekingsolutions.net">marv@seekingsolutions.net</a></p>
        <p><a href="http://www.ascentmn.com/" target="_blank">www.ascentmn.com</a></p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'main'
}
</script>

<style scoped>

  .main{
    margin-top: 200px;
    text-align: center;
  }

  .description{
    display: inline-block;
    text-align: left;
    margin: -10px 0 10px 20px;
    vertical-align: top;
  }

  h3{
    margin-top: 10px;
  }

  .marv{
    height: 170px;
    display: inline-block;
  }

  .r{
    font-size: 8pt;
    vertical-align: top;
  }

</style>
