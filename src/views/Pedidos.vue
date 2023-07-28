<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
    <div class="main-container">
      <h1>Gerenciar pedidos:</h1>
      <Dashboard />
    </div>
  </div>
</template>

<script>
import Dashboard from '../components/Dashboard'

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Pedidos',
  components: {
    Dashboard
  }
}
</script>
