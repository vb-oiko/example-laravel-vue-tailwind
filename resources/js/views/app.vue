<template>
    <div class="message">
        {{ message }}
    </div>
</template>

<script>
const default_layout = "default";

export default {
    computed: {},
    data() {
        return {
            message: "Hello World"
        };
    }
};
</script>

<style scoped>
.message {
    @apply text-blue font-3xl font-bold text-center pt-10;
}
</style>
