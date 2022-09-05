<script>
    import "../styles/_background.css"
    import maya_portrait from '../../static/maya-portrait.png';
    import { reveal } from 'svelte-reveal';
</script>

<body class="members">

<h4 use:reveal={{ delay: 50 }}>Maya Grossman</h4>

<div class="about-us-grid">
    <img src={maya_portrait} alt="the blank experiment group photo. They are standing in front of a white wall and smiling at eachother while holding their instruments" class="individual-photo" />
    <section class="group-bio">
        <p class="member-bio"><span class="tbe-podcast">Maya Grossman</span> (she/her/hers) currently serves as the Second Bassoonist of the Wichita Symphony Orchestra where she has a fellowship and graduate staff assistantship at Wichita State University.  As an orchestral and chamber musician, Maya is both a performer and arts advocate. She performs with the Chamber Orchestra of the Smoky Valley; the Wichita State Graduate Quintet; the Detroit Chamber Orchestra; and participated in programming performances to expand the repertoire of the musical canon.  She strives to perform both classical repertoire and new music to explore the different roles a bassoon has in each ensemble while actively increasing representation in music. </p>

        <p class="member-bio">Maya was named the June Stone Allen Fellow at Wichita State University where she is working towards her Master’s Degree, and holds a Bachelor’s Degree in Bassoon Performance with a double minor in Writing and Performing Arts Management & Entrepreneurship from the University of Michigan (2021), and a High School Diploma in Bassoon Performance from the Interlochen Arts Academy (2017). Maya’s primary instructors were Victoria King, Jeffrey Lyman, and Eric Stomberg. </p>

        <p class="member-bio">She also has experience working in arts administration with the Detroit Symphony Orchestra and the Great Lakes Chamber Music Festival. During her work, Maya recently completed a research project “The Musician, The Markswoman, and the Jew” where she explored how parts of identities play a role in community, music, and performance.</p>

    </section>
</div>

<p class="about-directory">
    <a href="/about#members">Back to Members</a></p>

</body>