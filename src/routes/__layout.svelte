<!-- src/routes/__layout.svelte -->

<div class="container">
    <nav>
        <div class="nav-container"></div>
            <a href="/" class="nav-logo" title="Back to Homepage">David Adeneye</a>
            <div class="nav-links">
                <a href="/about" class="link">About</a>
                <a href="/blog" class="link">Blog</a>
                <a href="/projects" class="link">Projects</a>
                <a href="/contact" class="link">Contact</a>
            </div>
    </nav>
    <slot />
</div>

<style>
     .container {
        max-width: 1400px;
        margin: 50px auto;
    }
</style>


