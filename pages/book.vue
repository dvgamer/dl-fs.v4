<template>
  <div class="container d-flex align-items-center h-100">
    <coming-soon :develop="2" />
  </div>
</template>

<script>
import comingSoon from '~/components/coming-soon'

export default {
  auth: false,
  components: {
    comingSoon
  }
}
</script>
