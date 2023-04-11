<template>
    <!-- props 전달할때 {{ msg }} -->
    <div>{{ msg }}</div>
</template>

<script>
export default {
  name: 'GoHome',
  props: {
    msg: String,
  }
}
</script>

