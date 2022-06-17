<script lang="ts">
    //export let showModal = true;
    export let image: string | undefined = undefined;
</script>

{#if image}
    <div class="backdrop" on:click|self>
        <div class="modal">
            <img src="{image}" alt="">
        </div>
    </div>
{/if}


<style>
    .backdrop {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.5);
        z-index: 1;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .modal {
        padding: 6px;
        border-radius: 4px;
        margin: 20% auto;
        background-color: #fff;
    }
</style>