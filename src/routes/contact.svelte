<script>
    // import "../styles/_background.css"
    import "../styles/_about-background.css";
    import { reveal } from 'svelte-reveal';
</script>

<body>

<h4 use:reveal={{ delay: 50 }}>Contact</h4>



<form action="https://api.staticforms.xyz/submit" method="post">
    <input type="text" name="name" placeholder="Your Name">
    <input type="text" name="email" placeholder="Your Email" />
    <input type="text" name="subject" placeholder="Your Subject" />
    <textarea name="message" class="submit-form" placeholder="Enter Your Message"></textarea>
    <input type="text" name="honeypot" style="display:none">
    <input type="hidden" name="accessKey" value="2f903c59-3647-4a7a-8244-5a73c5d27308">

    <input type="hidden" name="replyTo" value="theblankexperiment@outlook.com">
    <input type="hidden" name="redirectTo" value="https://tbe-website.vercel.app/contact-success">
    <input type="submit" value="Submit" />
</form>

</body>

<style>
    body {
        background: #292828;
        height: auto;
    }

</style>