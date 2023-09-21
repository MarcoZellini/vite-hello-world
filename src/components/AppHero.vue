
<script>
import AppTitle from './AppTitle.vue'

export default {

    data() {
        return {
        }
    },

    props: ['title'],
    components: {
        AppTitle
    }
}

</script>

<template>
    <div class="p-5 mb-4 bg-body-tertiary rounded-3">
        <div class="container-fluid py-5">
            <AppTitle class="text-start" :title="title" />
            <p class="col-md-8 fs-4">Using a series of utilities, you can create this jumbotron, just like the one in
                previous versions of Bootstrap. Check out the examples below for how you can remix and restyle it to your
                liking.</p>
            <button class="btn btn-primary btn-lg" type="button">Example button</button>
        </div>
    </div>
</template>