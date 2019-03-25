<!--     ./src/pages/Home.vue      -->

<template>
    <div>
        <div class="title">
            <h1>{{msg}}</h1>
        </div>
    </div>
</template>

<script>
export default {
    name: 'home',
    data () {
        return {
            msg: 'Velkommen til min webshop'
        }
    }
}
</script>