<template>
  <div class="login">

        <!-- Bread Crumb -->
            <section class="breadcrumb">
                <div class="container">
                    <div class="row">
                        <div class="col-12">
                            <nav class="breadcrumb-link">
                                <a href="#"><span>Home</span></a>
                                <a href="#"><span>Pages</span></a>
                                <span>Login & Register</span>
                            </nav>
                        </div>
                    </div>
                </div>
            </section>
            <!-- Bread Crumb -->

            <!-- Page Content -->
            <section class="content-page">
                <div class="container">
                    <div class="row">
                        <div class="col-md-6">
                            <div class="form-border-box">
                                <form>
                                    <h3 class="mb-15">Registered Customers</h3>
                                    <p>Lorem ipsum dolor amet, conse adipiscing, eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                                    <ul>
                                      <li class="text-danger" v-for="error in errors">{{ error }}</li>
                                    </ul>

                                    <div class="form-field-wrapper">
                                        <label>Enter Your Email <span class="required">*</span></label>
                                        <input id="author-email" class="input-lg form-full" name="author" placeholder="Enter Your Email Address" value="" size="30" aria-required="true" required="" type="email" v-model="email">
                                    </div>
                                    <div class="form-field-wrapper">
                                        <label>Enter Your Password <span class="required">*</span></label>
                                        <input id="author-pass" class="input-lg form-full" name="author-pass" placeholder="Enter Your Password" value="" size="30" aria-required="true" required="" type="password">
                                    </div>
                                    <div class="form-field-wrapper">
                                        <input name="submit" id="submit" class="submit btn btn-lg btn-black" value="Sign In" type="submit" v-model="password">
                                    </div>
                                </form>
                            </div>
                        </div>
                        <div class="col-md-6">
                            <div class="form-border-box">
                                <form>
                                    <h3 class="mb-15">New Customers</h3>
                                    <p>Lorem ipsum dolor amet, conse adipiscing, eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                                    <div class="form-field-wrapper">
                                        <input name="submit" id="submit1" class="submit btn btn-lg btn-color" value="Create An Account" type="submit">
                                    </div>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- End Page Content -->
          </div>
  
</template>

<script>
import axios from "axios";

export default {
  template: "#login-page",
  data: function() {
    return {
      email: "",
      password: "",
      errors: []
    };
  },
  methods: {
    submit: function() {
      var params = {
        email: this.email,
        password: this.password
      };
      axios
        .post("http://localhost:3000/api/sessions", params)
        .then(response => {
          axios.defaults.headers.common["Authorization"] =
            "Bearer " + response.data.jwt;
          localStorage.setItem("jwt", response.data.jwt);
          this.$router.push("/");
        })
        .catch(error => {
          this.errors = ["Invalid email or password."];
          this.email = "";
          this.password = "";
        });
    }
  }
};
</script>
