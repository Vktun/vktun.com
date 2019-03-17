<template>
    <b-row>
        <b-col cols="9">
            <left-top />
            <hr class="my-2">
            <p class="text-left">
                this is my firt blog website,It will share my experience and news from other resoures.

            </p>
            <left-content/>
        </b-col>
        <b-col>
            <right-top />
        </b-col>

    </b-row>
</template>
<script>
    import RightTop from './home/right/RightTop.vue'
    import LeftTop from './home/left/LeftTop.vue'
    import LeftContent from './home/left/LeftContent.vue'
    export default {
        name: "Index",
        components: {
            RightTop,
            LeftTop,
            LeftContent
        }
    };
</script>