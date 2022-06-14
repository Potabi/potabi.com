<script>
    import icon from "../assets/icons/systems.icon.png"
    let ReleaseNotes = "https://wiki.potabi.com/wiki/Potabi_Systems_B4-1.0A_Release"
    let ISO = "https://github.com/Potabi/release/releases/download/b4_1.0a-release/potabi-lumina-b4_1.0a_Luna.iso"
    import GFXMultimedia from "../assets/graphics/Multimedia.svg"
    import GFXAppDev from "../assets/graphics/AppDevelopment.svg"
</script>

<main class="px-5 py-2">
    <h1 class="text-2xl font-bold">Potabi Systems</h1>
    <div class="sm:flex sm:justify-between sm:items-center">
        <img class="w-3/5 md:w-2/5 lg:w-1/5" src="{GFXAppDev}" alt="Graphics-AppDev">
        <p class="w-full">
            Potabi Systems Desktop is still within the beta editions of the software, and is not yet ready for production use. If you wish, you may still test the system using the most recent beta of our operating system.

            Please note there will be issues, which are documented in the release notes
        </p>
        <img class="w-3/5 md:w-2/5 lg:w-1/5" src="{GFXMultimedia}" alt="Graphics-Multimedia">
    </div>
    <div class="flex items-center justify-center">
        <a href="https://buy.stripe.com/8wMfZTeON7z86xacMN" class="focus:outline-none text-white bg-red-700 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">
            Buy Potabi Systems
        </a>
        <a href="{ISO}" class="focus:outline-none text-white bg-red-700 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">
            Free Download Desktop
        </a>
        <a href="#" class="focus:outline-none text-white bg-red-300 hover:bg-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900" disabled>
            Download Mobile
        </a>
        <a href="{ReleaseNotes}" class="focus:outline-none text-white bg-purple-700 hover:bg-purple-800 focus:ring-4 focus:ring-purple-300 font-medium rounded-lg text-sm px-5 py-2.5 mb-2 dark:bg-purple-600 dark:hover:bg-purple-700 dark:focus:ring-purple-900">
            Release Notes
        </a>
    </div>
</main>

<style></style>