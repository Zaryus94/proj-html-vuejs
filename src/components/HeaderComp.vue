<template>
  <div class="header">
    <hr />
    <h4>Avada & Associates legal team announce deal to open up oil & gas</h4>
    <button class="SocialIcon">
      <i class="fa-brands fa-facebook-square"></i>
    </button>
    <button class="SocialIcon">
      <i class="fa-brands fa-twitter-square"></i>
    </button>
    <button class="SocialIcon">
      <i class="fa-brands fa-instagram-square"></i>
    </button>
    <button class="SocialIcon">
      <i class="fa-brands fa-youtube-square"></i>
    </button>

    <!-- IMG + MIRRORED IMG (BANNER) -->

    <img
      id="HeaderImg"
      src="..\src\assets\video_law_home_preview.jpg"
      alt="HeaderImg"
    />
    <img
      id="HeaderImg"
      src="..\src\assets\video_law_home_previewR.jpg"
      alt="HeaderImg"
    />
  </div>
</template>


<script>
</script>


<style scoped lang="scss">
hr {
  margin: 0 0 1%;
  border: 3px solid #54a096;
}
h4 {
  font-weight: normal;
  margin: 0 40% 2% 10%;
  display: inline-block;
}
button {
  background: transparent;
  border: 1px solid transparent;
}
button:hover {
  font-size: 31px;
}
.SocialIcon {
  padding: 10px;
  font-size: 30px;
  color: #54a096;
}
#HeaderImg {
  width: 50%;
  height: 50%;
}
</style>
