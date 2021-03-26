<template>
    <div>
        <Header :isCustom="true"></Header>
        <div class="containerPage">

            <div class="contactContent">
                <div style="padding-bottom: 2%">
                    Всего несколько шагов на пути к успеху!
                    Обратитесь к любому оператору в любой пункт технического осмотра вне зависимости от места регистрации транспортного средства!
                </div>
            </div>
            <div style="text-align: center; width: 100%; padding-bottom: 2%">
                <iframe src="https://yandex.ru/map-widget/v1/?um=constructor%3A27fa678c9be9663f3cef360bb11780181cdefd01fe13b3fb1a53579c8d9106d9&amp;source=constructor" width="100%" height="461" frameborder="0"></iframe>
            </div>
        </div>
    </div>
</template>
<script>
    import Header from '@/components/Header'


    export default {
        name: 'Contacts',
        components: {
            Header
        }
    }
</script>