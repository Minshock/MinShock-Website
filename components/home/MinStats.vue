<template>
  <!-- =====================  Stats Start  ===================== -->
  <div class="stat-container grey-bg">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <hgroup>
            <h6 class="subtitle">Awesome Stats!</h6>
            <h5>These number inspire us always.</h5>
          </hgroup>
          <ul class="stat-list list-unstyled">
            <li>
              <h3>
                <span class="timer" data-to="859" data-speed="2000"></span>
              </h3>
              <h6>Satisfied Clients</h6>
            </li>
            <li>
              <h3>
                <span class="timer" data-to="3622" data-speed="2000"></span>
              </h3>
              <h6>Completed Projects</h6>
            </li>
            <li>
              <h3>
                <span class="timer" data-to="23" data-speed="2000"></span>
              </h3>
              <h6>Countries Served</h6>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  <!-- =====================  Stats End  ===================== -->
</template>

<style scoped>
.stat-container {
  width: 100%;
  display: inline-block;
  vertical-align: top;
  padding: 100px 0;
  text-align: center;
}

.grey-bg {
  background: #f6f6f6;
}

hgroup {
  margin-bottom: 50px;
}

ul.stat-list {
  width: 100%;
  display: inline-block;
  vertical-align: top;
}

ul.stat-list li {
  width: 33.3%;
  float: left;
}

ul.stat-list li h3 {
  font-size: 72px;
  line-height: 1;
  color: #316bf5;
}

ul.stat-list li h6 {
  font-size: 15px;
  color: #243238;
}
</style>

<script>
export default {}
</script>
