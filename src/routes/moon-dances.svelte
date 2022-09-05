<script>
    import "../styles/_background.css";
    import moon_dance from '../../static/moon-dances-announcement.png';
    import { reveal } from 'svelte-reveal';
</script>

<h4 use:reveal={{ delay: 50 }} class="composer-bootcamp">Moon Dances: A Virtual Recital</h4>
<p>Coming Oct 1st, 2022</p>
<div class="poster">
<img src={moon_dance} class="poster-image"/>
</div>


<style>
    body {
        background: #292828;
        width: 100vw;

    }

</style>