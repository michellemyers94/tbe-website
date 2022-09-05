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
            <li><a href=".">home</a></li>
            <li><a href="/about">about</a></li>
            <li><a href="/media">media</a></li>
            <li><a href="https://facebook.us5.list-manage.com/subscribe/post?u=1b6151b7dbe8fc8f8f7d0df7a&id=cf4dfa7be9&f_id=00aadae6f0" target="_blank">subscribe</a></li>
            <li><a href="/contact">contact us</a></li>
            <li><a href="/moon-dances" class="special">Moon Dances</a></li>
        </ul>
    </aside>
</div>

