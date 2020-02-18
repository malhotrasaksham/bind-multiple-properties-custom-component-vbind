<template>
  <div class="hello">
    <h3>{{salutation}} {{ text }}</h3>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    text: String,
    salutation: String
  }
};
</script>

