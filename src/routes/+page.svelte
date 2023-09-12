<script>
import ProgressBar from "@okrad/svelte-progressbar";
import { tooltip } from "../lib/tooltip";
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<div class="wraper" use:tooltip title="test title">
  <ProgressBar series={[20, 20]} />
</div>
