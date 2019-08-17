<template>
  <div class="text-base leading-normal font-sans flex flex-col bg-gray-900">
    <div class="flex flex-grow content-center">
      <slot/>
    </div>
  </div>
</template>

<static-query>
  query {
  metaData {
  siteName
  }
  }
</static-query>
