<template>
  <div class="m-0 p-0 flex flex-col">
    <TheHeader />
    <main>
      <div class="grid grid-cols-3 items-center fill-inherit">
        <!-- Card 1 -->
        <AppCard :title="'Card 1'">
          <template #card-des>
            <p>What we don't know about the dark web</p>
          </template>
          <template #card-tags class="flex flex-row">
            <div class="flex flex-row justify-evenly">
              <div
                class="bg-gray-500 text-white rounded-lg flex justify-center p-2"
              >
                <p>tag1</p>
              </div>
              <div
                class="bg-gray-500 text-white rounded-lg flex justify-center p-2"
              >
                <p>tag2</p>
              </div>
              <div
                class="bg-gray-500 text-white rounded-lg flex justify-center p-2"
              >
                <p>tag3</p>
              </div>
            </div>
          </template>
        </AppCard>

        <!-- Card 2 -->
        <AppCard :title="'Card 2'">
          <template #card-des class="h-auto">
            <p>Are you voting this year?</p>
          </template>
          <template #card-tags class="flex flex-row m-auto">
            <div class="flex flex-row justify-evenly">
              <div
                class="bg-gray-500 text-white rounded-lg flex justify-center p-2"
              >
                <p>tag1</p>
              </div>
              <div
                class="bg-gray-500 text-white rounded-lg flex justify-center p-2"
              >
                <p>tag2</p>
              </div>
              <div
                class="bg-gray-500 text-white rounded-lg flex justify-center p-2"
              >
                <p>tag3</p>
              </div>
            </div>
          </template>
        </AppCard>

        <!-- Card 3 -->
        <AppCard :title="'Card 3'">
          <template #card-des>
            <p>Hello darkness my old friend</p>
          </template>
        </AppCard>
      </div>
    </main>
  </div>
</template>

<script setup>
const baseTitle = "A New Title";

const tagTitle = "Example Tag";
</script>
