<template>
  <div class="m-0 p-0 flex flex-col">
    <TheHeader />
    <main>
      <div class="grid grid-cols-3 py-12">
        <!-- Card 1 -->
        <AppCard :title="'Travel Anywhere, Anytime'">
          <template #card-des>
            <p>The best time to travel is now!</p>
          </template>
          <template #card-image class="py-">
            <img
              src="https://images.pexels.com/photos/11341064/pexels-photo-11341064.jpeg?auto=compress&cs=tinysrgb&dpr=2"
              alt="Image of Plane"
            />
          </template>

          <!-- Tag Section -->
          <template #card-tags class="flex flex-row">
            <div class="flex flex-row justify-evenly py-4">
              <div
                class="bg-gray-500 text-white rounded-lg flex justify-center p-1"
              >
                <p>tag1</p>
              </div>
              <div
                class="bg-gray-500 text-white rounded-lg flex justify-center p-1"
              >
                <p>tag2</p>
              </div>
              <div
                class="bg-gray-500 text-white rounded-lg flex justify-center p-1"
              >
                <p>tag3</p>
              </div>
            </div>
          </template>
        </AppCard>

        <!-- Card 2 -->
        <AppCard :title="'Visit the Mountains'">
          <template #card-des class="h-auto">
            <p>For those with an adventurous spirit</p>
          </template>
          <template #card-image class="py-">
            <img
              src="https://images.pexels.com/photos/3551214/pexels-photo-3551214.jpeg?auto=compress&cs=tinysrgb&dpr=2"
              alt="Image of Mountain"
            />
          </template>

          <!-- Tag Section -->
          <template #card-tags class="flex flex-row m-auto">
            <div class="flex flex-row justify-evenly py-4">
              <div
                class="bg-gray-500 text-white rounded-lg flex justify-center p-1"
              >
                <p>tag1</p>
              </div>
              <div
                class="bg-gray-500 text-white rounded-lg flex justify-center p-1"
              >
                <p>tag2</p>
              </div>
              <div
                class="bg-gray-500 text-white rounded-lg flex justify-center p-1"
              >
                <p>tag3</p>
              </div>
            </div>
          </template>
        </AppCard>

        <!-- Card 3 -->
        <AppCard :title="'Or Relax by the Beach'">
          <template #card-des>
            <p>Tired of that 9-5? Aren't we all</p>
          </template>
          <template #card-image class="py-">
            <img
              src="https://images.pexels.com/photos/11282403/pexels-photo-11282403.jpeg?auto=compress&cs=tinysrgb&dpr=2"
              alt="Image of Plane"
            />
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
