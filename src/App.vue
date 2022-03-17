<script setup>

</script>

<style>
  @import url('./assets/css/style.css');
  @import url('./assets/css/pos.css');
  
  @import url('https://unpkg.com/emoji.css/dist/emoji.min.css');
</style>

<template>
  <div id="app">
    <div class="header">
      <h1 class="nav-title">Webkit</h1>
      <nav class="push" id="navbar">
        <ul class="horizontal-flex">
          <li class="nav-li"><a class="nav-links" href="#" onclick="alert('Hello, world!')">Hello, world!</a></li>
          <li class="nav-li"><a class="nav-links" href="#" onclick="alert('Loerm ipsum')">Lorem ipsum</a></li>
        </ul>
      </nav>
    </div>
    <div class="content">
      <h1 class="big-title centred-elem">Starter Webkit <span class="ec ec-closed-book"></span></h1>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {

      }
    }
  }
</script>