<template>
    <div>
        <h3>Fcuking fucked!</h3>
        <div class="todos" v-for="todo in todos" :key="todo.id">id:{{todo.id}}   title:{{todo.title}}</div>
    </div>
</template>

<script>
export default {
    name:"ToDos",
    computed: {
      todos(){
            return this.$store.state.todos.todos;
      }
    },
}
</script>


<style lang="">
    
</style>