<template>
  <v-expansion-panels flat>
    <v-expansion-panel>
      <v-expansion-panel-header class="header-panel">
        <template v-slot:actions>
          <v-icon class="icon">$expand</v-icon>
        </template>
        <span class="header">БАЗОВАЯ КОМПЛЕКТАЦИЯ АППАРАТА</span>
      </v-expansion-panel-header>
      <v-expansion-panel-content>
        <ul>
          <li>Основная рама с механизмом вращения гентри и противовесом;</li>
          <li>Гентри с диапазоном вращения 360°;</li>
          <li>Радиационная головка с механизмом перемещения источника;</li>
          <li>Коллиматор;</li>
          <li>Источник ионизирующего излучения на основе изотопа кобальт-60 с капсулой типа С-146 и транспортным контейнером F147</li>
          <li>Система лазерных центраторов;</li>
          <li>Терапевтический стол для укладки пациентов;</li>
          <li>Автоматизированное рабочее место оператора с программным обеспечением;</li>
          <li>Устройство радиационного дозиметрического контроля с сигнализирующим блоком.</li>
        </ul>
      </v-expansion-panel-content>
    </v-expansion-panel>

    <v-expansion-panel>
      <v-expansion-panel-header class="header-panel">
        <template v-slot:actions>
          <v-icon class="icon">$expand</v-icon>
        </template>
        <span class="header">ПРОИЗВОДИТЕЛЬ</span>
      </v-expansion-panel-header>
      <v-expansion-panel-content>
        <ul>
          <a href="http://www.theratronics.ca/index.html">Best Theratronics ltd., Канада.</a>
        </ul>
      </v-expansion-panel-content>
    </v-expansion-panel>
  </v-expansion-panels>
</template>

<script>
export default {
  name: 'TheratronPanels'
}
</script>

<style>

</style>
