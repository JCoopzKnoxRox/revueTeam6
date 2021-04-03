

<template>

    <div class="hello">
        <h1>{{ msg }}</h1>
    </div>
</template>

<style>
h1 {text-align: center;}
</style>

<script>
    export default {
        name: 'Time',
        data () {
          var today = new Date();
          var time = today.getHours() + ":" + today.getMinutes() + ":" + today.getSeconds();
            return {
                msg: time
            }
        }
    }
</script>