<template>
  <div id="admin">
    <div class="container">
      <div class="row tex-center">
        <div class="col-md-offset-5 col-md-6">
          <div class="form-login">
            <h4>Welcome back.</h4>
            <input
              type="text"
              id="userName"
              class="form-control input-sm chat-input"
              placeholder="username"
            />

            <input
              type="text"
              id="userPassword"
              class="form-control input-sm chat-input"
              placeholder="password"
            />

            <div class="wrapper">
              <span class="group-btn">
                <a href="#" class="btn btn-primary btn-md">
                  login
                  <i class="fa fa-sign-in"></i>
                </a>
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
body {
  background-color: #fff;
  -webkit-font-smoothing: antialiased;
  font: normal 14px Roboto, arial, sans-serif;
}

.container {
  padding: 25px;
  position: fixed;
}

.form-login {
  background-color: #ededed;
  padding-top: 10px;
  padding-bottom: 20px;
  padding-left: 20px;
  padding-right: 20px;
  border-radius: 15px;
  border-color: #d2d2d2;
  border-width: 5px;
  box-shadow: 0 1px 0 #cfcfcf;
}

h4 {
  border: 0 solid #fff;
  border-bottom-width: 1px;
  padding-bottom: 10px;
  text-align: center;
}

.form-control {
  border-radius: 10px;
}

.wrapper {
  text-align: center;
}
</style>