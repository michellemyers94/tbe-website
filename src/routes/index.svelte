<script>
    import "../styles/_homepage-background.css";
    import logo from '../../static/white-logo.png';
    import { reveal } from 'svelte-reveal';
</script>


<header>
    <img src={logo} alt="tbe logo" class="main-logo" />
    <h1 use:reveal={{ delay: 50 }} class="homepage">The _____ Experiment</h1>

    <div class="sub-header">
<h2 use:reveal={{ delay: 50 }}>New Music Ensemble</h2>
    </div>


<div class="tagline">
<h3 use:reveal={{ delay: 1000 }}>Pushing The Boundaries</h3>

</div>
</header>




<style>
    /*body {*/

    /*    background: url("/static/mobile-background.png") no-repeat center center fixed;*/
    /*    -webkit-background-size: cover;*/
    /*    -moz-background-size: cover;*/
    /*    -o-background-size: cover;*/

    /*    background-size: cover;*/
    /*    height: 100%;*/


    /*}*/

    /*@media only screen and (min-width: 1025px) {*/
    /*    body {*/

    /*        background: url("/static/desktop-background.png") no-repeat center center fixed;*/
    /*        -webkit-background-size: cover;*/
    /*        -moz-background-size: cover;*/
    /*        -o-background-size: cover;*/

    /*        background-size: cover;*/

    /*    }*/
    /*}*/




</style>

