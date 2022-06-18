<script lang="ts">
    //export let showModal = true;
    export let image: string | undefined = undefined;
</script>

{#if image}
    <div class="backdrop" on:click|self>
        <div class="modal">
            <div class="closing-circle" on:click>
                <img src="cross.svg" alt="">
            </div>
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
        position: relative;
    }

    .closing-circle {
        position: absolute;
        top: 12px;
        right: 12px;
        cursor: pointer;
        border-radius: 25px;
        background-color: rgba(255, 255, 255, 0.675);
        width: 2rem;
        height: 2rem;
        text-align: center;
    }

    .closing-circle img {
        width: 50%;
        height: 100%;
    }
</style>