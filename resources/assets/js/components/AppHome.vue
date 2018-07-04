<template>
    <div>
        <app-toolbar></app-toolbar>
        <app-slider></app-slider>
        <app-content></app-content>
        <app-footer></app-footer>
    </div>
</template>

<script>
import AppToolbar from './AppToolbar'
import AppSlider from './AppSlider'
import AppContent from './AppContent'
import AppFooter from './AppFooter'

export default {
    components:{AppToolbar, AppSlider, AppContent, AppFooter}
}
</script>

<style>

</style>
