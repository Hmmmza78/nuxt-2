<template>
  <div>
    <div class="row">
      <div style="border: 1px solid black" class="col-md-6 my-4">
        <MainComponentsBar />
      </div>
      <div style="border: 1px solid black" class="col-md-6 my-4">
        <!-- <ChartsLine /> -->
      </div>
      <div style="border: 1px solid black" class="col-md-6 my-4">
        <MainComponentsTable />
      </div>
      <div style="border: 1px solid black" class="col-md-6 my-4">
        <MainComponentsPie :data="chartData" :options="chartOptions" />

      </div>
      <div style="border: 1px solid black" class="col-md-6 my-4">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis
        recusandae eligendi sapiente! Vitae esse quod a, nulla, placeat ad
        inventore pariatur soluta, alias rerum sint? Maxime, accusantium
        incidunt. Atque quibusdam praesentium, doloremque fuga dignissimos
        aliquam est quia facere itaque, molestias eligendi repellendus
        architecto fugit, quam sed maiores! Dolores fugit iste cum eaque
        assumenda asperiores veritatis, atque eum explicabo facilis voluptatibus
        soluta accusantium culpa, incidunt sint tempore autem mollitia.
      </div>
      <div style="border: 1px solid black" class="col-md-6 my-4">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis
        recusandae eligendi sapiente! Vitae esse quod a, nulla, placeat ad
        inventore pariatur soluta, alias rerum sint? Maxime, accusantium
        incidunt. Atque quibusdam praesentium, doloremque fuga dignissimos
        aliquam est quia facere itaque, molestias eligendi repellendus
        architecto fugit, quam sed maiores! Dolores fugit iste cum eaque
        assumenda asperiores veritatis, atque eum explicabo facilis voluptatibus
        soluta accusantium culpa, incidunt sint tempore autem mollitia.
      </div>
    </div>
  </div>
</template>

<script>

export default {
    name: "Main",
    // components: {
    //   PieChart
    // },
    data() {
      return {
        chartOptions: {
          hoverBorderWidth: 20
        },
        chartData: {
          hoverBackgroundColor: "red",
          hoverBorderWidth: 10,
          labels: ["Green", "Red", "Blue"],
          datasets: [
            {
              label: "Data One",
              backgroundColor: ["#41B883", "#E46651", "#00D8FF"],
              data: [1, 10, 5]
            }
          ]
        }
      };
    }
  };
</script>