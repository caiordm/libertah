<script>
    import instagramLogo from "../images/instagram.png";
    import tiktokLogo from "../images/tik-tok.png";
</script>

<div class="redesAqui">
    <h2>Redes Sociais</h2>
    <div class="redesList">
        <a href="https://www.instagram.com/bandalibertah/" target="_blank" class="instagramClass">
            <img src={instagramLogo} alt="Instagam" title="Instagam" />
        </a>
        <a href="https://www.tiktok.com/@bandalibertah" target="_blank" class="tiktokClass">
            <img src={tiktokLogo} alt="TikTok" title="TikTok" />
        </a>
    </div>
</div>

<style>
    h2 {
        color: var(--mid-white);
        font-size: 24px;
    }

    .redesList {
        display: flex;
        align-items: start;
        justify-content: start;
        gap: 1rem;
        flex-wrap: wrap;
    }

    .redesList a {
        display: flex;
        text-decoration: none;
        padding: 0.8rem;
        width: 1.2rem;
        height: 1.2rem;
        border-radius: 50%;
        background: none;
        border: 2px solid var(--mid-white);
        transition: all 0.4s;
    }

    .redesList img {
        max-width: 32px;
    }

    .instagramClass:hover {
        background-color: #c000a8;
        border: 2px solid #c000a8;
    }

    .instagramClass:focus {
        background-color: #c000a8;
        border: 2px solid #c000a8;
        outline: none;
    }

    .tiktokClass:focus {
        background-color: #69C9D0;
        border: 2px solid #69C9D0;
        outline: none;
    }

    .tiktokClass:hover {
        background-color: #69C9D0;
        border: 2px solid #69C9D0;
    }

</style>
