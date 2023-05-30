<svelte:head>
    <title>Учебные заведения</title>
</svelte:head>
<div class='container'>
    <h1>Учебные заведения Абакана</h1>
    <div class='blogposts'>
        {#each routes as page}
            <div class='post'>
                <h2>{page.title}</h2>
                <p>{page.body}</p>
                <p class='readmore'>
                    <a class='link' href={`/school/posts/${page.id}`}>Читать далее</a>
                </p>
            </div>
        {/each}
    </div>
</div>
<script>
    import {routes} from "./routes"
</script>
<style>
    .container {
    margin: 50px auto;
    max-width: 800px;
    padding: 0 20px;
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
    background-color: #B0E0E6;
    }
    .link {
    color: rgb(10, 10, 139);
    }
</style>