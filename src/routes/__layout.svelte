<script>
    import Nav from '$lib/nav/Nav.svelte';
    import "../app.css";
    import NavMobile from "$lib/nav/NavMobile.svelte";



</script>

<div class="nav-desktop">
<Nav />
</div>

<div class="nav-mobile">
    <NavMobile />
</div>

<slot />




