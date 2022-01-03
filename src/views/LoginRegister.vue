<template>
  <div id="sb">
    <div>
      <img src="../assets/logo.jpg" />
      <button>手机号登录</button>
      <button>注册</button>
    </div>
    <div>
      <van-divider>其他登录方式</van-divider>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
#sb {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  height: 100vh;
  img {
    width: 20vw;
    margin: 10vw auto;
  }
  button {
    display: inline-block;
    width: 90vw;
    margin: 1vh auto;
    height: 5vh;
    border: 1px solid red;
    border-radius: 25px;
    background-color: #fff;
    color: red;
  }
  div:nth-of-type(2){
    width: 50vw;
    font-size: 12px;
  }
}
</style>
>
