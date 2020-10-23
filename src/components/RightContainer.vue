<template>
  <div class="right">
    <h3 class="title">Member login</h3>
    <br>
    <div class="login-form">
      <font-awesome-icon icon="user-secret"/>
      &nbsp;
      <label for="">Email</label>
      <b-form-input type="email" placeholder="Enter your email"></b-form-input>
      <font-awesome-icon icon="unlock-alt"/>
      &nbsp;
      <label for="">Password</label>
      <b-form-input type="password" placeholder="Enter your password"></b-form-input>
      <br>
      <b-button variant="outline-primary login" href="#">Login</b-button>

      <p class="forgot">Forgot <strong>password/username</strong>?</p>
      <a href="#" class="register">Create your account <font-awesome-icon icon="arrow-right"/></a>
    </div>
  </div>
</template>

<script>
export default {
  name: "RightContainer",
  // data() {
  //   return {
  //     text: ''
  //   }
  // },
  comments: {}
}
</script>

<style scoped>
.right {
  width: 50%;
}

.login-form {
  padding: 10px 15px;
}

.title {
  text-align: center;
}

.login {
  width: 80%;
  margin: auto;
  display: block;
  border-radius: 20px;
}

.forgot {
  font-size: 14px;
  margin: 10px auto;
  display: table;
}

.register {
  display: table;
  margin: auto;
  font-size: 13px;
  color: #2c3e50;

}
</style>