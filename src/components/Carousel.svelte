<script>
    import "../app.css"
    import "../lib/flowbite/dist/flowbite.js"
    import "../lib/flowbite/dist/flowbite.css"
    import PotabiTDBG from "../assets/PotabiTDBG.jpg"
    import PotabiSystemsBG from "../assets/PotabiSystemsBG.jpg"
    import CoreNGSBG from "../assets/CoreNGSBG.jpg"
</script>

<main>
    <div id="default-carousel" class="relative h-full" data-carousel="static">
        <!-- Carousel wrapper -->
        <div class="overflow-hidden relative h-full">
             <!-- Item 1 -->
            <div class="duration-700 ease-in-out flex items-center" data-carousel-item>
                <img src="{PotabiTDBG}" class="block absolute w-screen h-screen" alt="Potabi Systems">
            </div>
            <!-- Item 2 -->
            <div class="duration-700 ease-in-out flex items-center" data-carousel-item>
                <img src="{CoreNGSBG}" class="block absolute w-screen h-screen" alt="Potabi Systems">
            </div>
            <!-- Item 3 -->
            <div class="duration-700 ease-in-out flex items-center" data-carousel-item>
                <img src="{PotabiSystemsBG}" class="block absolute w-screen h-screen" alt="Potabi Systems">
            </div>
        </div>
        <!-- Slider indicators -->
        <div class="flex absolute bottom-5 left-1/2 z-30 space-x-3">
            <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 1" data-carousel-slide-to="0"></button>
            <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 1" data-carousel-slide-to="1"></button>
            <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 1" data-carousel-slide-to="2"></button>
        </div>
        <!-- Slider controls -->
        <button type="button" class="flex absolute top-0 left-0 z-30 justify-center items-center px-4 h-full cursor-pointer group focus:outline-none" data-carousel-prev>
            <span class="inline-flex justify-center items-center w-8 h-8 rounded-full sm:w-10 sm:h-10 bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
                <span class="">&lt;</span>
            </span>
        </button>
        <button type="button" class="flex absolute top-0 right-0 z-30 justify-center items-center px-4 h-full cursor-pointer group focus:outline-none" data-carousel-next>
            <span class="inline-flex justify-center items-center w-8 h-8 rounded-full sm:w-10 sm:h-10 bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
                <span class="">&gt;</span>
            </span>
        </button>
    </div>
</main>

<style>
    main{
        height: 92.15vh;
    }
</style>