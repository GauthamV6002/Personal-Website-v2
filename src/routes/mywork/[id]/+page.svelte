<script>
    import { page } from '$app/stores';
    import config from '../../../config/site.config.json';
    
    const pageId = $page.params.id;
    console.log(config)
</script>


mywork-{$page.params.id}
<br>
title = {config.title}