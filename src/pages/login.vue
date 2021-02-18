<template>
  <div class="flex items-center justify-center">
    <div class="p-3 border rounded-md shadow-md w-2/5">
      <form action="" method="post">
        <div class="m-2">
          <label for="email">Email address</label>
          <input type="email" name="email" id="email" class="border p-2 rounded-md" />
        </div>
        <div class="m-2">
          <label for="passwd">Password</label>
          <input type="password" name="passwd" id="passwd" class="border p-2 rounded-md" />
        </div>
        <div class="flex m-2">
          <div class="">
            <input type="checkbox" name="remember" id="remember" />
            <label for="remember">Remember me</label>
          </div>
          <div class="color-blue">Forgot your password?</div>
        </div>
        <button class="p-2 bg-blue-600 rounded-md" type="submit">Sign in</button>
      </form>
    </div>
  </div>
</template>
