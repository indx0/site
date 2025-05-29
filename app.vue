<template>
  <div class="bg-zinc-900 flex flex-col items-center justify-start min-h-screen p-7 text-white">

    <div class="flex flex-col items-center justify-center gap-2">
      <img src="/pfp.jpg" height="150" width="150" class="rounded-full" />
      <h2 class="text-2xl font-bold">IndexZero</h2>
      <h4>Java backend developer</h4>
      <div class="flex flex-row text-3xl gap-2">
        <a href="https://github.com/indx0">
          <Icon name="mdi:github" style="color: white" />
        </a>
        <a href="https://t.me/index_zero">
          <Icon name="ic:baseline-telegram" style="color: white" />
        </a>
        <a href="https://vk.com/irindx">
          <Icon name="ri:vk-fill" style="color: white" />
        </a>
      </div>
    </div>
    <div class="flex flex-col items-start justify-center w-[100%] gap-2">
      <h2 class="text-xl font-bold">My Skills</h2>
      <h4 class="text-lg font-bold">Backend:</h4>

      <div class="flex flex-wrap flex-row items-center justify-start gap-2 w-[100%]">
        <div class="flex flex-col items-center justify-start gap-2 border border-zinc-700 p-5 rounded-md flex-grow">
          <Icon name="devicon:java" size="2.5em"/>
          <h4 class="text-lg font-bold">Java</h4>
        </div>

        <div class="flex flex-col items-center justify-start gap-2 border border-zinc-700 p-5 rounded-md flex-grow">
          <Icon name="devicon:spring" size="2.5em"/>
          <h4 class="text-lg font-bold">Spring Boot</h4>
        </div>

        <div class="flex flex-col items-center justify-start gap-2 border border-zinc-700 p-5 rounded-md flex-grow">
          <Icon name="devicon:postgresql" size="2.5em"/>
          <h4 class="text-lg font-bold">PostgreSQL</h4>
        </div>

        <div class="flex flex-col items-center justify-start gap-2 border border-zinc-700 p-5 rounded-md flex-grow">
          <Icon name="devicon:liquibase" size="2.5em"/>
          <h4 class="text-lg font-bold">Liquibase</h4>
        </div>
      </div>

    </div>
  </div>
</template>
<script setup lang="ts">
</script>
