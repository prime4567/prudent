<template>
  <div>
    <Header />
    <div class="container mx-auto px-4">
      <div class="grid grid-cols-1 gap-4 md:grid-cols-2 lg:grid-cols-3 mt-4">
        <div class="card">
          <h1 class="card-header">Total Expense</h1>
          <p class="text-bold text-lg">0.000.000</p>
        </div>
        <div class="card">
          <h1 class="card-header">Top Expenses</h1>
        </div>
        <div class="card">3</div>
        <div class="card">4</div>
        <div class="card">5</div>
        <div class="card">6</div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
