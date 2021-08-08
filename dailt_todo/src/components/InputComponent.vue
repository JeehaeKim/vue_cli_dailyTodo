<template>
  <div id="input">
      <div class="input-wrap">
          <input type="text" name="input_txt" id="inputTxt" value="" placeholder="오늘의 할일은 입력하세요">
          <button class="add-btn">Add</button>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
    #input{height: 70px;padding: 10px 0;margin-top: 15px;}
    #input .input-wrap{width: 90%;height: 50px;padding-right: 80px;position: relative;margin: 0 auto;}
    #input .input-wrap input{width: 100%;height: 50px;padding: 0 15px;border-radius: 10px 0 0 10px;}
    #input .input-wrap button{width: 80px;height: 50px;background-color: #444;color: #fff;position: absolute;top: 0;right: 0;border-radius: 0 10px 10px 0;}
</style>