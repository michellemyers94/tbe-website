<script>


let active =false;
</script>


<div class="nav-bar-mobile">

    <nav class="grid-mobile">
        <div class="grid-logo"><a href="."><img src="/black-logo.png"  class="nav-logo"/></a></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div class="menu-toggle">
        <div class="menu-icon" on:click={()=> active = !active}>
            {active? 'X' : '☰'}
        </div>
        </div>

    </nav>



    <aside class:active>
        <ul>
            <li>Home</li>
            <li>About</li>
            <li>Media</li>
            <li>Subscribe</li>
            <li>Contact Us</li>
            <li>Moon Dances</li>
        </ul>
    </aside>
</div>

