<template>
  <div
    class="flex flex-col text-center p-10 bg-orange-500 rounded-2xl m-auto w-8/12"
  >
    <section class="gap-1 p-10">
      <h2 class="text-2xl font-extrabold">{{ props.title }}</h2>
      <slot name="card-des" v-if="!showMore"></slot>
      <slot v-else-if="showMore"></slot>
      <AppButton
        :btn-text="'Show More'"
        v-on:click="showMore = !showMore"
      ></AppButton>
      <slot name="card-image"></slot>

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
  img: {
    type: String,
    default: "Image Url",
  },
  altText: {
    type: String,
    default: "Image altText",
  },
  showMore: false,
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
