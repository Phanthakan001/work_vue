<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <div
        class="pa-7 white rounded-circle d-inline-block"
      >
        <v-icon large color="blue">
          mdi-cloud-upload
        </v-icon>
      </div>
    </v-col>
    <div>
      <h1 style="margin-top: 20px">
        KNN BANK
      </h1>
      <h3>MOBILE APP</h3>
      <v-form>
        <v-container>
          <v-row>
            <v-col
              cols="12"
              sm="6"
              md="4"
            >
              <v-menu transition="scroll-y-transition">
                <template #activator="{ on, attrs }">
                  <v-text-field
                    label="Pleate Enter Your Password"
                    placeholder="Password"
                    filled
                    rounded
                    dense
                    v-bind="attrs"
                    v-on="on"
                  />
                </template>
                <div>
                  <div class="box">
                    <v-row>
                      <v-col class="d-flex justify-center ">
                        <v-btn
                          class="mx-2"
                          fab
                          dark
                          color="primary"
                        >
                          1
                        </v-btn>

                        <v-btn
                          class="mx-2"
                          fab
                          dark
                          color="primary"
                        >
                          2
                        </v-btn>

                        <v-btn
                          class="mx-2"
                          fab
                          dark
                          color="primary"
                        >
                          3
                        </v-btn>
                      </v-col>
                    </v-row>

                    <v-row>
                      <v-col class="d-flex justify-center">
                        <v-btn
                          class="mx-2"
                          fab
                          dark
                          color="primary"
                        >
                          4
                        </v-btn>

                        <v-btn
                          class="mx-2"
                          fab
                          dark
                          color="primary"
                        >
                          5
                        </v-btn>

                        <v-btn
                          class="mx-2"
                          fab
                          dark
                          color="primary"
                        >
                          6
                        </v-btn>
                      </v-col>
                    </v-row>

                    <v-row>
                      <v-col class="d-flex justify-center ">
                        <v-btn
                          class="mx-2"
                          fab
                          dark
                          color="primary"
                        >
                          7
                        </v-btn>

                        <v-btn
                          class="mx-2"
                          fab
                          dark
                          color="primary"
                        >
                          8
                        </v-btn>

                        <v-btn
                          class="mx-2"
                          fab
                          dark
                          color="primary"
                        >
                          9
                        </v-btn>
                      </v-col>
                    </v-row>

                    <v-row>
                      <v-col class="d-flex justify-center ">
                        <v-btn
                          class="mx-2"
                          fab
                          dark
                          color="white"
                        >
                          0
                        </v-btn>

                        <v-btn
                          class="mx-2"
                          fab
                          dark
                          color="primary"
                        >
                          0
                        </v-btn>

                        <v-btn
                          class="mx-2"
                          fab
                          dark
                          color="black"
                        >
                          9
                        </v-btn>
                      </v-col>
                    </v-row>
                  </div>
                </div>
              </v-menu>
              <v-btn depressed class="btn1">
                <span class="txt1"><i class="fas fa-sign-in-alt" />  Login</span>
              </v-btn>

              <p>Forgot password?</p>
              <p style="margin-bottom: 100px">
                New to Bank Apps? Sign Up
              </p>
            </v-col>
          </v-row>
        </v-container>
      </v-form>
    </div>
  </v-row>
</template>

<style>
.pa-7{
  margin-top: 100px;
}
h3{
  margin-bottom
  : 100px;
}
.txt1{
  color: rgb(114, 55, 27);
}
.btn1{
  background: linear-gradient(to bottom,#FFD54F,#FF8F00);
  margin-bottom: 98px;
}
.box{
  background-color: #fff;
  padding: 25px;
  border-radius: 20px;
  font-size: 18px;
}
</style>
