<template>
  <div class="flex flex-col text-center p-10 bg-orange-500 rounded-2xl m-auto">
    <section class="gap-1 p-10">
      <h2>Title</h2>
      <slot name="card-description"></slot>
      <AppButton :btn-text="'Hi From Parent'"></AppButton>
      <img src="#" alt="Card Image" />
      <div class="flex flex-row p-1 gap-4">
        <AppTag></AppTag>
        <AppTag></AppTag>
        <AppTag></AppTag>
      </div>
    </section>
  </div>
</template>
