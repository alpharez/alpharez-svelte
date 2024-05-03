<script>
    import LinkedIn from "svelte-material-icons/Linkedin.svelte"
    import Twitter from "svelte-material-icons/Twitter.svelte"
    import Facebook from "svelte-material-icons/Facebook.svelte"
    import Twitch from "svelte-material-icons/Twitch.svelte"

</script>
<div class="m-6">
    <h3 class="w-full text-2xl mb-1 mt-6 font-bold">Company</h3>
    <a href="#" class="mr-6 text-xl">About</a>
    <a href="#" class="text-xl">Contact</a>
    
    <div class="flex mt-6">
        <LinkedIn size="30px" class="mr-2" />
        <Twitter size="30px" class="mr-2" />
        <Facebook size="30px" class="mr-2" />
        <Twitch size="30px" class="mr-2" />
    </div>
</div>

<style>
    a {
        @apply hover:underline text-blue-600 hover:text-blue-800 visited:text-purple-600
    }
</style>