<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

body {
  background-color: #fef1d8;
}

.container {
  padding-right: 50px;
  padding-left: 50px;
  margin-right: auto;
  margin-left: auto;
}

.navigation {
  justify-content: center;
  display: flex;
  align-items: center;
  text-align: center;
  margin-top: 7vh;
  position: relative;
  z-index: 1000;
}

.content-nav {
  /* display: grid;
  grid-template-columns: repeat(12, 1fr); */
  display: flex;
  justify-content: center;
  align-items: center;
}

.nav {
  height: 60px;
  width: 500px;
  background-color: #fef1d8;
  border-radius: 100px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding-left: 15px;
  padding-right: 15px;
}

.number-nav-current {
  height: 30px;
  width: 30px;
  border-radius: 100px;
  background-color: #ff8a00;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.number-nav {
  height: 30px;
  width: 30px;
  border-radius: 100px;
  background-color: #ffe3b7;
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.content {
  margin-top: -25px;
  height: 70vh;
  width: 83vw;
  background-color: white;
  padding: 30px;
  padding-left: 50px;
  padding-right: 50px;
}

.row {
  display: flex;
}

input[type=email],[type=number],[type=text] {
  width: 350px;
  height: 60px;
  padding: 12px 20px;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  -webkit-box-shadow: 9px 11px 12px -7px rgba(0, 0, 0, 0.17);
  -moz-box-shadow: 9px 11px 12px -7px rgba(0, 0, 0, 0.17);
  box-shadow: 9px 11px 12px -7px rgba(0, 0, 0, 0.17);
  font-size: 15px;
  font-weight: bold;
}

input::-webkit-input-placeholder {
  color: rgb(192, 190, 187);
  font-size: 15px;
  font-weight: bold;
}

input[type=checkbox] {
  width: 100px;
  font-size: 15px;
  font-weight: bold;
  box-shadow: none;
  padding: 0;
}

.input {
  margin-bottom: 10px;
}
</style>
