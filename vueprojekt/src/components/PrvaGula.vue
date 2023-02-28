<template>
    <div class="row">
      <div>
        <p>Milujem gule a goth cajky</p>
      </div>
      <div id="gula1"></div>
      <div id="eye1"></div>
      <div id="eye2"></div>
      <div id="gula2"></div>
      <div id="button1"></div>
      <div id="button2"></div>
      <div id="button3"></div>

      <div id="gula3"></div>

    </div>
</template>

<script>
export default {
  name: 'PrvaGula',
  props: {
    msg: String
  }}
</script>

<style scoped>
    #gula1{
        height: 125px;
        width: 125px;
        background-color: rgb(183, 218, 255);
        border-radius: 50%;
    }
    #gula2{
        height: 200px;
        width: 200px;
        background-color: rgb(183, 218, 255);
        border-radius: 50%;
    }
    #gula3{
        height: 275px;
        width: 275px;
        background-color: rgb(183, 218, 255);
        border-radius: 50%;
    }
    #button1{
        height: 25px;
        width: 25px;
        background-color: rgb(0, 0, 0);
        border-radius: 50%;
        position: absolute;
        margin-top: 25px;
    }
    #button2{
        height: 25px;
        width: 25px;
        background-color: rgb(0, 0, 0);
        border-radius: 50%;
        position: absolute;
        margin-bottom: 80px;
    }
    #button3{
        height: 25px;
        width: 25px;
        background-color: rgb(0, 0, 0);
        border-radius: 50%;
        position: absolute;
        margin-bottom: 180px;
    }
    #eye1{
        height: 15px;
        width: 15px;
        background-color: rgb(5, 0, 70);
        border-radius: 50%;
        position: absolute;
        margin-bottom: 425px;
        margin-right: 40px;
    }
    #eye2{
        height: 15px;
        width: 15px;
        background-color: rgb(5, 0, 70);
        border-radius: 50%;
        position: absolute;
        margin-bottom: 425px;
        margin-left: 40px;
    }

    .row {
      display: flex;
      justify-content: center;
      flex-direction: column;
      align-items: center;
    }
</style>