<template>
  <button type="button" class="text-white">{{value}}</button>
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
        padding: 0.8rem 2.3rem;
        border-radius: 5px;
        font-size: 0.8rem;
        border: none;
        box-shadow: none;
        font-weight: 500;
        font-family: 'Montserrat', sans-serif;
    }
</style>
