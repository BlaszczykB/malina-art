<script lang="ts">
    import Modal from '../lib/modal.svelte';
    let selectedImage = ''

    let imagesLit = [
        'malwina.png',
        'malwina.png',
        'malwina.png',
        'malwina.png',
        'malwina.png',
        'malwina.png',
    ]
</script>

<Modal image="{selectedImage}" on:click={() => {selectedImage = ''}}/>

<div class="gallery">
    <div class="image-container content-sizing">
        {#each imagesLit as image, i}
        <img src="{image}" alt="" on:click={() => {selectedImage = image}}>
        {/each}
    </div>
</div>



<style>
    .gallery {
        background-color: var(--color3);
        height: calc(100vh - var(--header-height));
    }
    .image-container {
        padding: 3rem 0;
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        grid-auto-rows: 0.2fr;
        /* grid-gap: 10px;
        column-gap: 10px; */
        gap: 2rem 3rem;
        background-color: var(--color3);
    }

    img {
        width: 100%;
        height: auto;
        border-radius: 10px;
    }
</style>