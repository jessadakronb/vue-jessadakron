<template>
  <ul
    class="border border-black"
    v-for="manufacture in manufacturer"
    :key="manufacture.id"
  >
    <li>
      <button>
        {{ manufacture.Title }}
      </button>
    </li>
  </ul>
</template>

<script>
export default {
  data: () => ({
    manufacturer: [
      { id: 1, Title: 'Asus' },
      { id: 2, Title: 'Dell' },
    ],
  }),
};
</script>
