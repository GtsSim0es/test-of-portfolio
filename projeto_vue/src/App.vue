<template>
<div>
  <primeirocomponente />
</div>
</template>

<script>
import primeirocomponente from "./components/primeirocomponente.vue"
import lifeCycle from "./components/lifeCycle.vue"

export default {
   name: "app",
   components: {
      primeirocomponente,
      lifeCycle
   }
}
</script>