<script lang="ts">
import { mapType } from "./data";

export let item: any;
</script>

<section class="obsoletion-warning">
  ⚠️ This {mapType(item.type)} is marked as <em>obsolete</em>, meaning that it
  is likely not possible to obtain in this version.
</section>

<style>
.obsoletion-warning {
  background-color: #69553f;
}
</style>
