<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  /* font-family: 'Oxygen', sans-serif; */
}

h1 {
  font-size: 30px;
}

/* h1,h2,h3,h4,h5,h6 {
  font-family: 'Viga', sans-serif;
} */

header {
  position: sticky;
  top: 0px;
  background-color: lightsteelblue;
  padding: 16px;
  margin: 12;
}

header nav ul {
  list-style-type: none;
}

header nav ul li {
  margin: 6px;
}

footer {
  position: fixed;
  bottom: 0%;
  background-color: lightsteelblue;
  padding: 8px;
  width: 100%;
}

/* used to be home css */

/* used to be user css */
</style>