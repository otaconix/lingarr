﻿<template>
    <div
        class="grid grid-flow-row auto-rows-max grid-cols-1 gap-4 p-4 xl:grid-cols-2 2xl:grid-cols-3">
        <SubtitleSettings />
        <ValidationSettings />
    </div>
</template>

<script setup lang="ts">
import SubtitleSettings from '@/components/features/settings/SubtitleSettings.vue'
import ValidationSettings from '@/components/features/settings/ValidationSettings.vue'
</script>
