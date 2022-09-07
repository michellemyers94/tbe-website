<script>
    import "../styles/_links.css";
    import logo from '../../static/white-logo.png';
    import { reveal } from 'svelte-reveal';
    import FaTwitter from 'svelte-icons/fa/FaTwitter.svelte';
    import FaYoutube from 'svelte-icons/fa/FaYoutube.svelte';
    import FaFacebook from 'svelte-icons/fa/FaFacebook.svelte';
    import FaInstagram from 'svelte-icons/fa/FaInstagram.svelte'
    import VideoBackground from '../../static/links-video-background-lite.mp4';



</script>

<video autoplay muted loop id="myVideo">
    <source src={VideoBackground} type="video/mp4">
</video>


<body>
<a href="/index"><img src={logo} alt="tbe logo" class="link-logo" /></a>
<p>New Music Ensemble</p>
<div class="links">
<a href="/index" target="_blank"><button use:reveal={{ delay: 50}} class="active">Check out our new website</button></a>
    <a href="https://mailchi.mp/928f57c3d1f2/style-guide" target="_blank"><button use:reveal={{ delay: 250}}>Download our style guide</button></a>
    <a href="https://mailchi.mp/d0ece2b7da16/theblankexperiment" target="_blank"><button use:reveal={{ delay: 450}}>Subscribe to our email list</button></a>
    <a href="https://www.youtube.com/channel/UCyRGtoDqCPV-uHDXXxkPJ9A" target="_blank"><button use:reveal={{ delay: 550}}>Check out our Youtube Channel</button></a>
    <a href="https://youtu.be/BehU_9EMq4E" target="_blank"><button use:reveal={{ delay: 650}}>New Youtube video: Cole Ryes - Frayed Wings</button></a>


    <div class="urls">
        <div class="icon"> <a href="https://instagram.com/theblankexperiment" target="_blank"><FaInstagram /></a></div>
       <div class="icon"> <a href="https://twitter.com/blankexperiment" target="_blank"><FaTwitter /></a></div>
       <div class="icon"><a href="https://www.youtube.com/channel/UCyRGtoDqCPV-uHDXXxkPJ9A" target="_blank"><FaYoutube /></a></div>
        <div class="icon"><a href="https://www.facebook.com/theblankexperiment" target="_blank"><FaFacebook /></a></div>


</div>
</div>




</body>

<style>
    body {
        background: none;
    }
</style>
