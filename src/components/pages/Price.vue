<template>
    <div>
        <Header/>
        <div style="padding-top: 2%" class="containerPage">
            <h1 style="text-align: center; padding-bottom: 1%">Прейскурант</h1>
            <div class="containerPage" style="text-align: right; padding-top: 1%; padding-bottom: 2%">
              Стоимость указана без учёта НДС.
            </div>
            <table class="priceTable" border="1" align="center">
                <tr>
                    <th class="tableOneThItem">Категория ТС по техническому регламенту</th>
                    <th>Категория транспортных средств</th>
                    <th>Стоимость работ (руб.)</th>
                </tr>
                <tr>
                    <td align="center">M1</td>
                    <td>Транспортные средства, используемые для перевозки пассажиров и имеющие, помимо места водителя, не более 8 мест для сидения легковые автомобили</td>
                    <td align="center">1097</td>
                </tr>
                <tr>
                    <td align="center">М2</td>
                    <td>Транспортные средства, используемые для перевозки пассажиров, имеющие, помимо места водителя, более 8 мест для сидения, технически допустимая максимальная масса которых не превышает 5 тонн</td>
                    <td align="center">1879</td>
                </tr>
                <tr>
                    <td align="center">М3</td>
                    <td>Транспортные средства, используемые для перевозки пассажиров, имеющие, помимо места водителя, более 8 мест для сидения, технически допустимая максимальная масса которых превышает 5 тонн</td>
                    <td align="center">2269</td>
                </tr>
                <tr>
                    <td align="center">N1</td>
                    <td>Транспортные средства, предназначенные для перевозки грузов, имеющие технически допустимую максимальную массу не более 3.5 тонны</td>
                    <td align="center">1200</td>
                </tr>
                <tr>
                    <td align="center">N2</td>
                    <td>Транспортные средства, предназначенные для перевозки грузов, имеющие технически допустимую максимальную массу свыше 3,5 тонны, но не более 12 тонн</td>
                    <td align="center">2189</td>
                </tr>
                <tr>
                    <td align="center">N3</td>
                    <td>Транспортные средства, предназначенные для перевозки грузов, имеющие технически допустимую максимальную массу более 12 тонн</td>
                    <td align="center">2364</td>
                </tr>
<!--                <tr>-->
<!--                    <td align="center">О1</td>-->
<!--                    <td>Прицепы (полуприцепы), технически допустимая максимальная масса, которых не более 0,75 тонн.</td>-->
<!--                    <td align="center">420</td>-->
<!--                </tr>-->
<!--                <tr>-->
<!--                    <td align="center">О2</td>-->
<!--                    <td>Прицепы (полуприцепы), технически допустимая максимальная масса, которых свыше 0,75 тонн, но не более 3,5 тонн.</td>-->
<!--                    <td align="center">420</td>-->
<!--                </tr>-->
                <tr>
                    <td align="center">О3, O4</td>
                    <td>Прицепы, технически допустимая максимальная масса которых свыше 3,5 тонны, но не более 10 тонн, и прицепы, технически допустимая максимальная масса которых более 10 тонн</td>
                    <td align="center">1529</td>
                </tr>
                <tr>
                    <td align="center">L</td>
                    <td>Мототранспортные средства</td>
                    <td align="center">385</td>
                </tr>
                <tr>
                  <td align="center">M1</td>
                  <td>Специальные транспортные средства оперативных служб</td>
                  <td align="center">1170</td>
                </tr>
                <tr>
                  <td align="center">M2</td>
                  <td>Специальные транспортные средства оперативных служб</td>
                  <td align="center">1879</td>
                </tr>
                <tr>
                  <td align="center">M3</td>
                  <td>Специальные транспортные средства оперативных служб</td>
                  <td align="center">2144</td>
                </tr>
                <tr>
                  <td align="center">N1</td>
                  <td>Специальные транспортные средства оперативных служб, цистерны, цистерны для перевозки и заправки сжиженных углеводородных газов, фургоны, фургоны, имеющие места для перевозки людей, автоэвакуаторы</td>
                  <td align="center">1276</td>
                </tr>
                <tr>
                  <td align="center">N2</td>
                  <td>Специальные транспортные средства оперативных служб, автоэвакуаторы, транспортные средства с грузоподъемными устройствами, цистерны, цистерны для перевозки и заправки сжиженных углеводородных газов, фургоны, транспортные средства для перевозки пищевых продуктов</td>
                  <td align="center">2294</td>
                </tr>
                <tr>
                  <td align="center">N3</td>
                  <td>Специальные транспортные средства оперативных служб, автоэвакуаторы, транспортные средства с грузоподъемными устройствами, цистерны, цистерны для перевозки и заправки сжиженных углеводородных газов, фургоны, транспортные средства для перевозки пищевых продуктов</td>
                  <td align="center">2468</td>
                </tr>
                <tr>
                  <td align="center">O3, O4</td>
                  <td>Специальные транспортные средства оперативных служб, автоэвакуаторы, транспортные средства с грузоподъемными устройствами, цистерны, цистерны для перевозки и заправки сжиженных углеводородных газов, фургоны, транспортные средства для перевозки пищевых продуктов</td>
                  <td align="center">1599</td>
                </tr>
                <tr>
                  <td align="center">L</td>
                  <td>Специальные транспортные средства оперативных служб</td>
                  <td align="center">424</td>
                </tr>
                <tr>
                  <td align="center">N1</td>
                  <td>Специализированные транспортные средства, цистерны для перевозки и заправки нефтепродуктов</td>
                  <td align="center">1388</td>
                </tr>
                <tr>
                  <td align="center">N2</td>
                  <td>Специализированные транспортные средства, цистерны для перевозки и заправки нефтепродуктов, транспортные средства фургоны, имеющие места для перевозки людей</td>
                  <td align="center">2500</td>
                </tr>
                <tr>
                  <td align="center">N3</td>
                  <td>Специализированные транспортные средства, фургоны, имеющие места для перевозки людей, цистерны для перевозки и заправки нефтепродуктов</td>
                  <td align="center">2711</td>
                </tr>
                <tr>
                  <td align="center">O3, O4</td>
                  <td>Специализированные транспортные средства</td>
                  <td align="center">1772</td>
                </tr>
                <tr>
                  <td align="center">N1</td>
                  <td>Специальные транспортные средства для коммунального хозяйства и содержания дорог</td>
                  <td align="center">1314</td>
                </tr>
                <tr>
                  <td align="center">N2</td>
                  <td>Специальные транспортные средства для коммунального хозяйства и содержания дорог, транспортные средства для перевозки грузов с использованием прицепа-роспуска</td>
                  <td align="center">2397</td>
                </tr>
                <tr>
                  <td align="center">N3</td>
                  <td>Специальные транспортные средства для коммунального хозяйства и содержания дорог, транспортные средства для перевозки грузов с использованием прицепа-роспуска</td>
                  <td align="center">2607</td>
                </tr>
                <tr>
                  <td align="center">O3, O4</td>
                  <td>Специальные транспортные средства для коммунального хозяйства содержания дорог, транспортные средства - цистерны для перевозки и заправки нефтепродуктов</td>
                  <td align="center">1669</td>
                </tr>
                <tr>
                  <td align="center">N1</td>
                  <td>Транспортные средства для перевозки опасных грузов</td>
                  <td align="center">1576</td>
                </tr>
                <tr>
                  <td align="center">N2</td>
                  <td>Транспортные средства для перевозки опасных грузов</td>
                  <td align="center">2849</td>
                </tr>
                <tr>
                  <td align="center">N3</td>
                  <td>Транспортные средства для перевозки опасных грузов</td>
                  <td align="center">3059</td>
                </tr>
                <tr>
                  <td align="center">O3, O4</td>
                  <td>Транспортные средства для перевозки опасных грузов</td>
                  <td align="center">1842</td>
                </tr>
            </table>
        </div>
        <div class="containerPage" style="text-align: justify; padding-top: 1%; padding-bottom: 2%">
          <i>* Категории транспортных средств соответствуют классификации, установленной в приложении No 1 к техническому регламенту Таможенного союза «О безопасности колесных транспортных средств» (ТР ТС 018/2011).</i>
        </div>
        <div class="containerPage" style="text-align: justify; padding-top: 2%; padding-bottom: 2%">
            В Соответствии ст.18. «Проведение повторного технического осмотра» <a href="http://inkomstroy-to.ru/public/docs/fz-170.pdf" target="_blank">Федерального Закона № 170-ФЗ</a>. Транспортное средство, техническое состояние которого признано не соответствующим обязательным требованиям безопасности транспортных средств, подлежит повторному техническому осмотру. При проведении повторного технического осмотра транспортного средства в срок не позднее, чем двадцать дней с момента проведения предыдущего технического осмотра осуществляется проверка транспортного средства только в отношении показателей, которые согласно диагностической карте при проведении предыдущего технического осмотра не соответствовали обязательным требованиям безопасности транспортных средств, установить следующий размер платы:
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
<!--                    <th>O1 O2</th>-->
                    <th>O3 O4</th>
                </tr>
                <tr>
                    <td><b>Проверка тормозных систем</b></td>
                    <td align="center">50 р.</td>
                    <td align="center">200 р.</td>
                    <td align="center">250 р.</td>
                    <td align="center">450 р.</td>
                    <td align="center">200 р.</td>
                    <td align="center">250 р.</td>
                    <td align="center">450 р.</td>
<!--                    <td align="center">100 р.</td>-->
                    <td align="center">450 р.</td>
                </tr>
                <tr>
                    <td><b>Проверка рулевого управления</b></td>
                    <td align="center">50 р.</td>
                    <td align="center">200 р.</td>
                    <td align="center">250 р.</td>
                    <td align="center">250 р.</td>
                    <td align="center">250 р.</td>
                    <td align="center">250 р.</td>
                    <td align="center">250 р.</td>
<!--                    <td align="center">-</td>-->
                    <td align="center">-</td>
                </tr>
                <tr>
                    <td><b>Проверка внешних световых приборов</b></td>
                    <td align="center">50 р.</td>
                    <td align="center">150 р.</td>
                    <td align="center">150 р.</td>
                    <td align="center">150 р.</td>
                    <td align="center">150 р.</td>
                    <td align="center">150 р.</td>
                    <td align="center">150 р.</td>
<!--                    <td align="center">100 р.</td>-->
                    <td align="center">150 р.</td>
                </tr>
                <tr>
                    <td><b>Проверка стеклоочистителя  и стеклоомывателя</b></td>
                    <td align="center">-</td>
                    <td align="center">50 р.</td>
                    <td align="center">50 р.</td>
                    <td align="center">50 р.</td>
                    <td align="center">50 р.</td>
                    <td align="center">50 р.</td>
                    <td align="center">50 р.</td>
<!--                    <td align="center">-</td>-->
                    <td align="center">-</td>
                </tr>
                <tr>
                    <td><b>Проверка состояния шин и колес</b></td>
                    <td align="center">50 р.</td>
                    <td align="center">100 р.</td>
                    <td align="center">100 р.</td>
                    <td align="center">100 р.</td>
                    <td align="center">100 р.</td>
                    <td align="center">100 р.</td>
                    <td align="center">100 р.</td>
<!--                    <td align="center">100 р.</td>-->
                    <td align="center">100 р.</td>
                </tr>
                <tr>
                    <td><b>Проверка двигателя и его систем</b></td>
                    <td align="center">50 р.</td>
                    <td align="center">150 р.</td>
                    <td align="center">150 р.</td>
                    <td align="center">150 р.</td>
                    <td align="center">150 р.</td>
                    <td align="center">150 р.</td>
                    <td align="center">150 р.</td>
<!--                    <td align="center">-</td>-->
                    <td align="center">-</td>
                </tr>
                <tr>
                    <td><b>Проверка прочих элементов конструкции</b></td>
                    <td align="center">50 р.</td>
                    <td align="center">150 р.</td>
                    <td align="center">300 р.</td>
                    <td align="center">300 р.</td>
                    <td align="center">150 р.</td>
                    <td align="center">300 р.</td>
                    <td align="center">300 р.</td>
<!--                    <td align="center">150 р.</td>-->
                    <td align="center">150 р.</td>
                </tr>
            </table>
        </div>
      <div class="containerPage" style="text-align: justify; padding-top: 2%; padding-bottom: 2%">
        Выдача дубликата диагностической карты - 100р
      </div>


        <Footer/>
    </div>
</template>
<script>
    import Header from '@/components/Header'
    import Footer from '@/components/Footer'

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