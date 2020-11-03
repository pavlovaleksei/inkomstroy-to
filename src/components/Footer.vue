<template>
    <div class="footer">
        <div class="footer_container">
            <div class="footer_item1" v-on:click="openAuthor" style="cursor: pointer">
                @{{getCurrentYear()}} Aleksey Pavlov
            </div>
        </div>
    </div>
</template>
<script>
    export default {
        name: 'Footer',
        methods: {
            openAuthor() {
                window.open("https://pavlovaleksei.github.io/")
            },
            getCurrentYear() {
                return new Date().getFullYear();
            }
        }
    }
</script>