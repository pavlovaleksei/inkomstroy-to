<template>
    <div>
        <div class="menu">
            <nav>
                <a style="cursor: pointer" v-on:click="clickMenuItem({'about': true, 'price': false, 'lay': false, 'contacts': false})">Автовладельцам</a>
              <!-- 16-03-2022 Telegram Леш, когда будешь делать, убери, пожалуйста, аттестат аккредитации и прайс. Спасибо большое тебе! -->
<!--                <p>|</p>-->
<!--                <a style="cursor: pointer" v-on:click="clickMenuItem({'about': false, 'price': true, 'lay': false, 'contacts': false})">Прайс</a>-->
                <p>|</p>
                <a style="cursor: pointer" v-on:click="clickMenuItem({'about': false, 'price': false, 'lay': true, 'contacts': false})">Законодательство</a>
                <p>|</p>
                <a style="cursor: pointer" v-on:click="clickMenuItem({'about': false, 'price': false, 'lay': false, 'contacts': true})">Контакты</a>
            </nav>
        </div>
        <car-owners v-if="isShow.about"></car-owners>
        <price v-if="isShow.price"></price>
        <lay v-if="isShow.lay"></lay>
        <contacts v-if="isShow.contacts"></contacts>
    </div>
</template>
<script>
    import carOwners from '@/components/pages/CarOwners'
    import price from '@/components/pages/Price'
    import lay from '@/components/pages/Lay'
    import contacts from '@/components/pages/Contacts'

    export default {
        name: 'Main',

        components: {
            carOwners,
            price,
            lay,
            contacts
        },

        data() {
            return {
                isShow: {
                    about: true,
                    price: false,
                    lay: false,
                    contacts: false
                }
            }
        },
        methods: {
            clickMenuItem(obj) {
                this.isShow = obj;
            }
        }
    }
</script>