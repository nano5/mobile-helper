<template>
    <div class="conversation-box">
        <div class="conversation1">
            <div class="bubble1">
                How was your day
            </div>
        </div>
        <div class="conversation2">
            <div class="bubble2">
                yo what is going on
            </div>
        </div>
        <div class="conversation1">
            <div class="bubble1">
                sup my name is big boi
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Conversation"
    }
</script>

<style scoped>
    .conversation1 {
        float: left;
        position: relative;
        margin-top: 10%;
        width: 100%;
    }
    .conversation2 {
        float: right;
        position: relative;
        margin-top: 10%;
    }

    .conversation-box {
        margin: auto;
        width: 100%;
        overflow-y: auto;
        overflow-x: hidden;
    }

    .bubble1 {
        color: white;
        display: inline-block;
        background-color: #46ab68;
        border-radius: 25px;
        padding: 10px;
    }

    .bubble2 {
        display: inline-block;
        background-color: #e8dddc;
        border-radius: 25px;
        padding: 10px;
    }
</style>
