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
        <div tabindex="0">
            <svg
            width="24"
            height="24"
            xmlns="http://www.w3.org/2000/svg"
            fillRule="evenodd"
            clipRule="evenodd"
          >
            <path d="M21.883 12l-7.527 6.235.644.765 9-7.521-9-7.479-.645.764 7.529 6.236h-21.884v1h21.883z" />
          </svg>
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
        margin: 0;
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
        height: 50%;
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

.info .animate-background:before {
  animation: slide-in-bottom 1s ease-in-out both;
}

.info .animate-name {
  animation: tracking-in-expand 1s cubic-bezier(0.215, 0.61, 0.355, 1) both;
}

.info .animate-text-1 {
  animation: fade-in-bottom 0.5s ease-in-out both;
}

.animate-text-2 {
    padding-top: 15px;
}

.info .animate-subtitle {
  animation: fade-in-bottom 0.5s ease-in-out 100ms both;
}

.info .animate-scroll {
  animation: fade-in-bottom 0.5s ease-in-out 150ms both;
}


</style>