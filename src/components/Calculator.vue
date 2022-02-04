<template>
  <div>
    <input type="number" v-model.number="a" />
    +
    <input type="number" v-model.number="b" />
    <button @click="calculate">Hitung</button>
    <br />
    <p>{{ result }}</p>
  </div>
</template>

<script>
export default {
  name: "Calculator",
  data() {
    return {
      a: 0,
      b: 0,
      result: 0,
    };
  },
  methods: {
    calculate: function () {
      this.result = this.a + this.b;
    },
  },
};
</script>