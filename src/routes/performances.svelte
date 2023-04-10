<script>
    // import "../styles/_background.css";
    import "../styles/_about-background.css";
    import moon_dance from '../../static/moon-dances-announcement.png';
    import ziggys_poster from '../../static/ziggys-poster.png';
    import { reveal } from 'svelte-reveal';
</script>

<body>


<h4 use:reveal={{ delay: 50 }} class="composer-bootcamp">Ziggy's Performance: EP Release COncert for <em>Nostalgia</em></h4>
<p>April 11, 2023</p>
<p>7:30pm EDT</p>
<p>Location: Ziggy's</p>
<p>The concert is free!</p>
<a href="https://goo.gl/maps/PjhbnBDX178j9Wfp6" target="_blank"><button class="press-kit">Open in Google Maps</button></a>
<div class="poster">
    <img src={ziggys_poster} class="poster-image" />
</div>

</body>

<style>
    body {
        background: #292828;
        height: auto;
    }

</style>