<script lang="ts" setup></script>

<template>
  <nav text-xl mt-6 inline-flex gap-2>
    <button icon-btn @click="toggleDark()">
      <div dark:i-carbon-moon i-carbon-sun/>
    </button>

    <!--    <a-->
    <!--      icon-btn i-carbon-logo-github-->
    <!--      rel="noreferrer"-->
    <!--      href="https://github.com/lanseria/arco-uno-basic-template"-->
    <!--      target="_blank"-->
    <!--      title="GitHub"-->
    <!--    />-->
  </nav>
</template>
