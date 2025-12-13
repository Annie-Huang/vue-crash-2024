<script setup>
import jobData from '@/jobs.json';
import { ref } from 'vue';

// Similar to make this useState in react
const jobs = ref(jobData);
console.log(jobs.value);
</script>

<template>Job Listings</template>
