<script lang="ts">
  import { browser } from '$app/environment';
  
  let domain = "";
  
  if (browser) {
    domain = window.location.hostname;
    domain = domain.replace("www.","");
  }
  
  fetch("https://inspect.domains?domain="+domain)
        .then(response => {
          window.location.replace("https://woltair.cz?utm_source=michalcerny&utm_medium=domains&utm_campaign=redirect&utm_id=mcredirects");
        });
</script>
