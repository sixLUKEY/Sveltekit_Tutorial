<script>
    export const routes = [
        {
            name: 'introduction',
            href: 'introduction' 
        },
        {
            name: 'reactivity',
            href: 'reactivity'
        },
        {
            name: 'props',
            href: 'props'
        },
        {
            name: 'logic',
            href: 'logic'
        },
        {
            name: 'events',
            href: 'events'
        },
        {
            name: 'bindings',
            href: 'bindings'
        },
        {
            name: 'lifecycle',
            href: 'lifecycle'
        },
        {
            name: 'stores',
            href: 'stores'
        },
        {
            name: 'readable-stores',
            href: 'readable-stores'
        },
        {
            name: 'custom-stores',
            href: 'custom-stores'
        },
        {
            name: 'store-bindings',
            href: 'store-bindings'
        }
    ]
</script>

<nav>
    <ul>
        {#each routes as { name, href }}
             <li>
                <a {href}>{name}</a>
             </li>
        {/each}
    </ul>
</nav>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
