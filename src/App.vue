<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
body {
  background-color: #6877f5;
  width: 100vw;
}

#app {
  font-family: "roboto", sans-serif;
  text-align: center;
  color: #000000;

  p{
    text-decoration: underline;
  }

  .profile_pic {
    border-radius: 100%;
    margin-bottom: 12%;
  }

   .head{
        img{
            float:left;
        }
        :first-child{
            width: 70%;
            margin-right:4%;
        }

        :nth-child(2){
            width: 20%;
        }
    }
}
</style>
