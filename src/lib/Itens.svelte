<script>
    import bottoms from "../images/bottoms.jpg";
</script>

<h2>Nossos itens</h2>
<div class="itensList">
    <div class="item">
        <img src={bottoms} alt="Bottoms" />
        <span>Bottom Logo</span>
        <a href="#itens" id="ver-mais">Em breve...</a>
    </div>
</div>

<style>
    h2 {
        color: var(--mid-white);
        font-size: 32px;
    }

    .item {
        display: flex;
        flex-direction: column;
        gap: 1rem;
        align-items: flex-start;
        width: 20%;
    }

    .item img {
        width: 100%;
        aspect-ratio: 1 / 1;
        object-fit: cover;
        border-radius: 12px;
        box-shadow: rgb(0, 0, 0) 0px 10px 10px -10px;
    }

    span {
        font-size: 20px;
        color: var(--mid-white);
        font-weight: 600;
    }

    #ver-mais {
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: transparent;
        border: 2px solid var(--mid-white);
        border-radius: 10px;
        text-decoration: none;
        color: var(--mid-white);
        font-weight: 500;
        padding: 0.6rem 0rem;
        width: 100%;
        transition: 0.2s all;
    }

    #ver-mais:hover {
        color: var(--main-brown);
        background-color: var(--mid-white);
    }

    #ver-mais:focus {
        color: var(--main-brown);
        background-color: var(--mid-white);
    }

    @media (max-width: 500px) {
        h2 {
            font-size: 22px;
        }

        .itensList {
            gap: 10px;
        }

        .item {
            width: 32%;
            gap: 0.6rem;
        }

        span {
            font-size: 14px;
        }

        #ver-mais {
            font-size: 12px;
        }
    }
</style>
