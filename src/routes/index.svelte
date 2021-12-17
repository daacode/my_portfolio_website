<div class="info">
    <div class="fixed-info animate-background">
      <div class="container info-container">
        <div class="name-container">
          <span class="name animate-name">David Adeneye</span>
        </div>
        <div class="info-text">
          <h1>
            <p class="animate-text-1">School-taught Computer Scientist,</p>
            <p class="animate-text-2">Self-taught Software Engineer</p>
          </h1>
        </div>
        <h2 class="animate-subtitle">
          On a mission to help SMEs across the globe do businesses seamlessly and digitally.
        </h2>
        <div class="scroll-button animate-scroll" tabindex="0">
          <div class="arrow">→</div> scroll
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
        margin: 0;
    }
    
    .fixed-info {
        position: absolute;
        margin: auto;
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
        background-color: var(--shade-100);
        width: 100%;
        height: 50%;
        margin: auto;
        bottom: 0;
        left: 0;
    }

    .info .info-text {
        position: relative;
    }

    .scroll-button {
        position: absolute;
        opacity: 0;
        bottom: 0;
        padding: 2rem 0;
        border: none;
        outline: none;
        cursor: pointer;
        display: flex;
        transition: opacity 250ms;
    }

    .scroll-button .arrow {
        margin-right: 0.25rem;
    }

    .scroll-button:hover .arrow,
    .scroll-button:focus .arrow {
        animation: bounce-top 1.5s ease-in-out infinite both;
    }   

    .name {
    text-align: center;
    font-size: 1.25rem;
    color: var(--shade-500);
    letter-spacing: 1px;
    text-transform: uppercase;
}

.info .animate-background:before {
  animation: slide-in-bottom 1s ease-in-out both;
}

.info .animate-name {
  animation: tracking-in-expand 1s cubic-bezier(0.215, 0.61, 0.355, 1) both;
}

.info .animate-text-1 {
  animation: fade-in-bottom 0.5s ease-in-out both;
}

.info .animate-text-2 {
  animation: fade-in-bottom 0.5s ease-in-out 50ms both;
}

.info .animate-subtitle {
  animation: fade-in-bottom 0.5s ease-in-out 100ms both;
}

.info .animate-scroll {
  animation: fade-in-bottom 0.5s ease-in-out 150ms both;
}


</style>