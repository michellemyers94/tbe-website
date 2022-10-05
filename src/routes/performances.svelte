<script>
    // import "../styles/_background.css";
    import "../styles/_about-background.css";
    import moon_dance from '../../static/moon-dances-announcement.png';
    import narloch_poster from '../../static/narloch-poster.jpg';
    import { reveal } from 'svelte-reveal';
</script>

<body>


<h4 use:reveal={{ delay: 50 }} class="composer-bootcamp">Live at Narloch Piano Studio in Chicago</h4>
<p>October 16, 2022</p>
<p>7:30pm CDT</p>
<p>Location: 4636 N Francisco Ave, Chicago, IL 60625</p>
<p>The concert is free, but suggested donation is $10!</p>
<a href="https://docs.google.com/forms/d/17MS1zZ4SfxNU_VQZIxkW5eTH-dsDT0F9atNObQQxUJs/viewform?edit_requested=true" target="_blank"><button class="press-kit">RSVP here</button></a>
<div class="poster">
    <img src={narloch_poster} class="poster-image" />
</div>

</body>

<style>
    body {
        background: #292828;
        height: auto;
    }

</style>