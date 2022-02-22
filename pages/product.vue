<template>
  <v-container fluid>
    <v-layout row wrap>
      <v-tabs
        color="deep-purple accent-4"
        right
      >
        <v-tab>Theratron Equinox 80/100</v-tab>
        <v-tab>Многолепестковый коллиматор для Theratron Equinox</v-tab>
        <v-tab>ЗРИ на основе изотопа кобальт-60</v-tab>

        <v-tab-item>
          <v-container fluid>
            <v-img
              class="float-right mt-10 ml-10"
              max-height="400"
              max-width="700"
              src="http://www.teambest.in/wp-content/uploads/2017/07/teletherapyimg.jpg"
            />
          </v-container>
          <v-container
            fluid
          >
            <v-card-title>
              Гамма-терапевтический аппарат Theratron Equinox 80/100
            </v-card-title>
            <v-card-text>
              <p>
                Гамма-терапевтический аппарат Theratron Equinox предназначен для лечения онкологических заболеваний
                с помощью пучка гамма излучения от радионуклидного источника кобальт-60 методом дистанционной лучевой терапии.
              </p>
              <p>
                Радиоактивный источник Со-60 с активностью до 12 000 Кюри позволяет снизить время одного сеанса облучения до 10 мин.
                На аппарате с легкостью реализуются современные методики конформного облучения,
                а совместимость с компьютеризированной информационно-управляющей системой повышает точность выполнения плана лечения.
              </p>
              <v-row>
                <TheratronPanels />
              </v-row>
            </v-card-text>
          </v-container>
        </v-tab-item>

        <v-tab-item>
          <v-container fluid>
            <v-img
              class="float-right mt-10 ml-10"
              src="http://www.teambest.in/wp-content/uploads/2017/07/gammacoimg.jpg"
            />
          </v-container>
          <v-container
            fluid
          >
            <v-card-title>
              Многолепестковый коллиматор для гамма- терапевтического аппарата Theratron Equinox
            </v-card-title>
            <v-card-text>
              <p>
                Многолепестковый коллиматор с 60 лепестками от компании Best Theratronics (МЛК)
                разработан специально для использования на аппаратах Equinox 100.
              </p>
              <p>
                МЛК позволяет реализовывать методики 3D конформной лучевой терапии (3D CRT)
                и лучевой терапии с модулированной интенсивностью (IMRT), оплачиваемые по тарифам ВМП.
              </p>
              <p>
                Система МЛК легко интегрируется в рабочую сеть лечебного учреждения посредством Dicom RT.
              </p>
              <v-row>
                <MultileafPanels />
              </v-row>
            </v-card-text>
          </v-container>
        </v-tab-item>
      </v-tabs>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: 'ProductPage',
  data: () => ({
    items: [
      {
        id: 1,
        name: 'БАЗОВАЯ КОМПЛЕКТАЦИЯ АППАРАТА :',
        children: [
          { id: 2, name: 'основная рама с механизмом вращения гентри и противовесом;' },
          { id: 3, name: 'гентри с диапазоном вращения 360°;' },
          { id: 4, name: 'радиационная головка с механизмом перемещения источника;' },
          { id: 5, name: 'коллиматор;' },
          { id: 6, name: 'источник ионизирующего излучения на основе изотопа кобальт-60 с капсулой типа С-146 и транспортным контейнером F147;' },
          { id: 7, name: 'система лазерных центраторов;' },
          { id: 8, name: 'терапевтический стол для укладки пациентов;' },
          { id: 9, name: 'автоматизированное рабочее место оператора с программным обеспечением;' },
          { id: 10, name: 'устройство радиационного дозиметрического контроля с сигнализирующим блоком.' }
        ]
      }
    ]
  })
}
</script>
<style lang="scss" scoped>

</style>
