<template>
  <div class="box">
    <div class="box-head">
      <div class="task">
        <h3>task</h3>
      </div>
      <div class="time">
        <h3>Number of Time</h3>
      </div>
      <div class="set">
        <h3>Set</h3>
      </div>
    </div>
  </div>
</template>
<script>
export default {}
</script>
<style scoped>
.box {
  width: 450px;
  height: 400px;
  border: 2px black solid;
}
.box-head {
  display: flex;
  justify-content: flex-start;
}
.task {
  width: 200px;
}
.time {
  width: 100px;
}
.time h3 {
  font-size: 15px;
  margin-top: 3px;
}
.set {
  width: 100px;
}
.task h3 {
  margin: 0;
}
.set h3 {
  margin: 0;
}
</style>
