<template>
    <div class="col-xs-12 col-sm-6" v-if="selectedServer">
        <p>Server #{{ selectedServer.id }} {{ selectedServer.status }}</p>
    </div>

</template>

<script>
export default {
    props: ['selectedServer']
}
</script>

<style>

</style>
