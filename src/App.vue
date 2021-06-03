<template>
  <div id="app">
    <link
      href="https://fonts.googleapis.com/css?family=Acme"
      rel="stylesheet"
    />
    <div id="header">
      <div id="title">
        <Title />
      </div>
    </div>
    <div id="main">
      <div id="todo">
        <h2>Todo Box</h2>
        <TodoBox />
      </div>
      <div class="margin"></div>
      <div id="report">
        <h2>Report Box</h2>
        <ReportBox />
      </div>
    </div>
    <aside>
      <Aside />
    </aside>
  </div>
</template>

<script>
import Title from "@/components/Title.vue"
import Aside from "@/components/Aside.vue"
import TodoBox from "@/components/TodoBox.vue"
import ReportBox from "@/components/ReportBox.vue"
export default {
  components: {
    Title,
    Aside,
    TodoBox,
    ReportBox,
  },
}
</script>

<style>
#app {
  font-family: acme;
}
#main {
  margin-right: 150px;
  display: flex;
  justify-content: flex-end;
}
.margin {
  width: 75px;
}
#todo,
#report {
  text-align: center;
  width: 450px;
}
</style>
