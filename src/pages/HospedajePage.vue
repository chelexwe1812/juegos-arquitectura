<template>
    <q-page>
        <div class="bg-indigo-10 q-px-sm">
            <q-btn unelevated class="full-width q-mb-sm" align="left" text-color="black" color="blue-3"
                label="HOTEL" />
            <q-btn unelevated class="full-width q-mb-sm" align="left" text-color="black" color="blue-3"
                label="ALOJAMINETO" />
            <q-btn unelevated class="full-width q-mb-sm" align="left" text-color="black" color="blue-3"
                label="HOSTAL" />
        </div>
        <br />
        <div class="row justify-end q-px-sm">
            <q-btn rounded class="q-pa-md" color="pink-4" icon="arrow_back_ios" @click="$router.go(-1)" />
        </div>
    </q-page>
</template>

<script setup>

defineOptions({
    name: 'FixturePage'
});
</script>