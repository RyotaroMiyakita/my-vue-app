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
    <table>
      <tr>
        <td id="task-td">
          <input type="text" />
        </td>
        <td id="time-td">
          <input list="NumberTime" />
          <datalist id="NumberTime">
            <option value="5回"></option>
            <option value="6回"></option>
            <option value="7回"></option>
            <option value="8回"></option>
            <option value="9回"></option>
            <option value="10回"></option>
            <option value="12回"></option>
            <option value="15回"></option>
            <option value="20回"></option>
          </datalist>
        </td>
        <td id="set-td">
          <input list="SetCount" />
          <datalist id="SetCount">
            <option value="1セット"></option>
            <option value="2セット"></option>
            <option value="3セット"></option>
            <option value="4セット"></option>
            <option value="5セット"></option>
            <option value="6セット"></option>
          </datalist>
        </td>
      </tr>
    </table>
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
input {
  border-radius: 3px;
  height: 30px;
}
#task-td input {
  width: 185px;
}
#time-td input {
  width: 90px;
}
#set-td input {
  width: 90px;
}
</style>
