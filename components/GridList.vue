<template>
<div>
  <v-container grid-list-md text-xs-center>
    <v-layout fill-height="2">
      <v-flex xs12>
        <v-card dark color="primary">
          <v-card-text class="px-0">12</v-card-text>
        </v-card>
      </v-flex>

        <v-flex xs3 v-for="i in 4" :key="`3${i}`">
        <v-card dark color="secondary">
          <v-card-text class="px-0">3</v-card-text>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
  </div>

      </template>