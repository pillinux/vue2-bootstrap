<template>
  <div class="about">
    <form id="form-login" action="/login" method="post" novalidate="novalidate">
	<div class="form-group">
		<label>Email</label><input type="email" name="email" class="form-control" placeholder="Enter email" value="">
	</div>
	<div class="form-group">
		<label>Password</label> <input type="password" name="password" class="form-control" placeholder="Password" value="">
		<div class="my-3 text-right">
			<a href="/password" class="text-muted" data-pjax-state="">Forgot password?</a>
		</div>
	</div>
	<div class="checkbox mb-3">
		<label class="ui-check"><input type="checkbox" name="remember" value="true"><i></i> Remember me</label>
	</div>
	<input type="hidden" name="exec" value="true">
	<button type="submit" class="btn btn-primary btn-block">Sign In</button>
	<div>
		Do not have an account? <a href="/register" class="text-primary">Sign up</a>
	</div>
</form>
  </div>
</template>
