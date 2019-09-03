<template>
  <div>
    <img class="photo photo-container" src="../../img/profile_pic.jpg" />
    <div class="right-panel">
      <table>
        <tr>
          <td>
	    <div class="bio">
	      <h1>Peter Battaglia</h1>
              <h2>Software Engineering Leader</h2>
	      <h3>Seattle, Washington</h3>
              <p>I am a deeply technical engineering leader with a passion for motivating teams to deliver outsized results towards product goals. I have a demonstrated track record of immersing myself into uncharted technical territories; creating product areas that lead to customer happiness and revenue growth.</p>
            </div> 
          </td>
          <td>
	    <div style="margin-top: 100px;">
              <a href="https://www.linkedin.com/in/petersbattaglia/" target="_blank">
                <img class="contact-icon" src="../../img/linked_in.png" />
              </a>
              <br /><br />
              <a href="https://github.com/petersbattaglia" target="_blank">
                <img class="contact-icon" src="../../img/github.svg" />
              </a>
	      <br /><br />
              <a href="https://facebook.com/petersbattaglia" target="_blank">
                <img class="contact-icon" src="../../img/facebook.jpeg" />
              </a>
	      <br /><br />
              <a href="mailto:petersbattaglia@outlook.com" target="_blank">
                <img class="contact-icon" src="../../img/mail.png" />
              </a>
            </div>
          </td>
        </tr>
      </table>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Main',
}
</script>

<style scoped>
.photo-container {
    max-height: 100vh;
    width: 45vw;
    float: left;
}

h1 {
    margin: 0;
}

h2 {
    margin: 0;
}

h3 {
    margin: 0;
}

.bio {
    text-align: left;
    margin-right: 20px;
}

.right-panel {
    float: right;
    width: 50vw;
    min-width: 25%;
    text-align: right;
    margin-top: 20px;
    margin-right: 30px;
}

.contact-icon {
    height: 64px;
    width: 64px;
}

.photo {
    opacity: 0.5;
}

</style>
