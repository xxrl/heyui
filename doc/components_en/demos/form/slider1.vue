<template>
  <div>
    <p>Corresponding value：{{value}}</p>
    <Slider v-model="value"></Slider>
    <p>Corresponding value：{{value2}}</p>
    <Slider v-model="value2" multiple></Slider>
  </div>
</template>
<script>
export default {
  data() {
    return {
      value: 0,
      value2: {
        start: 0,
        end: 20
      }
    };
  }
};
</script>
