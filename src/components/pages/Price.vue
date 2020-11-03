<template>
    <div>
        <Header/>

        <div style="padding-top: 2%" class="containerPage">
            <h1 style="text-align: center; padding-bottom: 1%">Прейскурант</h1>
<!--            <table width="1024px" border="1" align="center" style="border: 1px solid black; border-collapse: collapse">-->
            <table class="priceTable" border="1" align="center">
                <tr>
                    <th class="tableOneThItem">Категория ТС по техническому регламенту</th>
                    <th>Категория транспортных средств</th>
                    <th>Стоимость работ (руб.)</th>
                </tr>
                <tr>
                    <td align="center">L 1</td>
                    <td>Мототранспортные средства</td>
                    <td align="center">160</td>
                </tr>
                <tr>
                    <td align="center">M 1</td>
                    <td>Легковые автомобили, используемые для перевозки пассажиров и имеющие, помимо места водителя, не более восьми мест для сидения.</td>
                    <td align="center">485</td>
                </tr>
                <tr>
                    <td align="center">М 2</td>
                    <td>Автобусы, используемые для перевозки пассажиров и имеющие, помимо места водителей, более восьми мест для сидения, максимальная масса которых, до  5 тонн.</td>
                    <td align="center">870</td>
                </tr>
                <tr>
                    <td align="center">М 3</td>
                    <td>Автобусы, используемые для перевозки пассажиров имеющие, помимо места водителей, более восьми мест для сидения, максимальная масса которых, более  5 тонн.</td>
                    <td align="center">1050</td>
                </tr>
                <tr>
                    <td align="center">N 1</td>
                    <td>Грузовые автомобили, предназначенные для перевозки грузов, имеющие технически допустимую максимальную массу до 3,5 тонн</td>
                    <td align="center">518</td>
                </tr>
                <tr>
                    <td align="center">N 2</td>
                    <td>Грузовые автомобили, предназначенные для перевозки грузов, имеющие технически допустимую максимальную массу от 3,5, но не более 12 тонн.</td>
                    <td align="center">1020</td>
                </tr>
                <tr>
                    <td align="center">N 3</td>
                    <td>Грузовые автомобили, предназначенные для перевозки грузов, имеющие технически допустимую максимальную массу более 12 тонн.</td>
                    <td align="center">1100</td>
                </tr>
                <tr>
                    <td align="center">О 1</td>
                    <td>Прицепы (полуприцепы), технически допустимая максимальная масса, которых не более 0,75 тонн.</td>
                    <td align="center">405</td>
                </tr>
                <tr>
                    <td align="center">О 2</td>
                    <td>Прицепы (полуприцепы), технически допустимая максимальная масса, которых свыше 0,75 тонн, но не более 3,5 тонн.</td>
                    <td align="center">405</td>
                </tr>
                <tr>
                    <td align="center">О 3</td>
                    <td>Прицепы (полуприцепы), технически допустимая максимальная масса, которых свыше 3, 5 тонн, но не более 10 тонн.</td>
                    <td align="center">710</td>
                </tr>
                <tr>
                    <td align="center">О 4</td>
                    <td>Прицепы (полуприцепы), технически допустимая максимальная масса, которых более 10 тонн.</td>
                    <td align="center">710</td>
                </tr>
            </table>
        </div>
        <div class="containerPage" style="text-align: justify; padding-top: 2%; padding-bottom: 2%">
            В Соответствии ст.18. «Проведение повторного технического осмотра» Федерального Закона № 170-ФЗ. Транспортное средство, техническое состояние которого признано не соответствующим обязательным требованиям безопасности транспортных средств, подлежит повторному техническому осмотру. При проведении повторного технического осмотра транспортного средства в срок не позднее, чем двадцать дней с момента проведения предыдущего технического осмотра осуществляется проверка транспортного средства только в отношении показателей, которые согласно диагностической карте при проведении предыдущего технического осмотра не соответствовали обязательным требованиям безопасности транспортных средств, установить следующий размер платы:
        </div>
        <div style="padding-bottom: 2%">
            <table border="1" align="center" class="priceTable" style="padding-top: 2%; padding-bottom: 2%">
                <tr>
                    <th class="tableTwoThItem"></th>
                    <th>L</th>
                    <th>М1</th>
                    <th>М2</th>
                    <th>М3</th>
                    <th>N1</th>
                    <th>N2</th>
                    <th>N3</th>
                    <th>O1 O2</th>
                    <th>O3 O4</th>
                </tr>
                <tr>
                    <td><b>Проверка тормозных систем</b></td>
                    <td align="center">40 р.</td>
                    <td align="center">100 р.</td>
                    <td align="center">160 р.</td>
                    <td align="center">310 р.</td>
                    <td align="center">110 р.</td>
                    <td align="center">260 р.</td>
                    <td align="center">310 р.</td>
                    <td align="center">90 р.</td>
                    <td align="center">310 р.</td>
                </tr>
                <tr>
                    <td><b>Проверка рулевого управления</b></td>
                    <td align="center">20 р.</td>
                    <td align="center">90 р.</td>
                    <td align="center">90 р.</td>
                    <td align="center">110 р.</td>
                    <td align="center">90 р.</td>
                    <td align="center">160 р.</td>
                    <td align="center">160 р.</td>
                    <td align="center">-</td>
                    <td align="center">-</td>
                </tr>
                <tr>
                    <td><b>Проверка внешних световых приборов</b></td>
                    <td align="center">20 р.</td>
                    <td align="center">60 р.</td>
                    <td align="center">90 р.</td>
                    <td align="center">90 р.</td>
                    <td align="center">70 р.</td>
                    <td align="center">140 р.</td>
                    <td align="center">140 р.</td>
                    <td align="center">70 р.</td>
                    <td align="center">70 р.</td>
                </tr>
                <tr>
                    <td><b>Проверка стеклоочистителя  и стеклоомывателя</b></td>
                    <td align="center">-</td>
                    <td align="center">10 р.</td>
                    <td align="center">20 р.</td>
                    <td align="center">20 р.</td>
                    <td align="center">10 р.</td>
                    <td align="center">20 р.</td>
                    <td align="center">30 р.</td>
                    <td align="center">-</td>
                    <td align="center">-</td>
                </tr>
                <tr>
                    <td><b>Проверка состояния шин и колес</b></td>
                    <td align="center">20 р.</td>
                    <td align="center">30 р.</td>
                    <td align="center">80 р.</td>
                    <td align="center">80 р.</td>
                    <td align="center">50 р.</td>
                    <td align="center">100 р.</td>
                    <td align="center">100 р.</td>
                    <td align="center">100 р.</td>
                    <td align="center">120 р.</td>
                </tr>
                <tr>
                    <td><b>Проверка двигателя и его систем</b></td>
                    <td align="center">20 р.</td>
                    <td align="center">75 р.</td>
                    <td align="center">100 р.</td>
                    <td align="center">100 р.</td>
                    <td align="center">60 р.</td>
                    <td align="center">100 р.</td>
                    <td align="center">110 р.</td>
                    <td align="center">-</td>
                    <td align="center">-</td>
                </tr>
                <tr>
                    <td><b>Проверка прочих элементов конструкции</b></td>
                    <td align="center">30 р.</td>
                    <td align="center">80 р.</td>
                    <td align="center">250 р.</td>
                    <td align="center">250 р.</td>
                    <td align="center">80 р.</td>
                    <td align="center">150 р.</td>
                    <td align="center">160 р.</td>
                    <td align="center">110 р.</td>
                    <td align="center">150 р.</td>
                </tr>
            </table>
        </div>


        <Footer/>
    </div>
</template>
<script>
    import Header from '@/components/Header'
    import Footer from '@/components/Footer'
    // import Project from '@/components/projects/BaseProject'

    export default {
        name: 'Price',
        components: {
            Header,
            // Project,
            Footer
        },
        data () {
            return {

            }
        }
    }
</script>