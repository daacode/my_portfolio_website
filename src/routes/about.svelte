<!-- src/routes/about.svelte -->
<svelte:head>
	<title>About</title>
</svelte:head>
<div class="main_container">
    <nav>
        <div class="container">
            <a href="/" class="nav-logo" title="Back to Homepage">David Adeneye</a>
            <div class="nav-links">
                <a href="/blog" class="link">Blog</a>
                <a href="/projects" class="link">Projects</a>
                <a href="/resume" class="link">Resume</a>
                <a href="/contact" class="link">Contact</a>
            </div>
        </div>
    </nav>
    
    
    <section id="about">
        <div class="container inner-container">
          <h2 class="about-title">I'm David Adeneye👋</h2>
          <div class="about-subtitle">
              <p>
                  Software Engineer and a Technical Writer with a solid background in Computer Science, 
                  I’m passionate about making the web accessible for everyone. When I’m not solving problems, 
                  I love to create technical content for engineers and tech startups across the globe. 
              </p>
              <p>
                Creating magic daily on the internet. View my <span class="info-text">Projects</span>, <span class="info-text">Article</span>, <span class="info-text">Resume</span>, <span class="info-text">Contact Me</span>, or Send me 
                 an email at <span class="info-text">adeneyeabiodun@gmail.com</span> 
              </p>
              <div class="scroll-button animate-scroll" tabindex="0">
                <a href="/about">See More About Me</a><div class="arrow">→</div>
              </div>
              <p></p>
          </div>
        </div>
      </section>
</div>

<style>
    .main_container {
        margin: 0 80px 0 80px;
    }

    nav {
        position: sticky;
        top: 0;
        left: 0;
        right: 0;
        padding-top: 2rem;
        padding-bottom: 2rem;
        transition-timing-function: top 500ms;
    }

    nav .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin: 0 80px 0 0px;
    }

    .nav-links {
        display: flex;
        margin: -1em 0;
        flex: 1 0 auto;
        justify-content: flex-end;
        align-items: center;
    }

    .nav-links .link {
        position: relative;
        margin: 1em;
        color: black;
        font-size: 0.85rem;
        letter-spacing: 1px;
    }

    .nav-links .link:hover:before {
        max-width: 10rem;
    }

    .nav-logo {
        position: relative;
        line-height: 1;
        font-size: 1.1rem
    }


    .about-title {
        font-size: 4.2rem;
        font-weight: bold;
        color: black;
        margin-top: 11rem;
    }

    .about-subtitle {
        margin-top: -2rem;
    }

    .about-subtitle >p {
        width: 65%;
        font-weight: normal;
        color: rgb(133, 131, 131);
        font-size: 1rem;
        line-height: 2rem;
    }

    .info-text {
        background-color: rgba(180, 180, 180, 0.74);
        padding: 6px 6px 6px 6px;
        border-radius: 5px;
    }

    .scroll-button { 
        margin-top: 3rem;
        border: none;
        outline: none;
        cursor: pointer;
        display: flex;
        transition: opacity 250ms;
    }

  .scroll-button .arrow {
        margin-left: 0.50rem;
    }
</style>