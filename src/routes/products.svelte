<script>
    import { Router, Link, Route } from "svelte-routing";
    import PotabiSystems from "./products/PotabiSystems.svelte";
    import CoreNGS from "./products/CoreNGS.svelte";
</script>

<Router>
    <div class="px-5">
        <h1 class="text-3xl">Products</h1>
        <div class="flex gap-2 my-5">
            <Link to="potabi-systems">
                <span class="block p-6 max-w bg-white rounded-lg border border-gray-200 shadow-md hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700">
                    <h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Potabi Systems</h2>
                    <p class="font-normal text-gray-700 dark:text-gray-400">A powerful desktop/mobile operating system designed for secure enterprises and personal use. Potential and Ability. Pretty. Powerful.</p>
                </span>
            </Link>
            <Link to="corengs">
                <span class="block p-6 max-w bg-white rounded-lg border border-gray-200 shadow-md hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700">
                    <h2 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">CoreNGS</h2>
                    <p class="font-normal text-gray-700 dark:text-gray-400">A multipurpose, highly configurable and redistributable operating system designed to be the base of other operating systems</p>
                </span>
            </Link>
        </div>
        <Route path="potabi-systems"><PotabiSystems /></Route>
        <Route path="corengs"><CoreNGS /></Route>
    </div>
</Router>