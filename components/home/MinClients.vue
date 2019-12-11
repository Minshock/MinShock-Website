<template>
  <!-- =====================  Client Start  ===================== -->
  <div class="client-container">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <hgroup>
            <h6 class="subtitle">Awesome Client!</h6>
            <h5>We works with some big brands.</h5>
          </hgroup>
          <ul class="client-list">
            <li>
              <div>
                <img src="~assets/images/client-logo.png" alt />
              </div>
            </li>
            <li>
              <div>
                <img src="~assets/images/client-logo2.png" alt />
              </div>
            </li>
            <li>
              <div>
                <img src="~assets/images/client-logo3.png" alt />
              </div>
            </li>
            <li>
              <div>
                <img src="~assets/images/client-logo.png" alt />
              </div>
            </li>
            <li>
              <div>
                <img src="~assets/images/client-logo2.png" alt />
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  <!-- =====================  Client End  ===================== -->
</template>

<style scoped>
.client-container {
  padding: 100px 0;
}

hgroup {
  margin-bottom: 50px;
}

ul.client-list {
  width: 100%;
  float: left;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  text-align: center;
}

ul.client-list > li {
  width: 20%;
  height: auto;
  float: left;
  padding: 40px 15px;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  align-items: center;
}

ul.client-list > li div {
  width: 100%;
}

ul.client-list li img {
  width: 100%;
  max-width: 100px;
}
</style>

<script>
export default {}
</script>
