<!-- src/routes/__layout.svelte -->

<nav>
    <div class="container">
        <a href="/" class="nav-logo" title="Back to Homepage">David Adeneye</a>
        <div class="nav-links">
            <a href="/about" class="link">About</a>
            <a href="src/routes/blog" class="link">Blog</a>
            <a href="/projects" class="link">Projects</a>
            <a href="/contact" class="link">Contact</a>
        </div>
    </div>
</nav>

<slot></slot>

