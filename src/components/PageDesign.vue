<template id="container">
  <div class="allDesign">
    <div class="leftbar">Deneme</div>
    <div class="storyandposts">
      <div class="stories">Deneme</div>
      <div class="posts">Deneme</div>
    </div>
    <div class="rightbar">Deneme</div>
  </div>
</template>
<style scoped>
.allDesign {
  width: 100%;
  display: inline-flex;
  justify-content: space-between;
}
.leftbar {
  width: 18%;
  background-color: aqua;
  height: 100vh;
}
.storyandposts {
  width: 45%;
  height: 88vh;
}
.stories {
  background-color: purple;
  width: 100%;
  height: 15vh;
  justify-content: center;
  display: flex;
  align-items: center;
  border-radius: 10px;
}
.posts {
  background-color: purple;
  width: 100%;
  height: 80vh;
  justify-content: center;
  display: flex;
  align-items: center;
  border-radius: 10px;
  margin-top: 25px;
}
.rightbar {
  width: 18%;
  height: 40vh;
  background-color: red;
}
.container {
  background-color: antiquewhite;
}
</style>
