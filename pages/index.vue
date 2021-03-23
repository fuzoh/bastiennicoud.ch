<template>
  <main>
    <div class="main_grid_box main_left">
      <my-abstract></my-abstract>
    </div>
    <nuxt-link class="main_grid_box main_right_up" :to="localePath('/skills')">
      <h1>Skills</h1>
    </nuxt-link>
    <nuxt-link
      class="main_grid_box main_right_middle"
      :to="localePath('/technologies')"
    >
      <h1>Technologies</h1>
    </nuxt-link>
    <nuxt-link
      class="main_grid_box main_right_down"
      :to="localePath('/contact')"
    >
      <h1>Contact</h1>
    </nuxt-link>
  </main>
</template>
