<template>
    <div class="card">
        <img src="https://picsum.photos/200" alt="prodotto">
        <h2>
            Articolo
        </h2>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Odio nostrum minus fuga omnis blanditiis magnam esse. Voluptatem, ab. Culpa consequuntur in facilis enim earum hic labore rem officia dicta voluptatem?
        </p>
        <button>
            Acquista
        </button>
    </div>
</template>

<style lang="scss" scoped>
.card {
    width: 200px;
    border: 1px solid lightgray;
    border-radius: 10px;
    padding: 20px;
    display: flex;
    flex-direction: column;
}

.card h2,
.card p {
    margin: 10px 0;
}

</style>