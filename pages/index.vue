<template>
  <div>
    <header>
      <h1>사이트제목</h1>
    </header>
    <v-sheet width="300" class="mx-auto">
      <v-form @submit.prevent>
        <v-text-field
          v-model="searchName"
          :rules="rules"
          label="검색어"
        ></v-text-field>
        <v-btn type="submit">검색</v-btn>
      </v-form>
    </v-sheet>
  </div>
</template>
<script></script>
