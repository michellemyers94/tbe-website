<script>
    // import "../styles/_background.css";
    import "../styles/_about-background.css";
    import present_poster from '../../static/the-present.png';
    import { reveal } from 'svelte-reveal';
</script>

<body>

<h4 use:reveal={{ delay: 50 }} class="composer-bootcamp">Virtual Recital Series: <em>the present...</em></h4>
<p>June 27, 2023</p>
<p>7pm EDT</p>
<p>Location: 2418 Professor Ave, Cleveland OH 44113</p>
<p>Tickets: $10</p>
<p class="member-bio"><a href="https://www.eventbrite.com/e/the-blank-experiment-live-at-kaiser-gallery-tickets-658465948377" class="performance">(Get Tickets)</a></p>
<a href="https://goo.gl/maps/AEZCsEKZZL7hang9A" target="_blank"><button class="press-kit">Open in Google Maps</button></a>
<div class="poster">
    <img src={present_poster} class="poster-image" />
</div>




</body>

<style>
    body {
        background: #292828;
        height: auto;
    }

</style>