<template>
  <UContainer class="my-4">
    <UCard
      class="border border-solid"
      :ui="{
        body: 'flex flex-col items-center justify-center gap-8',
      }"
    >
      <UPageHero
        title="Euro Bill Detection"
        description="Upload an image of a euro banknote to detect its denomination."
        :ui="{ container: 'text-center py-10!' }"
      />

      <UFileUpload
        color="neutral"
        highlight
        label="Drop your image here"
        description="SVG, PNG, JPG or GIF (max. 2MB)"
        class="w-70 sm:w-96 min-h-48"
      />

      <UButton size="xl" color="primary" label="Upload" />
    </UCard>
  </UContainer>
</template>
