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
              color="info"
              v-on:click="btn1_onclick"
            >
              按钮1
            </v-btn>
            <v-btn
              class="ma-2"
              color="info"
              v-on:click="btn2_onclick"
            >
              按钮2
            </v-btn>
            <v-btn
              class="ma-2"
              color="info"
              v-on:click="btn3_onclick"
            >
              按钮3
            </v-btn>
            <v-btn
              class="ma-2"
              color="info"
              v-on:click="btn4_onclick"
            >
              按钮4
            </v-btn>
            <v-btn
              class="ma-2"
              color="info"
              v-on:click="btn5_onclick"
            >
              按钮5
            </v-btn>
          </div>
        </v-row>

                <v-row justify="center">
          <div class="text-center">
            
               <v-btn
              class="ma-2"
              color="info"
              v-on:click="btn6_onclick"
            >
              按钮6
            </v-btn>
            <v-btn
              class="ma-2"
              color="info"
              v-on:click="btn7_onclick"
            >
              按钮7
            </v-btn>
            <v-btn
              class="ma-2"
              color="info"
              v-on:click="btn8_onclick"
            >
              按钮8
            </v-btn>
            <v-btn
              class="ma-2"
              color="info"
              v-on:click="btn9_onclick"
            >
              按钮9
            </v-btn>


          </div>
        </v-row>
      </v-col>

      <v-col class="mb-5" cols="12">
        <h2 class="headline font-weight-bold mb-3">这里是二级标题</h2>

        <v-row justify="center">
            
            <v-btn depressed color="info" v-on:click="event0"> Continue </v-btn>
          
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({}),
  methods: {
    btn1_onclick(){
      alert("btn1");
    },
    btn2_onclick(){
      alert("btn2");
    },
    btn3_onclick(){
      alert("btn3");
    },
    btn4_onclick(){
      alert("btn4");
    },
    btn5_onclick(){
      alert("btn5");
    },
    btn6_onclick(){
      alert("btn6");
    },
    btn7_onclick(){
      alert("btn7");
    },
    btn8_onclick(){
      alert("btn8");
    },
    btn9_onclick(){
      alert("btn9");
    },
    event0(){
      alert("event0");
    }
  }
};
</script>
