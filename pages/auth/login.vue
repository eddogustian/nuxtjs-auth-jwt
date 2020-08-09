<template>
  <div class="container">
    <div class="col-md-6 offset-md-3">
      <div class="card mt-4">
        <div class="card-header">
          <p>Login</p>
        </div>
        <div class="card-body">
          <form @submit.prevent="login">
            <div class="form-group">
              <label for="email">Email</label>
              <input type="text" class="form-control" placeholder="Email" />
            </div>
            <div class="form-group">
              <label for="password">Password</label>
              <input type="password" class="form-control" placeholder="Password" />
            </div>
            <div class="form-group">
              <input type="submit" value="login" class="btn btn-primary w-100" />
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>