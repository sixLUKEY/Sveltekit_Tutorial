<script>
    export let data;
</script>

<div class="layout">
    <main>
        <slot/>
    </main>
    <aside>
        <h2>More post</h2>
        <ul>
            {#each data.summaries as { slug, title }}
                 <li>
                    <a href="/blog/{slug}">{title}</a>
                 </li>
            {/each}
        </ul>
    </aside>
</div>