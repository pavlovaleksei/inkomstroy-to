<template>
    <div>
        <Header></Header>
        <div class="containerPage">
            <IndexText></IndexText>
        </div>
    </div>
</template>
<script>
    import Header from '@/components/Header'
    import IndexText from '@/components/pages/about/IndexText'

    export default {
        name: 'CarOwners',
        components: {
            Header,
            IndexText
        }
    }
</script>