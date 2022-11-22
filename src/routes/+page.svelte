<script lang="ts">
    import Test from "../lib/Test.svelte";
    import {init} from 'svelte-i18n'

    init({
            fallbackLocale: 'en',
        }
    );
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<Test/>
