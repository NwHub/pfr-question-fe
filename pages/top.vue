<template lang="html">
  <v-container grid-list-md>
    <v-layout>
      <v-flex xs8>
        <v-form>
          <v-card id="personal-info">
            <v-toolbar color="primary">Top</v-toolbar>
            <v-text-field class="mt-4 ml-3" label="Email" prepend-icon="email" value="abc.efg@needswell.com" disabled></v-text-field>
            <v-text-field class="ml-3" label="Point" prepend-icon="place" value="xxxxxxxx" disabled></v-text-field>
          </v-card>
          <v-card id="question-area">
            <v-card-title>Q1</v-card-title>
            <v-radio-group class="ml-4" row>
               <v-radio label="radio1" value="radio1"></v-radio>
               <v-radio label="radio2" value="radio2"></v-radio>
               <v-radio label="radio3" value="radio3"></v-radio>
               <v-radio label="radio4" value="radio4"></v-radio>
            </v-radio-group>
          </v-card>
          <v-card id="question-area">
            <v-card-title>Q2</v-card-title>
            <v-radio-group class="ml-4" row>
               <v-radio label="radio1" value="radio1"></v-radio>
               <v-radio label="radio2" value="radio2"></v-radio>
               <v-radio label="radio3" value="radio3"></v-radio>
               <v-radio label="radio4" value="radio4"></v-radio>
            </v-radio-group>
          </v-card>
          <v-card id="question-area">
            <v-card-title>Q3</v-card-title>
            <v-textarea
              class="ml-4"
              name="q3"
              value="free text area."
            ></v-textarea>
          </v-card>
        </v-form>
      </v-flex>
    </v-layout>
  </v-container>
</template>
