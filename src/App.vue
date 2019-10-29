<template>
    <div>
        <Conversation>

        </Conversation>
    </div>
</template>

<script>
    import PatientRooms from './components/PatientRooms.vue';
    import Conversation from './components/Conversation.vue';


    export default {
        components: {
            PatientRooms: PatientRooms,
            Conversation: Conversation
        },
        data() {
            return {

            };
        },
        methods: {

        },
        name: "App"
    }
</script>

<style scoped>
</style>
