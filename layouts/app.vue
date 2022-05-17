<template>
  <div
    class="grid grid-cols-5 gap-6 p-6 bg-indigo-900 min-h-screen overflow-auto max-h-screen"
  >
    <SideBar />
    <div class="col-span-4">
      <slot />
    </div>
  </div>
</template>
