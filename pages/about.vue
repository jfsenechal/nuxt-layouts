<script setup>
definePageMeta({
    layout: false //remove default layout, this is not working when file app/router.options.ts is present
})
</script>
<template>
    <NuxtLayout name="homelayout">
       <h3 class="text-lg">about page (homelayout)</h3>
    </NuxtLayout>
</template>