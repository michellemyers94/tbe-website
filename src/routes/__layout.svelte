<script>
    import Nav from '$lib/nav/Nav.svelte';
    import "../app.css";
    import NavMobile from "$lib/nav/NavMobile.svelte";

        function myFunction() {
        var x = document.getElementById("myLinks");
        if (x.style.display === "block") {
        x.style.display = "none";
    } else {
        x.style.display = "block";
    }
    }

</script>

<div class="nav-desktop">
<Nav />
</div>

<!--<div class="nav-mobile">-->
<!--    <NavMobile />-->
<!--</div>-->



<div class="footer">
    <p>&copy; The _____ Experiment, LLC 2022</p>
</div>

<slot />




