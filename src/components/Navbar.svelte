<div class="navbar bg-neutral text-neutral-content">
  <div class="navbar-start">
    <div class="dropdown">
      <!-- svelte-ignore a11y-label-has-associated-control -->
      <label tabindex="0" class="btn btn-ghost lg:hidden">
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
            d="M4 6h16M4 12h8m-8 6h16"
          /></svg
        >
      </label>
      <ul
        tabindex="0"
        class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52"
      >
        <!-- svelte-ignore a11y-missing-attribute -->
        <li><a>About</a></li>
        <!-- svelte-ignore a11y-missing-attribute -->
        <li><a>Features</a></li>
        <!-- svelte-ignore a11y-missing-attribute -->
        <li><a>Download</a></li>
      </ul>
    </div>
    <!-- svelte-ignore a11y-invalid-attribute -->
    <a href="#" class="btn btn-ghost normal-case text-xl">Woof OS</a>
  </div>
  <div class="navbar-center hidden lg:flex">
    <ul class="menu menu-horizontal p-0">
      <!-- svelte-ignore a11y-missing-attribute -->
      <li><a>About</a></li>
      <!-- svelte-ignore a11y-missing-attribute -->
      <li><a>Features</a></li>
      <!-- svelte-ignore a11y-missing-attribute -->
      <li><a>Download</a></li>
    </ul>
  </div>
  <div class="navbar-end">
    <!-- svelte-ignore a11y-missing-attribute -->
    <a href="https://github.com/woof-os" class="btn btn-active">Github</a>
  </div>
</div>
