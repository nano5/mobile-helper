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
        <div class="conversation2">
            <div class="bubble2">
                111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111
            </div>
        </div>
        <div class="conversation2">
            <div class="bubble2">
                2222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222
            </div>
        </div>
        <div class="conversation1">
            <div class="bubble1">
                1111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111111
            </div>
        </div>
        <div class="conversation1">
            <div class="bubble1">
                22222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222
            </div>
        </div>
        <div class="conversation2">
            <div class="bubble2">
                bbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbb bbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbbb
                bbbbbbbbbbbbbbbbb
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
        overflow-y: auto;
        width: 100%;
    }

    .conversation2 {
        overflow-y: auto;
        width: 100%;
    }

    .conversation-box {
        margin: auto;
        width: 100%;
        overflow-y: auto;
    }

    .bubble1 {
        float: right;
        margin-top: 10%;
        color: white;
        background-color: #46ab68;
        border-radius: 25px;
        padding: 10px;
        max-width: 80%;
        overflow-wrap: break-word;
    }

    .bubble2 {
        float: left;
        margin-top: 10%;
        background-color: #e8dddc;
        border-radius: 25px;
        padding: 10px;
        max-width: 80%;
        overflow-wrap: break-word;
    }

    .wrap {
        word-wrap: break-word;
        width: 100%;
        display: inline-block;
    }
</style>
