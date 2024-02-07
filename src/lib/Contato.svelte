<script>
    import whatsappLogo from "../images/whatsapp.png";
    import gmailLogo from "../images/gmail.png";
</script>

<h2>Leve a Libertah até sua cidade</h2>
<div class="contatos">
    <div class="whatsapp contact">
        <h3>Whatsapp</h3>
        <a href="https://wa.me/81988777137"><img src={whatsappLogo} alt="Whatsapp" title="Whatsapp"><span>(81) 9 1234-5678</span></a>
    </div>
    <div class="email contact">
        <h3>Email</h3>
        <a href="mailto:bandalibertah@gmail.com"><img src={gmailLogo} alt="Email" title="Email"><span>bandalibertah@gmail.com</span></a>
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
        font-size: 18px;
        text-decoration: none;
        display: flex;
        align-items: center;
        gap: 0.4rem;
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
        max-width: 2rem;
    }
</style>
