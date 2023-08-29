<template>
  <v-select>
    <template #additional-actions="{ search }">
      <button
        type="button"
        :title="`Add ${ search } to favourites`"
        :aria-label="`Add ${ search } to favourites`"
        class="vs__fav"
        style="margin-right:10px;"
      >
        <span>★</span>
      </button>
    </template>
  </v-select>
</template>