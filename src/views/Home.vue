<template>
  <div class="home">
    <div class="container">
      <!-- nav -->
      <div class="navigation">
        <div class="nav">
          <div class="content-nav">
            <div class="number-nav-current">
              <p style="font-weight: bold; color: white">1</p>
            </div>
            <p style="font-weight: bold; color: #ff8a00; margin-left: 10px">Delivery</p>
          </div>
          <i class="fas fa-chevron-right" style="color: #ff8a00"></i>
          <div class="content-nav">
            <div class="number-nav">
              <p style="font-weight: bold; color: #ff8a00">2</p>
            </div>
            <p style="font-weight: bold; color: #ff8a00; margin-left: 10px">Payment</p>
          </div>
          <i class="fas fa-chevron-right" style="color: #ff8a00"></i>
          <div class="content-nav">
            <div class="number-nav">
              <p style="font-weight: bold; color: #ff8a00">3</p>
            </div>
            <p style="font-weight: bold; color: #ff8a00; margin-left: 10px">Finish</p>
          </div>
        </div>
      </div>

      <!-- content -->
      <div style="display: flex; justify-content: center">
        <div class="content">
          <div class="row">
            <span style="cursor: pointer; color: #908e9c">
              <i class="fas fa-arrow-left" style="margin-right: 10px"></i>Back to cart
            </span>
          </div>
          <!--  -->
          <div class="row" style="margin-top: 20px">
            <div class="left">
              <h1 style="font-weight: bold; color: #ff8a00">Delivery details</h1>
              <div class="input">
                <input type="email" placeholder="Email" />
              </div>
              <div class="input">
                <input type="number" placeholder="Phone Number" />
              </div>
              <div>
                <input type="text" placeholder="Delivery address" style="height: 150px" />
              </div>
            </div>
            <div class="middle" style="height: 100px; width: 400px; padding: 30px">
              <div>
                <!-- kasih checkbox -->
                <input type="checkbox">
                <p>hehe</p>
              </div>
              <div>
                <input type="text" placeholder="Delivery address" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
  methods: {}
};
</script>
<style scoped>
#home {
  display: flex;
  justify-content: space-around;
  overflow: hidden;
}
</style>