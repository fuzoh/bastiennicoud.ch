<template>
  <div>
    <nav>
      <div class="nav_brand">
        <nuxt-link class="brand" :to="localePath('/')">
          Bastien Nicoud
        </nuxt-link>
      </div>
      <div class="nav_menu">
        <div class="nav_link">
          <nuxt-link :to="localePath('/')">{{ $t('nav.home') }}</nuxt-link>
        </div>
        <div class="nav_link">
          <nuxt-link :to="localePath('/contact')">
            {{ $t('nav.contact') }}
          </nuxt-link>
        </div>
        <div class="nav_link">
          <nuxt-link :to="switchLocalePath('en')">EN</nuxt-link> /
          <nuxt-link :to="switchLocalePath('fr')">FR</nuxt-link>
        </div>
      </div>
    </nav>
    <Nuxt />
  </div>
</template>
