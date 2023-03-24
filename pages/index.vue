<template>
  <v-container>
    <SearchFm />
    <v-row>
      <v-list class="d-flex">
        <v-list-item>
          <NuxtLink to="BookList"> 분류1 </NuxtLink>
        </v-list-item>
        <v-list-item>
          <NuxtLink to="NoteList"> 분류2 </NuxtLink>
        </v-list-item>
        <v-list-item>
          <NuxtLink to="TapaList"> 분류3 </NuxtLink>
        </v-list-item>
      </v-list>
    </v-row>
  </v-container>
</template>
<script setup>
import SearchFm from '../components/common/SearchFm.vue';
</script>
