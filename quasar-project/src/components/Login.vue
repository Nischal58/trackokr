<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" id="logo-link" href="/">
      <img
        src="../assets/images/mainlayout/okr.png"
        alt="OKRs.app"
        class="header-logo"
    /></a>
    <div class="collapse navbar-collapse">
      <ul class="nav navbar-nav ml-auto">
        <li class="nav-item">
          <router-link class="nav-link" :to="{ name: 'signup' }"
            >Sign up</router-link
          >
        </li>
        <li class="nav-item">
          <router-link class="nav-link" :to="{ name: 'login' }"
            >Login</router-link
          >
        </li>
      </ul>
    </div>
  </nav>
  <div class="container py-5">
    <div class="row">
      <div class="col-md-5 mx-auto">
        <div class="card rounded-0">
          <div class="card-header"><h3 class="mb-0">Login</h3></div>
          <div class="card-body">
            <form>
              <fieldset>
                <div class="form-group">
                  <label for="email">Email</label
                  ><input
                    id="email"
                    placeholder="example@example.com"
                    class="form-control"
                    type="text"
                    value=""
                  />
                </div>
              </fieldset>
              <fieldset>
                <div class="form-group">
                  <label for="password">Password</label
                  ><input
                    id="password"
                    placeholder="Enter password"
                    class="form-control"
                    type="password"
                    value=""
                  />
                </div>
              </fieldset>
              <button type="submit" class="btn btn-primary signup-button">
                Sign In
              </button>
            </form>
          </div>
        </div>
      </div>
    </div>
    <p class="mt-4">
      Don't have an account?&nbsp;<router-link :to="{ name: 'signup' }">signup</router-link>

    </p>
    <p class="mt-4">
      Forgot password?&nbsp;<a href="/forgot-password">Reset</a>
    </p>
  </div>
</template>

<script>
export default {};
</script>

<style>
p{
    text-align: center;
}
</style>