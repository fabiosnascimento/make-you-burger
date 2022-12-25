<template>
    <div class="message-container">
        <p id="message-content">{{ msg }}</p>
    </div>
</template>

<script>
export default {
    name: "MessageComponent",
    props: {
        msg: String
    }
}
</script>

<style scoped>
    .message-container {
        color: #004085;
        background-color: #CCE5FF;
        border: 2px solid #B8DAFF;
        border-radius: 5px;
        padding: 10px;
        max-width: 400px;
        margin: 30px auto;
    }

    #message-content {
        padding: 0 50px;
    }
</style>
