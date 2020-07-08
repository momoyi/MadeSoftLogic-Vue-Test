<template>
  <button type="button" class="">{{value}}</button>
</template>

<script>

export default {
  name: "RoundButton",
  props: {
    value: String
  }
};
</script>

<style scoped>
    button{
        background: #27DEBF!important;
        padding: 0.8rem 2rem;
        border-radius: 1.6rem;
        font-size: 0.8rem;
        border: none;
        box-shadow: none;
        font-weight: 600;
    }
</style>
