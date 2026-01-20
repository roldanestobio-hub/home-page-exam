
<script setup>
	import ProjectsCard from './ProjectsCard.vue';
    import projects from '../data/projects.json';
    import {computed} from 'vue';

    const chunkSize = 3;

    const chunkedProject = computed(() => {

        const chunks = [];

        for(let i = 0; i < projects.length; i += chunkSize) {

            chunks.push(projects.slice(i, i + chunkSize));
        }

        return chunks;
    })
</script>


<template>
  <div class="container py-5" id="project-card">
    <div class="text-center mb-5">
      <h2 class="hero-title"><span class="text-accent">Featured Arsenal</span></h2>
    </div>

    <div class="row g-4 justify-content-center">
      <ProjectsCard 
        v-for="project in projects" 
        :key="project.id" 
        :project="project" 
      />
    </div>
  </div>
</template>