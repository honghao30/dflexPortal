<template>
  <div>
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
  </div>
</template>
