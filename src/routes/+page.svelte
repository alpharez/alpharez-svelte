<script>
    import Heading from "../components/Heading.svelte"
    import WhatWeDo from "../components/WhatWeDo.svelte";
    import Footer from "../components/Footer.svelte";
</script>

<main>
    <Heading />
    <WhatWeDo />
    <Footer />
</main>

<style>
    :global(html) {
        background: linear-gradient(#12c2e9,#eef,#ccc);
        background-repeat: no-repeat;
        background-attachment: fixed;
        height: 100%;
        margin: 0;
        padding: 2rem;
    }
  </style>