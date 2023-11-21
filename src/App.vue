<script>
export default {
  data() {
    return {}
  },
  methods: {},
}
</script>

<template>
  // title
  <h1>My ToDo App</h1>
  <input type="text" /><button>追加</button><button>完了済みを削除する</button>
  <ul>
    <li>
      <input type="checkbox" checked /><span class="todo-done"
        >todoリスト作ってタスク管理する</span
      >
    </li>
    <li><input type="checkbox" /><span>ヘッダー、フッターコンポーネントを手抜き作成する</span></li>
    <li><input type="checkbox" /><span>pageを作成し、ヘッターからvm.$routerで遷移する</span></li>
  </ul>
</template>

<style>
body {
  background-color: #2a832074;
}

.todo-done {
  text-decoration: line-through;
}
</style>
