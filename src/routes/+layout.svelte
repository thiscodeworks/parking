<script>
    import { afterNavigate } from "$app/navigation";
    import "../app.css";
    import { dev } from '$app/environment';
    import { inject } from '@vercel/analytics';
    
    inject({ mode: dev ? 'development' : 'production' });

    afterNavigate(() => {
      //window.HSStaticMethods.autoInit();
    });

</script>

<slot />