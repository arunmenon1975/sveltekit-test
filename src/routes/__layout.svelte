<script>
    import Title from "$lib/Title.svelte";
    import  '../styles/global.css';
</script>

<header>
    <Title title="Default Title" />
</header>

<main>
    <slot></slot>
</main>

<footer>
    <p>Copyright 20202 </p>
</footer>

<style>
    header{
        display: flex;
        justify-content: center;
    }
    main{
        max-width: 960px;
        margin: 20px auto;
    }
    footer{
        text-align: center;
    }
</style>