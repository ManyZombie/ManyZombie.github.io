<template>
  <v-app>

    <!-- <v-toolbar></v-toolbar> -->
    <v-content>
      <v-container>
        <v-layout>
          <v-flex>
            <v-card>
              <v-layout align-center justify-center>
                <div>
                  <v-img src="./security.svg" width='120px'></v-img>
                </div>
              </v-layout>
              <v-card-text>
                <v-text-field></v-text-field>
                <v-text-field></v-text-field>
              </v-card-text>
            </v-card>
          </v-flex>
        </v-layout>


      </v-container>
    </v-content>

  </v-app>
</template>

<script>
export default {
  data() {
    return {
      test: 'test',
    };
  },
};
</script>
