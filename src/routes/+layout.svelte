<nav>
    <div class="nav-container">
        <a href="/" class="nav-logo" title="Back to Homepage">Город Абакан</a>
        <div class="nav-links">
            {#each nav as link}
                {#if link.isShow}
                <a href={link.href} class="link">{link.title}</a>
                {/if}
            {/each}
        </div>
    </div>
</nav>
   <div class="container">
        <!-- Pages will be injected below -->
        <slot></slot>
   </div>
<script>
    const nav = [
        {
            title: `История`,
            href: `/history`,
            isShow: true
        },
        {
            title: `Фотографии`,
            href: `/photo`,
            isShow: true
        },
        {
            title: `Достопримечательности`,
            href: `/project`,
            isShow: true
        },
        {
            title: `Учебные заведения`,
            href: `/school`,
            isShow: true
        },
        {
            title: `Отдых`,
            href: `/chill`,
            isShow: false
        },
    ];
</script>
<style>
    .container {
    max-width: 1400px;
    margin: 50px auto;
    }
</style>