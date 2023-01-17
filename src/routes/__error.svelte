<script lang="ts" context="module">
    export function load({ error, status}) {
        return {
            props: {
                title: `${status}: ${error.message}`
            }
        }
    }
</script>

<script lang="ts">
    export let title;
</script>

<div class="align-middle">
<h1>Uh oh!</h1>
<p>There must be an error. If you think you should have gotten to a normal page, please contact me!</p>
<p style:color="#D81E5B">{title}</p>
</div>