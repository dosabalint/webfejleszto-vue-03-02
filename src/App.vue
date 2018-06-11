<template>
    <div>
        <h1>{{ message }}</h1>
        <Button></Button>
    </div>
</template>

<script>
import Button from './components/Button.vue';

export default {
    name: 'App',
    components: {
        Button
    },
    data: function() {
        return {
            message: 'Ez itt már a VueJS alkalmazásunk!'
        };
    }
};
</script>