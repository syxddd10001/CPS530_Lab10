<script setup lang="ts">

</script>

<template>
  <div style="width: 100vh; height: 100vh;" class="top">
    <h1>Lab 10 Problem 3 <h2>My Experience using Vue</h2> </h1>
    <p>In order to get started with Vue, I first had to install Node.js for Windows.</p>
    <p>Then I installed npm using Powershell by typing in <strong>npm install -g npm</strong></p>
    <p>After that, I installed vue/cli using the <strong>npm install -g @vue/cli</strong></p>
    <br></br>
    <p>Everything required to start a Vue project has been installed. <strong>npm install -g @vue/cli</strong></p>
    <p>I then created a Vue project using Vite using <strong>npm create vite@latest lab10problem3 --template vue</strong></p>
    <p>It gave my options to select what type of project I wanted to create, I selected Vue. And then asked me what language I wanted to use: JavaScript or TypeScript.
    I chose TypeScript because I like static type checking.</p>    
    
    <p>It created a boilerplate Vue TypeScript project for me.
    Then I replaced the boilerplate content with my content in App.vue. 
    I deleted HelloWorld.vue which was an existing component and replaced it with the content I want (what I am typing right now)</p>
    
    <p>I also added some CSS styling of my own to structure and style the page</p>

    <p>It was mostly a smooth experience for me getting started / setting up the Vue project. It was fun and I didn't face any
    major difficulties.</p>
    
    
  </div>

</template>

<style scoped>
  .top{
    display: flex;
    flex-direction: column;
    justify-items: flex-start;
    align-content: flex-start;
  }

</style>
