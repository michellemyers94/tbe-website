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

<h4 use:reveal={{ delay: 50 }} class="composer-bootcamp">Live at Narloch Piano Studio in Chicago</h4>
<p>October 16, 2022</p>
<p>7:30pm CDT</p>
<p>Location: 4636 N Francisco Ave, Chicago, IL 60625</p>
<p>The concert is free, but suggested donation is $10!</p>
<a href="https://www.eventbrite.com/e/moon-dances-a-virtual-recital-tickets-421442384517" target="_blank"><button class="press-kit">RSVP here</button></a>
<div class="poster">

</body>

<style>
    body {
        background: #292828;
        height: auto;
    }

</style>