<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<script setup></script>
<style>
* {
  font-family: 'Open Sans', 'Helvetica Neue', sans-serif;
  color: #292929;
}
body {
  background-color: #f9f9f9;
  margin: 0;
  padding: 0;
}
.container {
  display: flex;
  flex-direction: column;
  width: 60%;
  margin: auto;
  padding: 20px 0px;
}
h1 {
  font-weight: 300;
  font-family: Lora;
}
.rounded-full {
  border-radius: 5%;
}
code {
  background-color: #27305f;
  padding: 10px 4px;
  border-radius: 4px;
  font-family: 'Courier New', Courier, monospace;
  width: 100%;
  display: inline-block;
  color: white;
}
a {
  color: gray;
}
img {
  max-width: 100%;
  height: auto;
  background-color: #f0f0f0;
  border-radius: 2%;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s;
}
</style>
