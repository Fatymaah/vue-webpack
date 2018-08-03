<template>
  <div class="container">
    <input type="search" id="city-search" placeholder="Search City">


   
    

  </div>
</template>

<script>
export default {
  data: function() {
    return {
      title: 'My First App',
      click: 0 ,
      newTask:'SAMPLE',
      
      tasks:[
      
      ]
    }
  },
  methods:{
    addTask(){
      this.tasks.unshift(this.newTask);
      this.newTask = '';
    
    }
  }
}
</script>
