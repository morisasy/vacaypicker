<template>
    <div class="container">
        <VacationPicker />
        <FooterComponent />

    </div>
</template>

<script>
    import VacationPicker from './components/VacationPicker'
    import FooterComponent from './components/FooterComponent'

    export default {
        name: 'app',
        components: {
            VacationPicker,
            FooterComponent
        }
    }
</script>

<style>
</style>
