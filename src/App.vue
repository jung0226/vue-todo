<template>
  <div id="app"></div>
  <TodoHeader></TodoHeader>
  <TodoInput></TodoInput>
  <TodoList></TodoList>
  <TodoFooter></TodoFooter>
</template>
<script>

import TodoHeader from './components/TodoHeader.vue'
import TodoInput from './components/TodoInput.vue'
import TodoList from './components/TodoList.vue'
import TodoFooter from './components/TodoFooter.vue'

export default {
  components:{
    'TodoHeader':TodoHeader,
    'TodoInput':TodoInput,
    'TodoList':TodoList,
    'TodoFooter':TodoFooter,
  }
}
</script>
<style>
  body{
        text-align: center;
        background-color: #f6f6f8;
    }
  input{
      border-style:groove;
      width:200px;
  }
  button{
      border-style:groove;
  }
  .shadov{
      box-shadow:5px 10px 10px rgba(0, 0, 0, 0.03)
  }
</style>