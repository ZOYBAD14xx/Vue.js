<template>
  <div>
      <!-- interpolation -->
    <h1>{{title}}</h1>    
    <h2>{{count}}</h2>
    <button @click="clickAdd">Add</button>
  </div>
</template>
<script>
export default {
  name:"app",
  data() {
    return {
      title:"Number",
      count:0,
    }
  },
  methods: {
    clickAdd(){
      this.count=this.count+1
    }
  },
};
</script>
<style></style>
