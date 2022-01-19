<!-- src/routes/about.svelte -->
<svelte:head>
	<title>About</title>
</svelte:head>

<div class="main_container">
    <section>
        <div class="inner-container">
          <h2 class="about-title">I'm David Adeneye👋</h2>
          <div class="about-subtitle">
              <p>
                Software Engineer and a Technical Writer with a solid background in Computer Science, 
                I’m passionate about making the web accessible for everyone. 
                I design and develop visually compelling applications with user-friendly interaction that 
                drive business growth and improve user experience. When I’m not solving problems, 
                I love to create technical content for engineers and tech startups across the globe.
 
              </p>
              <p>
                Creating magic daily on the internet. You can send me 
                 an email at <span class="info-text">adeneyeabiodun@gmail.com</span> 
              </p>
          </div>
        </div>
      </section>
</div>

<style>
    .main_container {
        margin: 0 80px 0 65px;
    }

    .about-title {
        font-size: 4.2rem;
        font-weight: bold;
        margin-top: 11rem;
    }

    .about-subtitle {
        margin-top: -2rem;
    }

    .about-subtitle >p {
        width: 60%;
        font-weight: normal;
        font-size: 1rem;
        line-height: 2rem;
    }

    .info-text {
        font-style: italic;
        font-weight: bold;
    }

</style>