<template>
    <div>
        <div id="top">
            <button>
                <<
            </button>
        </div>
        <br/>
        <div class="box">
            <div class="room" v-for="roomItem in roomItems">
                <div class="room-number-box">
                    <div class="room-number">
                        {{roomItem.roomNumber}}
                    </div>
                </div>
                <div class="room-message-box">
                    <div class="room-message-time">
                        1:27 PM
                    </div>
                    <div class="room-message">
                        message: {{roomItem.message}}asdasdasdasfadsfasdasdasdfasdfas
                        dfasdfasdfasddagdafggqergqerfasd
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                roomItems: [
                    {roomNumber: 100, message: "test0"},
                    {roomNumber: 101, message: "test1"},
                    {roomNumber: 102, message: "test2"},
                    {roomNumber: 103, message: "test3"},
                    {roomNumber: 104, message: "test4"},
                    {roomNumber: 105, message: "test5"},
                    {roomNumber: 106, message: "test6"},
                    {roomNumber: 107, message: "test7"},
                    {roomNumber: 108, message: "test8"},
                    {roomNumber: 109, message: "test9"},
                    {roomNumber: 110, message: "test10"},
                    {roomNumber: 111, message: "test11"},
                    {roomNumber: 112, message: "test12"},
                    {roomNumber: 113, message: "test13"},
                    {roomNumber: 114, message: "test14"},
                    {roomNumber: 115, message: "test15"},
                    {roomNumber: 116, message: "test16"},
                    {roomNumber: 117, message: "test17"},
                    {roomNumber: 118, message: "test18"},
                    {roomNumber: 119, message: "test19"},
                    {roomNumber: 120, message: "test20"},
                    {roomNumber: 121, message: "test21"},
                    {roomNumber: 122, message: "test22"},
                    {roomNumber: 123, message: "test23"},
                    {roomNumber: 124, message: "test24"},
                    {roomNumber: 125, message: "test25"},
                    {roomNumber: 126, message: "test26"},
                    {roomNumber: 127, message: "test27"},
                    {roomNumber: 128, message: "test28"}
                ]
            }
        },
        methods: {
            roomHeightStyle() {
                const height = screen.height;
                const els = document.getElementsByClassName("room");
                for (var i = 0; i < els.length; ++i) {
                    els[i].style.height = (height * .11).toString() + "px";
                }
            },
            topHeightStyle() {
                const height = screen.height;
                const el = document.getElementById("top");
                el.style.height = (height * .05).toString() + "px";
            }
        },
        computed: {},
        mounted() {
            this.roomHeightStyle();
            //this.topHeightStyle();
        },
        name: "PatientRooms"
    }
</script>

<style scoped>
    .box {
        overflow: auto;
        /*float: left;*/
        width: 100%;
        height: auto;
    }

    #top {
        position: fixed;
        width: 100%;
        z-index: 10;
    }

    .room {
        border-bottom: 1px solid lightgrey;
        width: 100%;
        float: left;
        clear: left;
    }

    .room-number-box {
        width: 15%;
        height: 100%;
        float: left;
    }

    .room-number {
        color: #0352fc;
        display: inline-block;
        position: relative;
        left: 50%;
        top: 50%;
        transform: translate(-50%, -50%);
    }

    .room-message-box {
        /* may need to adjust later*/
        width: 82%;
        height: 100%;
        float: left;
    }

    .room-message {
        float: none;
        display: inline-block;
        color: dimgrey;
        position: relative;
        left: 50%;
        top: 40%;
        transform: translate(-50%, -50%);
    }

    .room-message-time {
        float: right;
        color: dimgrey;
        position: relative;
        right: 20%;
        top: 10%;
        display: inline-block;
    }
</style>
