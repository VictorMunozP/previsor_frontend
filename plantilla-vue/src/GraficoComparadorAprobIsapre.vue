<template>
  <section class="container">
    <h1>Comparacion entre dos prestadores seleccionados</h1>
    <div class="columns">
      <div class="column">
        <h3>Line Chart</h3>
        <!--Line Chart Example-->
        <chartjs-bar></chartjs-bar>
      </div>
      <div class="column">
        <h3>Bar Chart</h3>
        <!--Bar Chart Example-->
        <chartjs-bar></chartjs-bar>
      </div>
    </div>
    <div class="columns">
      <div class="column">
        <h3>Radar Chart</h3>
        <!--Radar Chart Example-->
        <chartjs-radar></chartjs-radar>
      </div>
      <div class="column">
        <h3>Data Binding Line Chart</h3>
        <!--Data Binding Line Chart Example-->
        <!--form @submit.prevent="addData">
          <input placeholder="Add a Data" v-model="dataentry">
          <input placeholder="Add a Label" v-model="datalabel">
          <button type="submit">Submit</button>
        </form>
        <chartjs-line :labels="labels" :data="dataset" :bind="true"></chartjs-line-->
        <chartjs-line></chartjs-line>
      </div>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'VueCharts',
    data () {
      return {
        labels: ['January', 'February', 'March', 'April', 'May', 'June', 'July'],
        dataset: [65, 59, 80, 81, 56, 55, 40]
      }
    }
  }
</script>

<style scoped>
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }
</style>
