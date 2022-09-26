<script>
    // import "../styles/_background.css";
    import "../styles/_about-background.css";
    import moon_dance from '../../static/moon-dances-announcement.png';
    import { reveal } from 'svelte-reveal';
</script>

<body>
<h4 use:reveal={{ delay: 50 }} class="composer-bootcamp">Moon Dances: A Virtual Recital</h4>
<p>Coming Oct 1st, 2022</p>
<p>8pm-9pm EDT</p>
<a href="https://www.eventbrite.com/e/moon-dances-a-virtual-recital-tickets-421442384517" target="_blank"><button class="press-kit">Get Your Tickets Here!</button></a>
<div class="poster">
<img src={moon_dance} class="poster-image"/>
</div>

</body>

<style>
    body {
        background: #292828;
        height: auto;
    }

</style>