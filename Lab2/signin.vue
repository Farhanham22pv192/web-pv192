<template>
 <form class="form-signin">
 <img class="mb-4" src="=bootstrap-solid.svg" alt="" width="72" height="72">
 <h1 class="h3 mb-3 font-weight-normal">Please sign in</h1>
 <label for="inputEmail" class="sr-only">Email address</label>
 <input type="email" id="inputEmail" class="form-control" placeholder="Email 
address" required autofocus>
 <label for="inputPassword" class="sr-only">Password</label>
 <input type="password" id="inputPassword" class="form-control" 
placeholder="Password" required>
 <div class="checkbox mb-3">
 <label>
 <input type="checkbox" value="remember-me"> Remember me
 </label>
 </div>
 <button class="btn btn-lg btn-primary btn-block " type="submit">Sign in</button>
 <div class="mt-2"><a class="mr-5" href="">Registration</a><a class="ml-5" 
href="">Forget password</a></div>
 <p class="mt-5 mb-3 text-muted">&copy; 2020-2021</p>
 </form>
</template>