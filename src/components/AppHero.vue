<script>

</script>

<template>
    <div class="jumbo">
        <h2>Titolo del Jumbohero</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Error veniam, ipsum vero quam accusantium commodi itaque
            quisquam odio consectetur totam accusamus, obcaecati suscipit expedita iure impedit eveniet dicta autem quod!
        </p>
        <img src="/public/vite.svg">
    </div>
</template>

<style>
.jumbo {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 1em;

    padding: 1em;

    background: #4d4c4c;
}

.jumbo img {
    width: 100px;
    cursor: pointer;
    margin: 3.5em 0;
}

.jumbo img:hover {
    filter: drop-shadow(2px 2px 40px rgba(255, 208, 39, 0.587));
    scale: 1.01;
}
</style>