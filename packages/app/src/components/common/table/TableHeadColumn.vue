<template>
  <th scope="col" class="table-head-col">
    <slot></slot>
  </th>
</template>

<script setup lang="ts"></script>

<style>
.table-head-col {
  @apply whitespace-nowrap px-2 py-4 text-left text-xs uppercase tracking-wider bg-primary-800 text-neutral-100 first:pl-6 last:pr-6 font-semibold;
}
</style>
