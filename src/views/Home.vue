<template>
      <div class="home" >
          <b-header> <b-img :src="require('C:\\Users\\kaouk\\WebstormProjects\\frontendbtw\\src\\assets\\bigwatchpicture.png')"  fluid alt="Responsive Image"> text="Helllo"</b-img> </b-header>
          <div class="left"> NEW TONES OF ELEGANCE </div>
    </div>

</template>

<script>

    export default {
        name: "Home"

    }
</script>

<style scoped>
    .home {
        position: relative;
        text-align: center;
        color: white;

    }
    .left {
        font-family: Neue Helvetica W01,Helvetica,helvetica,arial,"sans-serif";
        position: absolute;
        top: 50px;
        left: 16px;
        font-size: 45px;
        line-height: 1.1667;
        margin-top: -9.9608px;
        margin-bottom: 26.0392px;

    }
h1 {
    font-family: Neue, Helvetica, Arial, sans-serif;
    font-size: medium;
    text-align: left;
    color: white;
}
    header {
        background-color: black;

    }
</style>