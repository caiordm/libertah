<script>
    import logo from "../images/logoTransparentWhite.png";
</script>

<header>
    <img src={logo} alt="Libertah" />
</header>
<main>
    <slot />
</main>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

    :global(body) {
        font-family: 'Raleway', sans-serif;
        background-image: linear-gradient(
            to bottom,
            #0b0603,
            #0b0503,
            #0b0503,
            #0a0404,
            #0a0404,
            #0d0404,
            #100404,
            #120404,
            #170404,
            #1a0505,
            #1e0505,
            #210505
        );
        min-height: 100vh;
        padding: 0;
        margin: 0;
        margin-bottom: 4rem;
    }

    :global(html) {
        scroll-behavior: smooth;
    }

    :root {
        --low-white: #cacaca;
        --mid-white: #e7f1f5;
    }

    header {
        display: flex;
        justify-content: center;
        padding: 2rem;
    }

    header img {
        max-width: 200px;
    }

    main {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 3rem;
    }
</style>
