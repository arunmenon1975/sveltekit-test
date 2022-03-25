<script>
   export let title = "Page Title"
</script>
<div class="title">
    <img src="/svelte-welcome.png" alt="Logo" />
    <h1> {title} </h1>
</div>

<style>
    .title {
        display: flex;
    }
    .title img {
        max-width: 200px;
        display: inline-block;
        filter: invert(88%) sepia(18%) saturate(86%) hue-rotate(199deg) brightness(100%) contrast(98%);
    }
    .title h1 {
        margin-left: 10px;
    }
</style>