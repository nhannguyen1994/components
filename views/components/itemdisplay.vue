<!-- TODO: Hãy viết thành một component hoàn chỉnh -->
<template lang="html">
    <div class="row">
        <div  class="col-md-4" v-for="item in itemdisplay">
        <img :src="'/public/image/' + item.photo" :alt="item.name" width="128" height="128">
        <p>{{item.name}}</p>

        </span>
    </div>

</template>

<script>
export default {
    props: ['itemdisplay']
}
</script>

<style lang="css">
</style>