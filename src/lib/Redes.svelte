<script>
    import instagramLogo from "../images/instagram.png";
    import tiktokLogo from "../images/tik-tok.png";
    import youtubeLogo from "../images/youtube.png";
</script>

<div class="redesAqui">
    <h2>Redes Sociais</h2>
    <div class="redesList">
        <a
            href="https://www.instagram.com/bandalibertah/"
            target="_blank"
            class="instagramClass"
        >
            <img src={instagramLogo} alt="Instagam" title="Instagam" />
        </a>
        <a
            href="https://www.tiktok.com/@bandalibertah"
            target="_blank"
            class="tiktokClass"
        >
            <img src={tiktokLogo} alt="TikTok" title="TikTok" />
        </a>
        <a
            href="https://www.youtube.com/channel/UCI1ZYryfTnleRv_B3paUWAQ"
            target="_blank"
            class="youtubeClass"
        >
            <img src={youtubeLogo} alt="Youtube" title="Youtube" />
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

        transition: all 0.4s;
    }

    .redesList img {
        max-width: 32px;
    }

    .instagramClass {
        background-color: #c000a8;
        border: 2px solid #c000a8;
    }

    .instagramClass:hover {
        background: none;
        border: 2px solid var(--mid-white);
    }

    .instagramClass:focus {
        background: none;
        border: 2px solid var(--mid-white);
        outline: none;
    }

    .tiktokClass {
        background-color: #69c9d0;
        border: 2px solid #69c9d0;
    }

    .tiktokClass:focus {
        background: none;
        border: 2px solid var(--mid-white);
        outline: none;
    }

    .tiktokClass:hover {
        background: none;
        border: 2px solid var(--mid-white);
    }

    .youtubeClass {
        background-color: #ff0000;
        border: 2px solid #ff0000;
    }

    .youtubeClass:focus {
        background: none;
        border: 2px solid var(--mid-white);
        outline: none;
    }

    .youtubeClass:hover {
        background: none;
        border: 2px solid var(--mid-white);
    }

    @media (max-width: 468px) {
        h2 {
            font-size: 22px;
        }

        .redesList {
            align-items: center;
            justify-content: center;
        }

        .redesAqui {
            display: flex;
            align-items: center;
            justify-content: center;
        }
    }
</style>
