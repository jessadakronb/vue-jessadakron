<template>
  <ul v-for="device in devices" :key="device.id">
    <li>
      {{ device.DeviceName }}
    </li>
  </ul>
</template>

<script>
export default {
  data: () => ({
    devices: [
      { id: 1, DeviceName: 'Asus ROG' },
      { id: 2, DeviceName: 'Dell XP13' },
    ],
  }),
};
</script>
