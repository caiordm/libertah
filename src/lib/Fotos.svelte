<script>
    import foto1 from "../images/foto1.jpg";
    import foto2 from "../images/foto2.jpg";
    import foto3 from "../images/foto3.jpg";
    import foto4 from "../images/foto4.jpg";
    import foto5 from "../images/foto5.jpg";
    import foto6 from "../images/foto6.jpg";
    import foto7 from "../images/foto7.jpg";
    import logo from "../images/logo.jpg";
</script>

<h2>Veja nossas fotos</h2>
<div class="fotosList">
    <img src={foto1} alt="Fotos da Libertah" class="foto1" />
    <img src={foto2} alt="Fotos da Libertah" class="foto2" />
    <img src={foto3} alt="Fotos da Libertah" class="foto3" />
    <img src={foto5} alt="Fotos da Libertah" class="foto5" />
    <img src={foto6} alt="Fotos da Libertah" class="foto6" />
    <img src={logo} alt="Fotos da Libertah" class="logo" />
    <img src={foto7} alt="Fotos da Libertah" class="foto7" />
    <img src={foto4} alt="Fotos da Libertah" class="foto4" />
</div>

<style>
    h2 {
        color: var(--mid-white);
        font-size: 32px;
    }

    .fotosList {
        display: grid;
        grid-template-columns: repeat(8, 1fr);
        grid-template-rows: repeat(7, 5vw);
        grid-gap: 15px;
    }

    img {
        width: 100%;
        height: 100%;
        object-fit: cover;
        border-radius: 12px;
        transition: all 0.4s;
    }

    img:hover {
        transform: scale(1.3, 1.3);
        box-shadow: rgb(0, 0, 0) 0px 20px 30px -10px;
    }

    img:focus {
        transform: scale(1.3, 1.3);
        box-shadow: rgb(0, 0, 0) 0px 20px 30px -10px;
    }

    .foto1 {
        grid-column-start: 1;
        grid-column-end: 4;
        grid-row-start: 1;
        grid-row-end: 5;
    }

    .foto2 {
        grid-column-start: 4;
        grid-column-end: 7;
        grid-row-start: 1;
        grid-row-end: 4;
    }

    .foto3 {
        grid-column-start: 7;
        grid-column-end: 9;
        grid-row-start: 1;
        grid-row-end: 4;
    }

    .foto4 {
        grid-column-start: 5;
        grid-column-end: 7;
        grid-row-start: 4;
        grid-row-end: 7;
    }

    .foto5 {
        grid-column-start: 7;
        grid-column-end: 9;
        grid-row-start: 4;
        grid-row-end: 7;
    }

    .foto6 {
        grid-column-start: 1;
        grid-column-end: 3;
        grid-row-start: 5;
        grid-row-end: 7;
    }

    .foto7 {
        grid-column-start: 3;
        grid-column-end: 5;
        grid-row-start: 5;
        grid-row-end: 7;
    }
</style>
