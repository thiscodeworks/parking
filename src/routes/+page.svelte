<script lang="ts">
  import { onMount } from 'svelte';
  import { browser } from '$app/environment';

  onMount(() => {
    if (browser) {
      let domain = window.location.hostname.replace("www.", "");

      fetch(`https://inspect.domains?domain=${domain}`)
        .then(response => {
          console.log('Domain inspection request sent.');
          window.location.replace("https://woltair.cz?utm_source=michalcerny&utm_medium=domains&utm_campaign=redirect&utm_id=mcredirects");
        })
        .catch(error => {
          console.error('Error fetching domain info:', error);
        });
    }
  });
</script>
