<template>
  <div>
    A *default* layout
    <ul>
      <li><NuxtLink to="/">Home</NuxtLink></li>
      <li><NuxtLink to="/post1">Post 1</NuxtLink></li>
      <li><NuxtLink to="/project/post2">Post 2</NuxtLink></li>
      <li>About</li>
    </ul>
    <div>---------</div>
    <slot />
  </div>
</template>
