<template>
<div id="app">
  <div class="header">
    <div id="spider-icon">
      <router-link to="/">
        <img src="/spider-icon.png" width="50px" height="50px" />
      </router-link>
    </div>
    <div class="title">
      <router-link to="/">

        <h1>Upload Some Bugs!</h1>
      </router-link>
    </div>
    <div id="upload-button">
      <router-link to="/admin"><img src="/upload-icon.png" width="50px" /></router-link>
    </div>
  </div>
  <div class="content">
    <router-view />
  </div>
  <a href="https://github.com/roundpigeon/creativeproject4" id="github">Github</a>
</div>
</template>

<style>
html {
  box-sizing: border-box;
}

body {
  font-family: 'Montserrat', sans-serif;
  font-size: 16px;
  background: #fff;
  padding: 0px;
  margin: 0px;
}

/* Header */
.header {
  display: flex;
  /* padding: 10px 100px 0px 100px; */
  background-color: #2bcc6b;
}

.title {
  margin: 5px auto 0 0;
  text-align: center;
}

.title h1 {
  font-size: 2.5rem;
}

.content {
  padding: 20px 100px;
  min-height: 500px;
}

a, a:visited {
  text-decoration: none;
  color: black;
}

#upload-button {
  display: flex;
  align-items: center;
  margin-right: 3rem;
}

#spider-icon {
  display: flex;
  align-items: center;
  margin-left: auto;
  margin-right: 1em;
}

#github {
  margin-left: 6.4em;
  text-decoration: underline;
}
</style>
