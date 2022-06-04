<template>
    <div>
        <h5>{{Blog[0].title}}</h5>
        <p>{{Blog[0].date}}</p>
    </div>
    <div>
        <h5>{{Blog[1].title}}</h5>
        <p>{{Blog[1].date}}</p>
    </div>
    <div>
        <h5>{{Blog[2].title}}</h5>
        <p>{{Blog[2].date}}</p>
    </div>

</template>

<script>
export default {
    name : 'list',

    props : {
        Blog : Array,
    }
}
</script>

<style>

</style>