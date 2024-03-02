<script>
    import instagramLogo from "../images/instagram.png";
</script>

<h2>Leve a Libertah até sua cidade</h2>
<div class="contatos">
    <div class="email contact">
        <h3>Fale conosco pelo Instagram!</h3>
        <a href="https://www.instagram.com/bandalibertah/">
            <img
                src={instagramLogo}
                alt="Instagram da banda"
                title="Instagram da banda"
            />
            <span>@bandalibertah</span>
        </a>
    </div>
</div>

<style>
    h2 {
        color: var(--mid-white);
        font-size: 32px;
    }

    .contatos {
        display: flex;
        gap: 8rem;
    }

    .contact {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    h3 {
        color: var(--mid-white);
        font-size: 20px;
        font-weight: 400;
    }

    a {
        color: var(--mid-white);
        font-size: 22px;
        text-decoration: none;
        display: flex;
        align-items: center;
        gap: 0.6rem;
        transition: 0.1s;
        font-weight: 600;
    }

    a:hover {
        color: var(--low-white);
    }

    a:focus {
        color: var(--low-white);
    }

    img {
        max-width: 1.8rem;
    }

    @media (max-width: 468px) {
        h2 {
            font-size: 22px;
        }

        .contatos {
            flex-direction: column;
            gap: 1rem;
        }
    }
</style>
