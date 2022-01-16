<!-- src/routes/blog.svelte -->
<svelte:head>
	<title>Blog</title>
</svelte:head>

<script context="module">
    export const load = async ({ fetch }) => {
        const res = await fetch("https://jsonplaceholder.typicode.com/posts");
        const blogposts = await res.json();
        return {
            props: {
                blogposts,
            }
        }
    }
 
</script>

<script>
    export let blogposts; 
</script>



<div class="container">
    <h1>My Articles</h1> 

    <div class="blogposts">
        {#each blogposts as post}
        <div class="post">
            <h2>{post.title.substring(0, 20)}</h2>
            <p>{post.body.substring(0, 80)}</p>
            <p class="readmore"><a href={`/blog/${post.id}`}>Read More</a></p>
        </div> 
        {/each}
    </div>
</div>



<style>
    .container {
        max-width: 800px;
        margin: 50px auto;
    }
    .blogposts {
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-gap: 20px;
    }

    .post {
        border: 1px solid #ddd;
        padding: 10px;
        box-shadow: 0 0 10px #eee;
    }

    h2 {
        margin: 0;
    }

    .readmore {
        color: rgb(10, 10, 139);
        text-align: right;
        margin: 20px 0 0 0;
    }

    .readmore:hover {
        color: green;
    }
</style>