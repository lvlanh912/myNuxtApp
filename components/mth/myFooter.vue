<template>
  <h1>DDaay laf footer</h1>
  {{ props.id }}
</template>

<script setup lang="ts">
interface Props{
    id?:number,
    title?:string
}
const props=defineProps(["id","hello"])
</script>