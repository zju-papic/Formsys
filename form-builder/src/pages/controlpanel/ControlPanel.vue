<template>
  <div>
    <h3>this is panel</h3>
    <button @click='tobuilder'>to builder</button>
    <button @click='todatachecker'>data checker</button>
  </div>
</template>

<script>
export default {
  name: 'ControlPanel',
  methods: {
    tobuilder: function () {
      self.location.href += '/builder'
    },
    todatachecker: function () {
      self.location.href += '/present'
    }
  }
}
</script>
