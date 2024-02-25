<template>
  <div>
    <NuxtLayout>
      <header>
        <ul
          class="flex justify-center gap-2 bg-green-700 text-white text-center"
        >
          <li>
            <NuxtLink to="/">Home</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/events">Events</NuxtLink>
          </li>
        </ul>
      </header>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
