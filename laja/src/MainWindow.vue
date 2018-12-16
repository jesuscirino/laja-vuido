<template>
  <Window title="laja" width="400" height="100" margined v-on:close="exit">
    <Box padded>
      <Text>Welcome to your Vuido application!</Text>
      <Box horizontal padded>
        <Button stretchy>OK</Button>
        <Button stretchy>Cancel</Button>
      </Box>
    </Box>
  </Window>
</template>

<script>
export default {
  methods: {
    exit() {
      this.$exit();
    }
  }
}
</script>
