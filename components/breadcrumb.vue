<template>
  <v-breadcrumbs :items="items" divider='>'>
    <template v-slot:item="{ item }">
      <v-breadcrumbs-item
        :href="item.href"
        :disabled="item.disabled"
      >
        <v-icon>{{ item.text }} </v-icon> 
        <!-- <v-icon>mdi-help</v-icon> -->
      </v-breadcrumbs-item>
    </template>
  </v-breadcrumbs>
</template>

<script>
  export default {
    data: () => ({
      items: [
        {
          text: 'mdi-home',
          disabled: false,
          href: 'breadcrumbs_dashboard',
        },
        
      ],
    }),
  }
</script>