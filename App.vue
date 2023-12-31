<template>
    <v-md-editor v-model="text" :left-toolbar="toolbar" :disabled-menus="[]" height="500px"/>
</template>

<script setup>
    import { ref } from 'vue'

    const toolbar = 'undo redo clear | h bold italic strikethrough quote | ul ol table hr | link image code | save'
    const content = ref('It was nice to meet you!')
</script>
