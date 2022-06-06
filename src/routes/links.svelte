<script>
    import "../styles/_links.css";
    import { reveal } from 'svelte-reveal';
    import FaTwitter from 'svelte-icons/fa/FaTwitter.svelte';
    import FaYoutube from 'svelte-icons/fa/FaYoutube.svelte';
    import FaFacebook from 'svelte-icons/fa/FaFacebook.svelte';
    import FaInstagram from 'svelte-icons/fa/FaInstagram.svelte'



</script>




<body>
<h4>The _____ Experiment</h4>
<div class="links">
<a href="https://tbe-website.vercel.app" target="_blank"><button use:reveal={{ delay: 50}}>Check out our new website</button></a>
    <a href="https://mailchi.mp/928f57c3d1f2/style-guide" target="_blank"><button use:reveal={{ delay: 250}}>Download our style guide</button></a>
    <a href="https://mailchi.mp/d0ece2b7da16/theblankexperiment" target="_blank"><button use:reveal={{ delay: 450}}>Subscribe to our email list</button></a>
    <a href="https://www.youtube.com/channel/UCyRGtoDqCPV-uHDXXxkPJ9A" target="_blank"><button use:reveal={{ delay: 550}}>Check out our Youtube Channel</button></a>
    <a href="https://www.youtube.com/watch?v=IsIn3kbXxCc" target="_blank"><button use:reveal={{ delay: 650}} class="active">New Youtube video: Cassie Wieland - Go Together</button></a>


    <div class="urls">
        <div class="icon"> <a href="https://instagram.com/theblankexperiment" target="_blank"><FaInstagram /></a></div>
       <div class="icon"> <a href="https://twitter.com/blankexperiment" target="_blank"><FaTwitter /></a></div>
       <div class="icon"><a href="https://www.youtube.com/channel/UCyRGtoDqCPV-uHDXXxkPJ9A" target="_blank"><FaYoutube /></a></div>
        <div class="icon"><a href="https://www.facebook.com/theblankexperiment" target="_blank"><FaFacebook /></a></div>


</div>
</div>




</body>

