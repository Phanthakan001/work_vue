<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card light rounded-lg class="caed">
        <div class="box">
          Sign up your bank account
        </div>
        <div class="txt">
          <v-row style="margin-top: 5px;">
            <v-col
              cols="12"
              sm="6"
            >
              <v-text-field
                label="Your Name"
                single-line
                outlined
                color="black"
              />
            </v-col>
          </v-row>

          <v-row style="margin-top:1px;">
            <v-col
              cols="12"
              sm="6"
            >
              <v-text-field
                label="Bank Account"
                single-line
                outlined
                color="black"
              />
            </v-col>
          </v-row>

          <v-row style="margin-top:1px;">
            <v-col
              cols="12"
              sm="6"
            >
              <v-text-field
                label="Mobile phone number"
                single-line
                outlined
                color="black"
              />
            </v-col>
          </v-row>

          <v-row style="margin-top:1px;">
            <v-col
              cols="12"
              sm="6"
            >
              <v-text-field
                label="Email"
                single-line
                outlined
                color="black"
              />
            </v-col>
          </v-row>

          <v-row style="margin-top:1px;">
            <v-col
              cols="12"
              sm="6"
            >
              <v-text-field
                type="password"
                label="Password"
                single-line
                outlined
                color="black"
                append-icon="mdi-eye"
              />
            </v-col>
          </v-row>
        </div>
        <div class="box2">
          Use 6 charaacters with a mix of numbers <br>
          and letters
        </div>
        <v-col cols="10">
          <v-checkbox
            indeterminate
            label="By signing up, you agree to Back's Term of Use & Privacy Policy."
            value
            color="black"
          />
        </v-col>

        <v-col class="d-flex justify-center ">
          <v-btn depressed class="btn1">
            <span class="txt1"><i class="fas fa-sign-in-alt" />  SIGN UP</span>
          </v-btn>
          <p class="p1">
            or
          </p>
          <v-btn
            depressed
            class="btn2"
            outlined
            color="black"
          >
            <span class="txt1">  CANCEL</span>
          </v-btn>
        </v-col>

        <v-col class="d-flex justify-center ">
          <div class="box4">
            Already signed up?
          </div>
          <div class="box3">
            <a href="#" class="bnt">Log in</a>
          </div>
        </v-col>
      </v-card>
    </v-col>
  </v-row>
</template>

<style>
.pa-4{
  margin-top: 25px;
  margin-bottom: 70px;
  margin-left: 15px;
  margin-right: 15px;
}
.box{
  padding-top: 15px;
  margin-top: 30px;
  font-size: 20px;
  color: rgb(12, 16, 211);
}
.box2{
  font-size: 16px;
  color: rgb(12, 16, 211);
}
.box3{
  font-size: 16px;
  color: rgb(12, 16, 211);
  padding-left: 5px;
}
.box4{
  font-size: 16px;
  color: rgb(0, 0, 0);
}
.v-text-field--outlined fieldset{
  color: #29292a !important

}
.v-text-field--outlined label{
  color: #29292a !important
}
.v-checkbox{
  color: #29292a
}
.txt{
  padding-top: 20px;
  padding-left: 20px;
  padding-right: 20px;
}
.v-checkbox{
  color: black !important
}
.btn1{
  background: linear-gradient(to bottom,#FFD54F,#FF8F00);
  margin-bottom: 5px;
}
.p1{
  color: #29292a;
  padding-left: 5px;
  padding-right: 5px;
  padding-top: 5px;
}
.caed{
  padding: 10px;
  margin-top: 30px;
  margin-left: 10px;
  margin-right: 10px;
  margin-bottom: 50px;
}
</style>
