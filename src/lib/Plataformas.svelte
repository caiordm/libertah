<script>
    import deezerLogo from "../images/deezer.png";
    import spotifyLogo from "../images/spotify.png";
    import appleMusicLogo from "../images/apple.png";
    import soundcloudLogo from "../images/soundcloud.png";
    import tiktokMusicLogo from "../images/tik-tok.png";
</script>

<h2>Nossas plataformas digitais</h2>
<div class="plataformsList">
    <a href="https://deezer.page.link/67T3ULVhEwGnKzGf6" target="_blank" class="deezerClass" title="Deezer">
        <img src={deezerLogo} alt="Deezer" />
    </a>
    <a href="https://open.spotify.com/intl-pt/artist/6TibSMRNbrQMH3r1HjObxM?si=1LZEQ8L_S8Wl0roZs7a4VQ" target="_blank"  class="spotifyClass" title="Spotify" >
        <img src={spotifyLogo} alt="Spotify" />
    </a>
    <a href="https://music.apple.com/br/artist/banda-libertah/1516525424" target="_blank" class="appleMusicClass" title="Apple Music" >
        <img src={appleMusicLogo} alt="Apple Music" />
    </a>
    <a href="https://soundcloud.com/bandalibertah" target="_blank" class="soundcloudClass" title="Soundcloud" >
        <img src={soundcloudLogo} alt="Soundcloud" />
    </a>
    <a href="https://music.tiktok.com/artist/6669910081548605442?channel=seo" target="_blank" class="tiktokMusicClass" title="TikTok Music" >
        <img src={tiktokMusicLogo} alt="TikTok Music" />
    </a>
</div>

<style>
    h2 {
        color: var(--mid-white);
        font-size: 32px;
    }

    .plataformsList {
        display: flex;
        align-items: center;
        gap: 2rem;
        flex-wrap: wrap;
    }

    .plataformsList a {
        display: flex;
        text-decoration: none;
        padding: 1rem;
        width: 2rem;
        height: 2rem;
        border-radius: 50%;
        transition: all 0.2s;
    }

    .plataformsList img {
        max-width: 48px;
    }

    .deezerClass {
        background-color: #181818;
        border: 2px solid #181818;
    }

    .deezerClass:focus {
        border: 2px solid var(--mid-white);
        outline: none;
    }

    .deezerClass:hover {
        border: 2px solid var(--mid-white);
    }

    .spotifyClass {
        background-color: #00ea5f;
        border: 2px solid #00ea5f;
    }

    .spotifyClass:focus {
        border: 2px solid var(--mid-white);
        outline: none;
    }

    .spotifyClass:hover {
        border: 2px solid var(--mid-white);
    }

    .appleMusicClass {
        background-color: #fb233c;
        border: 2px solid #fb233c;
    }

    .appleMusicClass:focus {
        border: 2px solid var(--mid-white);
        outline: none;
    }

    .appleMusicClass:hover {
        border: 2px solid var(--mid-white);
    }

    .soundcloudClass {
        background-color: #fd5400;
        border: 2px solid #fd5400;
    }

    .soundcloudClass:focus {
        border: 2px solid var(--mid-white);
        outline: none;
    }

    .soundcloudClass:hover {
        border: 2px solid var(--mid-white);
    }

    .tiktokMusicClass {
        background-color: #69C9D0;
        border: 2px solid #69C9D0;
    }

    .tiktokMusicClass:focus {
        border: 2px solid var(--mid-white);
        outline: none;
    }

    .tiktokMusicClass:hover {
        border: 2px solid var(--mid-white);
    }
</style>
