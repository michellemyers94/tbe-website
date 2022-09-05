<script>
    import "../styles/_about-background.css";
    import { reveal } from 'svelte-reveal';
    import group_photo from '../../static/about-us-group.jpg';
</script>

<body>

<h4 use:reveal={{ delay: 50 }}>about us</h4>

<p>Meet The Ensemble</p>
<div class="about-us-grid">
<img src={group_photo} alt="the blank experiment group photo. They are standing in front of a white wall and smiling at eachother while holding their instruments" class="group-photo" />
<section class="group-bio">
    <p class="bio"><span class="tbe-podcast">The _____ Experiment</span> (pronounced The “Blank” Experiment) is an up and coming flexible instrumentation ensemble based in the Midwest. With over 30 commissions, this group is committed to expanding the repertoire for mixed chamber ensembles. Their mission is to commission music by a variety of composers in order to create high quality, but audibly approachable new music by performing outreach concerts for a variety of audiences in various locations. . This ensemble was originally founded in 2017 by Andrew Hosler (saxophones), Michelle Cusick (clarinets), and Natalie Pate (harp). The ____ Experiment quickly began collaborating with composers around the United States to create works for this new instrumentation. </p>

    <p class="bio"> Their first recital tour featured performances at Michigan State University and Bowling Green State University, following that they had additional performances at the Flint Institute of Music and the University of Michigan both featuring mostly newly composed works. In the summer of 2018, The _____ Experiment recorded their first album, Conversations, with Sly Pup Production and went on to release the album in March 2020. This album featured seven world premiere recordings featuring composers from multiple states, including: Michigan, Florida, Ohio, and Arizona. </p>

    <p class="bio">In July of 2020 The ____ Experiment expanded to include oboist, Ava Wirth. Throughout the rest of the year, the ensemble worked to record pieces that were compatible with socially distanced settings. One of these works was the first composer collaboration with the new instrumentation:  Tyler Mazone’s Mini Personalities for Oboe, Bb Clarinet, and Tenor Saxophone. They also started a series of virtual projects aimed at cross disciplinary collaboration entitled Visual Soundscapes. In the Spring of 2021, the ensemble continued to expand to include Maya Grossman on Basson. During this time, The _____ Experiment was heading a commission for composer Josh Trentadue. In May of 2021, the newest member was added to the ensemble, harpist Danielle Kuntz. </p>

    <p class="bio">In August of 2021, the entire ensemble met in person, the first time since the Covid-19 pandemic began. During this meeting, The _____ Experiment rehearsed and recorded new works that were released during the fall of 2021. Six of these works were released on the October recital, “Kadupal”. This recital had three world premieres, including the commission with Josh Trentadue, Meditation and Hymn to Nature.</p>

    <p class="bio">The members of The _____ Experiment are located in Ann Arbor, MI, Cleveland, OH, Chicago, IL, Wichita, KS, and San Francisco, CA. When not rehearsing, the members of this ensemble enjoy mountain biking, taking care of their pets and plants, and laughing at cheesy jokes about musicians.
</section>
</div>



<a href="../../static/tbe-press-kit.pdf" target="_blank" download="The Blank Experiment Press Kit"><button class="press-kit">Download our press kit</button></a>



<p> </p>
<h4 use:reveal={{ delay: 50 }}>Our Members</h4>

<div id="members">
    <div class="individual">
        <p class="about-member">Michelle Cusick</p>
        <a href="michelle"><p class="empty"> </p></a>

    </div>


    <div class="individual">
        <p class="about-member">Drew Hosler</p>
        <a href="drew"><p class="empty"> </p></a>

    </div>

    <div class="individual">
        <p class="about-member">Ava Wirth</p>
        <a href="ava"><p class="empty"> </p></a>

    </div>

<div class="individual">
        <p class="about-member">Maya Grossman</p>
        <a href="maya"><p class="empty"> </p></a>

</div>

    <div class="individual">
        <p class="about-member">Danielle Kuntz</p>
        <a href="danielle"><p class="empty"> </p></a>

    </div>


</div>
</body>


<style>
    body {
        background: #292828;
        height: 100%;
    }
</style>