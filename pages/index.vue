<template>
  <v-container>
    <header>
      <h1>사이트제목</h1>
    </header>
    <v-sheet class="mx-auto">
      <v-form class="d-flex" @submit.prevent>
        <v-autocomplete
          variant="outlined"
          placeholder="검색어"
          :items="[
            'California',
            'Colorado',
            'Florida',
            'Georgia',
            'Texas',
            'Wyoming',
          ]"
        ></v-autocomplete>
        <v-btn type="submit" variant="flat" color="error">검색</v-btn>
      </v-form>
    </v-sheet>
    <v-row>
      <v-list class="d-flex">
        <v-list-item>키워드1</v-list-item>
        <v-list-item>키워드2</v-list-item>
        <v-list-item>키워드3</v-list-item>
      </v-list>
    </v-row>
    <v-row>
      <v-list class="d-flex">
        <v-list-item>
          <NuxtLink to="#"> 분류1 </NuxtLink>
        </v-list-item>
        <v-list-item>
          <NuxtLink to="#"> 분류2 </NuxtLink>
        </v-list-item>
        <v-list-item>
          <NuxtLink to="#"> 분류3 </NuxtLink>
        </v-list-item>
      </v-list>
    </v-row>
  </v-container>
</template>
<script></script>
