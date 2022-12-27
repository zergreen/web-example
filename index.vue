<template>
  <div>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
    <a
      href="#"
      class="block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow-md hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700"
    >
      <h5
        class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white"
      >
        Noteworthy technology acquisitions 2021
      </h5>
      <p class="font-normal text-gray-700 dark:text-gray-400">
        Here are the biggest enterprise technology acquisitions of 2021 so far,
        in reverse chronological order.
      </p>
    </a>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'Hello World!',
    }
  },
  head() {
    return {
      title: this.title,
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        {
          hid: 'description',
          name: 'description',
          content: 'My custom description',
        },
      ],
      link: [
        {
          rel: 'stylesheet',
          href: 'https://unpkg.com/flowbite@1.5.5/dist/flowbite.min.css',
        },
      ],
      script: [
        {
          src: 'src="https://unpkg.com/flowbite@1.5.5/dist/flowbite.js"',
        },
      ],
    }
  },
}
</script>

<style></style>

