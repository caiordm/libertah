<script>
    import Plataformas from "../lib/Plataformas.svelte";
    import Sobre from "../lib/Sobre.svelte";
    import Musicas from "../lib/Musicas.svelte";
    import Contato from "../lib/Contato.svelte";
    import Fotos from "../lib/Fotos.svelte";
    import Redes from "../lib/Redes.svelte";
    import Footer from "../lib/Footer.svelte";
</script>

<div class="header">
    <ul>
        <li><a href="#plataformas">Plataformas</a></li>
        <li><a href="#abanda">A Libertah</a></li>
        <li><a href="#musicas">Músicas</a></li>
        <li><a href="#contato">Contato</a></li>
        <li><a href="#fotos">Fotos</a></li>
        <li><a href="#redes">Redes</a></li>
    </ul>
</div>

<section id="plataformas">
    <Plataformas />
</section>

<section id="abanda">
    <Sobre />
</section>

<section id="musicas">
    <Musicas />
</section>

<section id="contato">
    <Contato />
</section>

<section id="fotos">
    <Fotos />
</section>

<section id="redes">
    <Redes />
    <Footer />
</section>

<style>
    .header ul {
        display: flex;
        gap: 2rem;
        flex-wrap: wrap;
    }

    .header ul li {
        list-style: none;
    }

    a {
        text-decoration: none;
        color: var(--mid-white);
        font-size: 24px;
    }

    a:hover {
        border-bottom: solid 1px var(--low-white);
        color: var(--low-white);
    }

    a:focus {
        border-bottom: solid 1px var(--low-white);
        color: var(--low-white);
        outline: none;
    }

    section {
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    #plataformas {
        gap: 1rem;
        transition: all 2s;
    }

    #musicas {
        width: 60%;
    }

    #fotos {
        width: 65%;
    }

    #redes {
        width: 65%;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: start;
    }

    @media(max-width: 468px) {
        .header {
            max-width: 80%;
        }
        ul {
            justify-content: center;
            padding-left: 0;
        }

        a {
            font-size: 16px;
        }

        #musicas {
            max-width: 90%;
        }

        #redes {
            flex-direction: column;
            align-items: center;
            justify-content: center;
            gap: 2rem;
        }
    }
</style>
