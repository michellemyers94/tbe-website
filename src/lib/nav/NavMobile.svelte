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
            <li><a href="." on:click={()=> active = !active}>home</a></li>
            <li><a href="/about" on:click={()=> active = !active}>about</a></li>
            <li><a href="/media" on:click={()=> active = !active}>media</a></li>
            <li><a href="https://facebook.us5.list-manage.com/subscribe/post?u=1b6151b7dbe8fc8f8f7d0df7a&id=cf4dfa7be9&f_id=00aadae6f0" target="_blank" on:click={()=> active = !active}>subscribe</a></li>
            <li><a href="/contact" on:click={()=> active = !active}>contact us</a></li>
            <li><a href="/performances" class="special" on:click={()=> active = !active}>performances</a></li>
        </ul>
    </aside>
</div>

