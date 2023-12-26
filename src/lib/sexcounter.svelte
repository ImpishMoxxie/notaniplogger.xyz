<script>
    let count = 0;
    function up (){
        count+=1;
    }
</script>

<main>
    <!-- svelte-ignore a11y-click-events-have-key-events -->
    <!-- svelte-ignore a11y-no-noninteractive-element-interactions -->
    <h1 on:click = {up}>Echo body count: {count}</h1>
</main>

<style>

</style>