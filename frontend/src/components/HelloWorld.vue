<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="12">
        <v-img
          :src="require('../assets/logo.svg')"
          class="my-3"
          contain
          height="200"
        />
      </v-col>

      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">这里是标题</h1>

        <v-row justify="center">
          <div class="text-center">
            <v-btn
              class="ma-2"
              :loading="loading"
              :disabled="loading"
              color="secondary"
              @click="loader = 'loading'"
            >
              按钮1
            </v-btn>

            <v-btn
              :loading="loading3"
              :disabled="loading3"
              color="blue-grey"
              class="ma-2 white--text"
              @click="loader = 'loading3'"
            >
              按钮2
            </v-btn>

            <v-btn
              class="ma-2"
              :loading="loading2"
              :disabled="loading2"
              color="success"
              @click="loader = 'loading2'"
            >
              按钮3
            </v-btn>

            <v-btn
              class="ma-2"
              :loading="loading4"
              :disabled="loading4"
              color="info"
              @click="loader = 'loading4'"
            >
              按钮4
            </v-btn>
          </div>
        </v-row>

                <v-row justify="center">
          <div class="text-center">
            <v-btn
              class="ma-2"
              :loading="loading"
              :disabled="loading"
              color="cyan"
              @click="loader = 'loading'"
            >
              按钮5
            </v-btn>

            <v-btn
              :loading="loading3"
              :disabled="loading3"
              color="teal"
              class="ma-2 white--text"
              @click="loader = 'loading3'"
            >
              按钮6
            </v-btn>

            <v-btn
              class="ma-2"
              :loading="loading2"
              :disabled="loading2"
              color="primary"
              @click="loader = 'loading2'"
            >
              按钮7
            </v-btn>



          </div>
        </v-row>
      </v-col>

      <v-col class="mb-5" cols="12">
        <h2 class="headline font-weight-bold mb-3">这里是二级标题</h2>

        <v-row justify="center">
            
            <v-btn depressed color="pink"> Continue </v-btn>
          
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({}),
};
</script>
