<script lang="ts">
</script>

<div class="navbar ">
	<div class="navbar-start">
		<div class="dropdown">
			<!-- svelte-ignore a11y-label-has-associated-control -->
			<label tabindex="0" class="btn btn-ghost btn-circle">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="h-5 w-5"
					fill="none"
					viewBox="0 0 24 24"
					stroke="currentColor"
					><path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M4 6h16M4 12h16M4 18h7"
					/></svg
				>
			</label>
			<ul
				tabindex="0"
				class="dropdown-content menu rounded-box menu-compact mt-3 w-52 bg-base-100 p-2 font-poppins shadow"
			>
				<li><a href="/">Home</a></li>
				<li><a href="/about">About</a></li>
				<li><a href="/country">Marketplace</a></li>
			</ul>
		</div>
	</div>
	<div class="navbar-center">
		<img src="../src/assets/Logo.png" class="w-36" />
	</div>
	
  <div class="navbar-end">
	<button class="btn btn-outline mr-4 mt-4 px-8">Login</button>
  </div>
</div>
