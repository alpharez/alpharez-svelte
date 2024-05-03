<script>
    import Cloud from "svelte-material-icons/Cloud.svelte";
    import ShieldLock from "svelte-material-icons/ShieldLock.svelte";
    import Router from "svelte-material-icons/Router.svelte";
    import Cog from "svelte-material-icons/Cog.svelte";
    import Monitor from "svelte-material-icons/MonitorDashboard.svelte"
    import App from "svelte-material-icons/ApplicationBraces.svelte"
  </script>

<h3 class="w-full text-2xl ml-6 mb-1 mt-6 font-bold">
    What We Offer
</h3>

<div class="flex flex-row flex-wrap">
    <div class="w-1/3 p-4 m-1 bg-stone-100 shadow-lg rounded-md">
        <div class="flex">
            <Router size="30px" class="mr-2" />
            <h3 class="text-2xl mb-6 font-bold text-blue-700">
                Networking
            </h3>
        </div>
        Network design, integration, troubleshooting and configuration
    </div>
    <div class="w-1/3 p-4 m-1 bg-stone-100 shadow-lg rounded-md">
        <div class="flex">
            <ShieldLock  size="30px" class="mr-2" />
            <h3 class="text-2xl mb-6 font-bold text-blue-700">
                Security
            </h3>
        </div>
        Be safe from attackers and vulnerabilities
    </div>
    <div class="w-1/3 p-4 m-1 bg-stone-100 shadow-lg rounded-md">
        <div class="flex">
            <Cog size="30px" class="mr-2" />
            <h3 class="text-2xl mb-6 font-bold text-blue-700">
                Automation
            </h3>
        </div>
        Eliminate manual processes through code
    </div>
    <div class="w-1/3 p-4 m-1 bg-stone-100 shadow-lg rounded-md">
        <div class="flex">
            <Cloud size="30px" class="mr-2" />
            <h3 class="text-2xl mb-6 font-bold text-blue-700">
                Cloud
            </h3>
        </div>
        Move your infrastructure to the cloud.  Azure, AWS, GCP
    </div>
    <div class="w-1/3 p-4 m-1 bg-stone-100 shadow-lg rounded-md">
        <div class="flex">
            <Monitor size="30px" class="mr-2" />
            <h3 class="text-2xl mb-6 font-bold text-blue-700">
                Monitoring
            </h3>
        </div>
        Monitor things and other stuff
    </div>
    <div class="w-1/3 p-4 m-1 bg-stone-100 shadow-lg rounded-md">
        <div class="flex">
            <App size="30px" class="mr-2" />
            <h3 class="text-2xl mb-6 font-bold text-blue-700">
                Applications
            </h3>
        </div>
        We do some apps yes?
    </div>
</div>