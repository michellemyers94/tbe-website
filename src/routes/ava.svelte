<script>
    import "../styles/_background.css"
    import ava_portrait from '../../static/ava-portrait.png';
    import { reveal } from 'svelte-reveal';

</script>



<h4 use:reveal={{ delay: 50 }}>Ava Wirth</h4>

<div class="about-us-grid">
    <img src={ava_portrait} alt="the blank experiment group photo. They are standing in front of a white wall and smiling at eachother while holding their instruments" class="individual-photo" />
    <section class="group-bio">
        <p class="member-bio">
        <span class="tbe-podcast">Ava Wirth</span> is a Chicago based oboist with a focus on contemporary music. As a soloist, she has placed in competitions in the Midwest, including the 2019 Tuesday Musical Solo Competition Woodwind Division and the 2019 New Albany Symphony Orchestra (NASO) Concerto Competition Senior Division. She has performed as a soloist with the Bowling Green State University (BGSU) New Music Ensemble at the 2018 and 2019 BGSU New Music Festivals as well as performing the Legacy Concerto by Oscar Navarro with the NASO in 2019.</p>

        <p class="member-bio">As an avid supporter of contemporary music, Ava has taken part in commissions and recordings that promote new works. In 2018, she was principal oboist on the BGSU Wind Symphony CD, Trends: New Music for Wind Band, Vol. 1. Her most recent commissions and collaborations include Adam Kennaugh’s 2020 work for solo oboe, You’re Here Because Someone Won a Fight With a Rock and Josh Trentadue’s 2021 piece for five-part ensemble, Meditation and Hymn to Nature, which was commissioned by her ensemble, The _____ Experiment.</p>

        <p class="member-bio">In her time at DePaul University, Ava performed as principal oboe and english horn with the DePaul Symphony Orchestra and DePaul University Wind Ensemble. In her free time, Ava enjoys tending to her succulents and watching comedy movies. She has earned a Master’s in Music from DePaul University while studying with Alex Klein (2022) and a Bachelor's Degree in Music from Bowling Green State University while studying with Dr. Nermis Mieses (2020).</p>

    </section>
</div>


<p class="about-directory">
    <a href="/about#members">Back to Members</a></p>