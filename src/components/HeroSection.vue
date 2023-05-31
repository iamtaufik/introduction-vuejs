<script setup>
import Button from './Button.vue';
</script>
<template>
  <div class="container py-5">
    <div class="row flex-lg-row-reverse align-items-center d-flex g-5 justify-content-between py-5">
      <div class="col-10 col-sm-8 col-lg-6">
        <img src="../assets/students.jpg" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy" />
      </div>
      <div class="col-lg-6">
        <h1 class="display-5 fw-bold text-body-emphasis lh-1 mb-3">
          Kuliah disini <br />
          Gak Mahal!
        </h1>
        <p class="lead">
          Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and
          powerful JavaScript plugins.
        </p>
        <div class="d-grid gap-2 d-md-flex justify-content-md-start">
          <Button text="Primary" class="btn-primary btn-lg px-4 me-md-2" />
          <Button text="Default" class="btn-outline-secondary btn-lg px-4" />
        </div>
      </div>
    </div>
  </div>
</template>
