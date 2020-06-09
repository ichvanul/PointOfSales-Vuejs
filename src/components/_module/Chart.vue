<template>
<div class="container-chart">
  <div class="rectangle">
    <div class="notes">
      <h3>Recent Order</h3>
    </div>
    <div class="body-chart">
      <div class="value">
        <h6>INVOICES</h6>
        <p>#1101154288</p>
        <p>#1101154288</p>
        <p>#1101154288</p>
      </div>
      <div class="value">
        <h6>CASHIER</h6>
        <p>Ichvanul</p>
        <p>Vivi Alida</p>
        <p>Ryan Hidayat</p>
      </div>
      <div class="value">
        <h6>DATE</h6>
        <p>21 May 2020</p>
        <p>20 May 2020</p>
        <p>20 May 2020</p>
      </div>
      <div class="value">
        <h6>ORDERS</h6>
        <p>Coffee Latte, Steak</p>
        <p>V60, Bread</p>
        <p>Cappucino, Fried Fries</p>
      </div>
      <div class="value">
        <h6>AMOUNT</h6>
        <p>Rp. 63.000</p>
        <p>Rp. 48.000</p>
        <p>Rp. 55.000</p>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'Chart',
};
</script>

<style lang="scss" scoped>
.container-chart{
  margin: 50px 50px 50px 90px;
  .rectangle {
    background: linear-gradient(285.38deg, lightgray 30.05%, rgba(255, 143, 178, 0) 133.19%);
    border-radius: 10px;
    height: 243px;
    width: 1245px;
    padding-top: 30px;
    padding-bottom: 30px;
    .notes{
      h3{
        font-size: 20px;
        text-align: center;
      }
    }
    .body-chart{
      display: flex;
      flex-direction: row;
      justify-content: space-evenly;
    }
  }
}
</style>
