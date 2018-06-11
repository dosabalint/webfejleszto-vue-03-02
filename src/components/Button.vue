<template>
    <button @click="ShowAlert()">
        {{ message }}
    </button>
</template>

<script>
export default {
    data: function() {
        return {
            message: 'Ez meg már a mi gombunk!'
        };
    },
    methods: {
        ShowAlert() {
            alert('Örvendetes!');
        }
    }
};
</script>
 
<style lang="scss" scoped>
button {
    &.btn {
        margin: 0 1rem;
    }
}
</style> 
