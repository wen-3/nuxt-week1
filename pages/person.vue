<script setup  >
import Loading from 'vue-loading-overlay';
import 'vue-loading-overlay/dist/css/index.css';

const isLoading = ref(true);
setTimeout(() => {
    isLoading.value = false;
}, 2000);

</script>

<template>
    <div>
        <h2>Person</h2>
        <img src="/image.png" alt="">
        
        <ClientOnly>
            <Loading :active="isLoading"></Loading>
        </ClientOnly>
    </div>
</template>