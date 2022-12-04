<template>
  <div class="main">
    <div class="title">S T A T I S T I C S.</div>
    <div class="flex">
      <div class="small-box box">
        <img src="~/assets/icons/cpu-light.png" alt="" />
        <div class="stats">
          <div>temp</div>
          <span class="blue">65.3 °C</span>
          <div>speed</div>
          <span class="blue">3.4 GHZ</span>
        </div>
      </div>
      <div class="small-box box">
        <img src="~/assets/icons/ram-light.png" alt="" />
        <div class="stats">
          <div>usage</div>
          <span class="blue">12.3/32 GB</span>
          <div>speed</div>
          <span class="blue">3200 MHZ</span>
        </div>
      </div>
      <div class="wide-box box">
        <img src="~/assets/icons/tasks-light.png" alt="" />

        <div class="stats">
          <table>
            <tr>
              <td>task</td>
              <td>cpu %</td>
              <td>ram %</td>
            </tr>
            <tr>
              <td class="blue">CS:GO</td>
              <td>12.3%</td>
              <td>2.5%</td>
            </tr>
            <tr>
              <td class="blue">server.jar</td>
              <td>144.3%</td>
              <td>2222%</td>
            </tr>
            <tr>
              <td class="blue">minecraft launcher</td>
              <td>12.3%</td>
              <td>2.5%</td>
            </tr>
          </table>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
</style>


<script>
export default {};
</script>