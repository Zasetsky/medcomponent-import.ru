<template>
  <v-expansion-panels flat>
    <v-expansion-panel>
      <v-expansion-panel-header class="header-panel">
        <template v-slot:actions>
          <v-icon class="icon">$expand</v-icon>
        </template>
        <span class="header">ПРЕИМУЩЕСТВА</span>
      </v-expansion-panel-header>
      <v-expansion-panel-content>
        <p>ГТА Theratron сохраняет следующие качества:</p>
        <ul>
          <li>Простота в использовании и износостойкость;</li>
          <li>
            опыт эксплуатации ГТА Theratron с МЛК показал высокую
            надёжность работы, отсутствие поломок и простоев;
          </li>
          <li>
            При установке МЛК не требуется обучение персонала,
            только дополнительный углубленный инструктаж;
          </li>
          <li>Лечение пациентов возможно как с МЛК, так и без (снимается при необходимости).</li>
        </ul>
      </v-expansion-panel-content>
    </v-expansion-panel>

    <v-expansion-panel>
      <v-expansion-panel-header class="header-panel">
        <template v-slot:actions>
          <v-icon class="icon">$expand</v-icon>
        </template>
        <span class="header">КОМПЛЕКТ ПОСТАВКИ</span>
      </v-expansion-panel-header>
      <v-expansion-panel-content>
        <ul>
          <li>Многолепестковый коллиматор;</li>
          <li>Коллиматор с моторизированным клином;</li>
          <li>Контроллер ПК для соединения с МЛК;</li>
          <li>Лифт для установки МЛК на ГТА;</li>
          <li>3D-система планирования IMRT Prowess Panther с рабочей станцией.</li>
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
  name: 'MultileafPanels'
}
</script>

<style>

</style>
