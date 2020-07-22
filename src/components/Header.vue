<template>
  <div>
    <b-nav>
      <b-nav-item active>Fancy Quiz App</b-nav-item>
      <b-nav-item>Counter {{ score }}/{{ attempts }}</b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  props: ["score", "attempts"],
};
</script>
