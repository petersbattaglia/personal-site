<template>
  <div>
    <table style="padding: 0; margin: 0; border: 0; border-spacing: 0">
      <tr>
        <td>
          <img class="photo photo-container" src="../../img/profile_pic.jpg" />
        </td>
        <td style="vertical-align: top;">
          <div class="right-panel">
            <table>
              <tr>
                <td>
	          <div class="bio">
	            <h1>Peter Battaglia</h1>
                    <!--<h2>Software Engineering Leader</h2>-->
	      	    <h3>Seattle, Washington</h3>
              	    <p>I am a deeply technical engineering leader with a passion for motivating teams to deliver 
	            outsized results towards product goals. I have a demonstrated track record of immersing
		    myself into uncharted technical territories; creating product areas that derive 
		    customer happiness and revenue growth.</p>
		    
		    <p>
		    After 3 years in the Cybersecurity space with Versive/eSentire, I have begun a new chapter in 
		    the Core Platform team of <a href="https://www.qualtrics.com/">Qualtrics</a> (as of September 2019).
		    </p>

		    <p>
		    Feel free to connect with me via social media! 
		    </p>
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
	</td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  name: 'Main',
}
</script>

<style scoped>
.photo-container {
    height: 100vh;
display: table-cell;
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
    padding: 30px;
    min-width: 100px;
}

.right-panel {
    //width: auto;
display: table-cell;
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
