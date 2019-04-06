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

section {
  display: flex;
  flex-direction: column;
  padding: 12px;
  margin: 12px;
}

section p,
details {
  margin: 6px;
  padding: 6px;
  line-height: 150%;
}

/* Full-width inputs */
input[type="text"],
input[type="password"] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
}

/* Set a style for all buttons */
button {
  background-color: #4caf50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
}

/* Add a hover effect for buttons */
button:hover {
  opacity: 0.8;
}

/* Extra style for the cancel button (red) */
.cancelbtn {
  width: auto;
  padding: 10px 18px;
  background-color: #f44336;
}

/* Add padding to containers */
.container {
  padding: 16px;
}

/* The "Forgot password" text */
span.psw {
  float: right;
  padding-top: 16px;
}
</style>