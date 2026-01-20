<script setup>
  import { defineProps } from 'vue';

  defineProps({
    project: Object
  });
</script>

<template>
  <div class="col-12 col-md-4">
    <div class="card product-card h-100 shadow-sm">
      <div class="product-img-wrapper">
        <img :src="project.image" class="img-fluid" :alt="project.product">
      </div>
      
      <div class="card-body text-center">
        <h4 class="fw-bold text-primary-blue">{{ project.product }}</h4>
        <p class="text-muted small">
          {{ project.description }}
        </p>
        <button class="btn btn-main w-100 mt-auto">Initialize Protocol</button>
      </div>
    </div>
  </div>
</template>