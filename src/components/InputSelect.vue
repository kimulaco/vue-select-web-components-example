<script>
export default {
  name: 'InputSelect',
  props: {
    label: {
      type: String,
      required: true
    },
    name: {
      type: String,
      required: true
    },
    id: {
      type: String,
      required: true
    }
  }
}
</script>

<template>
  <div>
    <label :for="id" class="label">{{ label }}</label>
    <div>
      <select :name="name" :id="id">
        <option value="0">0</option>
        <option value="1">1</option>
        <option value="2">2</option>
        <option value="3">3</option>
        <option value="4">4</option>
        <option value="5">5</option>
        <option value="6">6</option>
        <option value="7">7</option>
        <option value="8">8</option>
        <option value="9">9</option>
      </select>
    </div>
  </div>
</template>

<style scoped>
.label {
  font-size: 18px;
}
</style>