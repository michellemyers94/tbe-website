<script>
    import logo from '../../static/white-logo.png';
</script>

<body>
<header>
    <img src={logo} alt="tbe logo" class="main-logo" />
    <div class="desktop-header">
    <h1>The _____ Experiment</h1>
    </div>

    <div class="sub-header">
<h2>New Music Ensemble</h2>
    </div>


<div class="tagline">
<h3>Pushing The Boundaries</h3>
</div>
</header>
</body>

<style>
    body {

        background: url("../static/mobile-background.png") no-repeat center center fixed;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        -o-background-size: cover;

        background-size: cover;
        height: 100%;


    }

    @media only screen and (min-width: 1025px) {
        body {

            background: url("../static/desktop-background.png") no-repeat center center fixed;
            -webkit-background-size: cover;
            -moz-background-size: cover;
            -o-background-size: cover;

            background-size: cover;

        }
    }

</style>

