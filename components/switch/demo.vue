<template>
  <div class="mdc-demo mdc-demo--container">
    <div><p><mdc-switch 
      v-model="checked" 
      :label="checked?'switch on':'switch off'"/></p>
      <p><mdc-switch 
        disabled 
        label="Disabled"/></p>
  </div>  </div>
</template>

<script>
export default {
  data() {
    return {
      checked: false
    }
  }
}
</script>
