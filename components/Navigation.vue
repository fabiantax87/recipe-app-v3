<template>
  <nav class="h-screen sticky top-0 left-0 border-r-2">
    <ul class="flex flex-col gap-2 p-4 px-6">
      <NuxtLink to="/">
        <li class="hover:shadow-hover hover:bg-gray-200 rounded-sm px-1">Home</li>
      </NuxtLink>
      <NuxtLink to="/my-meals">
        <li class="hover:shadow-hover hover:bg-gray-200 rounded-sm px-1">My meals</li>
      </NuxtLink>
      <NuxtLink to="/profile">
        <li class="hover:shadow-hover hover:bg-gray-200 rounded-sm px-1">Profile</li>
      </NuxtLink>
    </ul>
  </nav>
</template>