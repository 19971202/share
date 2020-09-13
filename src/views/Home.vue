<template>
  <div class="flex">
    <div class="left">
      <SideNavi />
    </div>
    <div class="right">
      <div class="title">
        <p>ホーム</p>
      </div>
      <Message />
    </div>
  </div>
</template>

<script>
import SideNavi from "../components/SideNavi";
import Message from "../components/Message";
export default {
  components: {
    SideNavi,
    Message
  }
};
</script>

<style scoped>
.left {
  width: 22%;
  height: 100vh;
}

.flex {
  display: flex;
}

.right {
  width: 78%;
  height: 100vh;
}

.title p {
  font-size: 20px;
  font-weight: bold;
}

.title {
  border-bottom: 1px solid white;
  border-left: 1px solid white;
  padding: 15px;
}
</style>