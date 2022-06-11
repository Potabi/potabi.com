<script>
    import "./app.css"
    import "https://kit.fontawesome.com/eb07830743.js"
    import logo from "./assets/PotabiTDLogo.png"
    import Carousel from "./components/Carousel.svelte"
    import About from "./components/About.svelte"
    import Potabi from "./components/Potabi.svelte";
import Footer from "./components/Footer.svelte"
</script>

<main>
    <nav class="bg-white px-2 sm:px-4 py-2.5">
        <div class="container flex flex-wrap justify-between items-center mx-auto">
            <a href="https://plcltd.github.io" class="flex items-center" target="_blank">
                <img src="{logo}" alt="Logo" class="w-12 px-2">
                <h1 class="text-xl font-bold">Potabi</h1>
            </a>
            <div class="flex items-center">
                <a href="https://github.com/potabi"><i class="fab fa-github"></i></a>
            </div>
        </div>
    </nav>

    <Carousel />

    <About />

    <Potabi />

    <Footer />
</main>

<style></style>
