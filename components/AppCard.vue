<template>
  <div
    class="flex flex-col text-center p-10 bg-orange-500 rounded-2xl m-auto w-8/12"
  >
    <section class="gap-1 p-10">
      <h2>{{ props.title }}</h2>
      <slot name="card-des"></slot>

      <AppButton :btn-text="'CLICK ME'"></AppButton>
      <img src="#" alt="Card Image" />

      <slot name="card-tags"></slot>
    </section>
  </div>
</template>

<script setup>
const props = defineProps({
  title: {
    type: String,
    default: "Card Title",
  },
  //   tag1: {
  //     type: String,
  //     default: "Tag Section",
  //   },
  //   tag2: {
  //     type: String,
  //     default: "Tag Section",
  //   },
  //   tag3: {
  //     type: String,
  //     default: "Tag Section",
  //   },
});
</script>
