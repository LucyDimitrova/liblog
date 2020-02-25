<template>
    <div>
        <example-component></example-component>
    </div>
</template>

<script>
    // Imports
    import ExampleComponent from './components/ExampleComponent';


    export default {
        components: {
            'example-component': ExampleComponent
        },
        data() {
            return {}
        },
        methods: {}
    }
</script>

<style>
</style>