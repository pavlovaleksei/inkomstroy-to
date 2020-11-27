<template>
    <div>
        <div class="header" v-if="isCustom">
            <div class="header_content">
                <div>
                    <div class="customeHeaderContentOne">
                        ТЕХОСМОТР В ИНКОМСТРОЙ
                    </div>
                    <div class="customeHeaderContentTwo">
                        Высокотехнологично, качественно, быстро
                    </div>
                </div>
                <div>
                    <div class="containerPage">
                        <div style="color: black; text-align: left"><b>ООО "Инкомстрой-ТО"</b></div>
                        <div style="display: flex; color: black;">
                            <div style="">Адрес:</div>
                            <div style="padding-left: 1%">410036, Россия, г. Саратов, ул. Ново-Астраханское шоссе, д. 73</div>
                        </div>
                        <div style="display: flex; color: black;">
                            <div style="">Рабочий телефон:</div>
                            <div style="padding-left: 1%">+7 8452 94-05-56</div>
                        </div>
                        <div style="display: flex; color: black;">
                            <div style="">E-mail:</div>
                            <div style="padding-left: 1%">inkomto@yandex.ru</div>
                        </div>
                        <div style="display: flex; color: black;">
                            <div style="">График работы:</div>
                            <div style="padding-left: 1%; text-align: left">пн-пт: 08.30 - 17.00<br>сб: 09.00 - 13.00<br>вс: выходной<br>обед: 13.00 - 14.00</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="header" v-if="!isCustom">
            <div class="header_content">
                <img class="header_image" alt="Photo" src="../assets/logotype.png">
                <div>
                    <div class="containerPage">
                        <div style="color: black; text-align: left"><b>ООО "Инкомстрой-ТО"</b></div>
                        <div style="display: flex; color: black;">
                            <div style="">Адрес:</div>
                            <div style="padding-left: 1%; text-align: left">410036, Россия, г. Саратов, ул. Ново-Астраханское шоссе, д. 73</div>
                        </div>
                        <div style="display: flex; color: black;">
                            <div style="">Рабочий телефон:</div>
                            <div style="padding-left: 1%">+7 8452 94-05-56</div>
                        </div>
                        <div style="display: flex; color: black;">
                            <div style="">E-mail:</div>
                            <div style="padding-left: 1%">inkomto@yandex.ru</div>
                        </div>
                        <div style="display: flex; color: black;">
                            <div style="">График работы:</div>
                            <div style="padding-left: 1%; text-align: left">пн-пт: 08.30 - 17.00<br>сб: 09.00 - 13.00<br>вс: выходной<br>обед: 13.00 - 14.00</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    export default {
        name: 'Header',
        props: {
            isCustom: {
                type: Boolean,
                default: false
            }
        },
        data() {
            return {
                msg: {
                    projectTitle: "Прейскурант"
                }
            }
        }
    }
</script>