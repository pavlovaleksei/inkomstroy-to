<template>
    <div>
        <Header></Header>
        <div style="padding-top: 2%" class="containerPage">
            <h1 style="text-align: center">
                Законодательство
            </h1>
            <div>
                <div style="padding-top: 5%">
                    <a href="http://inkomstroy-to.ru/public/docs/fz-170.pdf" target="_blank" style="font-size: 20px">
                        - Федеральный закон от 1 июля 2011г. N170-ФЗ
                        "О техническом осмотре транспортных средств и о внесении изменений в
                        отдельные законодательные акты Российской Федерации"
                    </a>
                </div>
                <div style="padding-top: 5%">
                    <a href="https://autoins.ru/tekhosmotr/zakonodatelstvo/" target="_blank" style="font-size: 20px">
                        - Законодательство в сфере технического осмотра
                    </a>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    import Header from '@/components/Header'

    export default {
        name: 'Lay',
        components: {
            Header
        }
    }
</script>