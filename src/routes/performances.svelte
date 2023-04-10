<script>
    // import "../styles/_background.css";
    import "../styles/_about-background.css";
    import moon_dance from '../../static/moon-dances-announcement.png';
    import kaiser_poster from '../../static/kaiser_poster.png';
    import classical_revolution from '../../static/classical_revolution.png';
    import { reveal } from 'svelte-reveal';
</script>

<body>

<h4 use:reveal={{ delay: 50 }} class="composer-bootcamp">Kaiser Gallery's June Concert Series <em>Melodic Mixtures</em></h4>
<p>June 27, 2023</p>
<p>7pm EDT</p>
<p>Location: 2418 Professor Ave, Cleveland OH 44113</p>
<p>Tickets: $10</p>
<a href="https://goo.gl/maps/AEZCsEKZZL7hang9A" target="_blank"><button class="press-kit">Open in Google Maps</button></a>
<div class="poster">
    <img src={kaiser_poster} class="poster-image" />
</div>


<h4 use:reveal={{ delay: 50 }} class="composer-bootcamp">Classical Revolution Cleveland</h4>
<p>June 21, 2023</p>
<p>8pm EDT</p>
<p>Location: Happy Dog</p>
<p>Tickets: FREE</p>
<a href="https://goo.gl/maps/UsPL11dsVXPJkNnN9" target="_blank"><button class="press-kit">Open in Google Maps</button></a>
<div class="poster">
    <img src={classical_revolution} class="poster-image" />
</div>



</body>

<style>
    body {
        background: #292828;
        height: auto;
    }

</style>