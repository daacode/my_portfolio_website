<!-- src/routes/index.svelte -->
<svelte:head>
	<title>David Adeneye</title>
</svelte:head>

<div class="info">
    <div class="fixed-info animate-background">
      <div class="container info-container">
        <div class="name-container">
          <span class="name animate-name">David Adeneye</span>
        </div>
        <div class="info-text">
          <h1>
            <p class="animate-text-1">School-taught Computer Scientist,</p>
            <p class="text-2">Self-taught Software Engineer</p>
          </h1>
        </div>
        <h2 class="subtitle">
          On a mission to help SMEs across the globe do businesses seamlessly and digitally.
        </h2>
        <div class="scroll-button animate-scroll" tabindex="0">
          <a href="/about">Click Here</a><div class="arrow">→</div>
        </div>
      </div>
    </div>
</div>


<style>
    .info {
        text-align: center;
        position: relative;
        height: 100vh;
    }        

    .info-container {
        height: 100%;
        display:flex;
        flex-direction: column;
        justify-content: center;
        text-align: left;
        align-items: start;
    }

    .container {
        margin: 0 0 0 80px;
    }

    .info h1 {
        font-size: 4rem;
        margin: 0;
    }

    .info h1 p {
        position: relative;
        font: inherit;
        margin: 0;
        width: fit-content;
        font-weight: 800;
        text-align: left;
        line-height: 130%;
        letter-spacing: -0.03em;
    }

    .info h2 {
        max-width: 65ch;
        font-weight: 200;
        color: var(--shade-500);
        margin-top: 0.50rem;
    }
    
    .fixed-info {
        position: absolute;
        height: 100vh;
        width: 100%;
        top:0;
        left: 0;
        right: 0;
        bottom: 0;
    }

    .fixed-info {
        position: fixed;
    }

    .info .fixed-info:before {
        content: "";
        z-index: -1;
        position: absolute;
        background-color: red;
        width: 100%;
        height: 53%;
        margin: auto;
        bottom: 0;
        left: 0;
    }

    .info .info-text {
        position: relative;
    }

    .name {
    text-align: center;
    font-size: 1.25rem;
    color: var(--shade-500);
    letter-spacing: 1px;
    text-transform: uppercase;
    
    }

  .scroll-button { 
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