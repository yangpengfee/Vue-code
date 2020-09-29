<template>
<h1>{{count}}</h1>
<button @click="add">拍一下</button>
</template>

<script>
export default {
    data() {
        return {
            count: 1
        };
    },
    methods: {
        add() {
            this.count++;
        }
    }
};
</script>
