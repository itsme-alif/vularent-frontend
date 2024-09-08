<template>
  <div class="vularent__form-group">
    <label :for="id">{{ label }}</label>
    <input :id="id" type="text" v-model="value" :placeholder="placeholder" />
  </div>
</template>
<script setup>
const props = defineProps({
  label: {
    type: String,
    required: false,
  },
  placeholder: {
    type: String,
    required: false,
  },
});
</script>
