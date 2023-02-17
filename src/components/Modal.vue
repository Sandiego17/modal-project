<template>
    <div class="backdrop">
        <div class="modal">
            <h1>Modal Title</h1>
            <p>modal content</p>
        </div>
    </div>
</template>

<style scoped>
    .modal {
        background: white;
        border-radius: 10px;
        margin: 100px auto;
        padding: 20px;
        width: 400px;
    }

    .backdrop {
        background: rgba(0, 0, 0, 0.5);
        height: 100%;
        position: fixed;
        top: 0;
        width: 100%;
    }

    h1 {
        color: #03cfb4;
        border: none;
        padding: 0;
    }
</style>