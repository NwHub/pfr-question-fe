<template>
  <v-container grid-list-md>
    <v-layout>
      <v-flex xs8>
        <v-form>
          <v-card>
            <v-toolbar color="primary">Login</v-toolbar>
            <v-form>
              <v-text-field class="mt-4 ml-3" prepend-icon="mail" name="Username" label="Username"></v-text-field>
              <v-text-field class="ml-3" prepend-icon="lock" name="Password" label="Password" type="password"></v-text-field>
            </v-form>
            <v-card-actions>
              <v-spacer></v-spacer>
              <v-btn>Login</v-btn>
            </v-card-actions>
          </v-card>
        </v-form>
      </v-flex>
    </v-layout>
  </v-container>
</template>
