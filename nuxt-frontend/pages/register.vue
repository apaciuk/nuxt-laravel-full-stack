<template>
<div class="mt-5 mb-5">
    <form class="form-signin">
     <img src="~/assets/bootstrap-solid.svg" width="100px;" />
      <h1 class="h3 mb-3 font-weight-normal">Please sign up</h1>

     <div class="form-group">
      <label for="inputName" class="sr-only">Full Name</label>
      <input type="text" id="inputName" class="form-control" placeholder="Full Name" required autofocus>
        </div>
     <div class="form-group">
      <label for="inputEmail" class="sr-only">Email address</label>
      <input type="email" id="inputEmail" class="form-control" placeholder="Email address" required autofocus>
        </div>
      <div class="form-group">
      <label for="inputPassword" class="sr-only">Password</label>
      <input type="password" id="inputPassword" class="form-control" placeholder="Password" required>
      </div>
      <div class="checkbox mb-3">
        <label>
          <input type="checkbox" value="remember-me"> Remember me
        </label>
      </div>
      <button class="btn btn-lg btn-success btn-block" type="submit">Sign in</button>
       <p class="mt-5 mb-3 text-muted">Already have an account? <nuxt-link to="login">Sign In</nuxt-link></p>
    </form>
    </div>
</template>