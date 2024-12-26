<script lang="ts">
  import { Button } from "$lib/components/ui/button";

  let counter = $state(0);
</script>

<div class="flex h-screen w-full items-center justify-center">
  <Button onclick={() => ++counter}>Count: {counter}</Button>
</div>
