<!-- src/routes/about.svelte -->
<svelte:head>
	<title>About</title>
</svelte:head>

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
      <h2 class="about-title">I'm David Adeneye</h2>
      <div class="about-subtitle">
          <p>
              Software Engineer and a Technical Writer with a solid background in Computer Science, 
              I’m passionate about making the web accessible for everyone. 
          </p>
          <p>
            Creating magic daily on the internet. View my Projects, Article, Resume, Contact Me, or Send me 
             an email at adeneyeabiodun@gmail.com 
          </p>
          <div class="scroll-button animate-scroll" tabindex="0">
            <a href="/about">See More About Me</a><div class="arrow">→</div>
          </div>
          <p></p>
      </div>
    </div>
  </section>

<style>
    nav {
        position: sticky;
        top: 0;
        left: 0;
        right: 0;
        background-color:silver;
        transition-timing-function: top 500ms;
    }

    nav .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
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
        color: black
        
    }
</style>