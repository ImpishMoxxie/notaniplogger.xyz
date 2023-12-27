<script>
    import Sexcounter from "./lib/sexcounter.svelte";
    import Funnyshape from "./lib/funnyshape.svelte";
    import Kiwi from "./assets/Snapchat-1320868886.jpg"
</script>

<main>
    <center>
        <div class="funnyshape">
            <img src="https://adu.shiggy.fun/v1/712653921692155965/avatar" alt="" class="img-avatar">
            <h1 class="my-name">Moxxie</h1>
            <h1>Just your casual imp (Not a POSSUM!)</h1>
            <Funnyshape funny1 = {Kiwi}></Funnyshape>
        </div>
    </center>
</main>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Rubik+Bubbles&display=swap');

    .funnyshape{
        margin-right: 25%;
        margin-left: 25%;
        border: 0.3em solid black;
        border-radius: 25px;
    }

    .img-avatar{
        margin-top: 3%;
        border: 0.3em solid black;
        border-radius: 25px;
        display: flex;
        align-items: flex-start;
    }

    .my-name{
        font-family: "Rubik Bubbles";
        font-size: 300%;
    }
</style>