<template>
  <q-layout>
    <q-page-container class="container_bg window-height">
      <q-page>
        <div style="margin-left:150px;">
          <img
            class="q-mt-xl"
            src="~assets/icon.jpg"
          >
          <div>
            <p class="q-mt-xl text-h2 text-primary text-weight-light">
              Get Started with MedSTAFF
            </p>
            <p class="q-ml-sm text-subtitle1 text-primary text-weight-medium">
              Take Control of your appointments and income, We'll handle the rest
            </p>
          </div>

          <div
            class="q-mt-xl"
            style="max-width:300px;"
          >
            <q-form class="q-gutter-y-sm">
              <q-input
                outlined
                label="Email"
              />

              <q-input
                outlined
                label="Name"
              />

              <q-input
                outlined
                label="Password"
              />

              <q-input
                outlined
                label="Password"
              />

              <q-btn
                class="full-width text-center q-mt-lg"
                color="primary"
                label="Sign Up"
              />
            </q-form>

            <div class="q-mt-lg q-gutter-x-sm">
              <p class="text-weight-medium">Connect Via</p>
              <q-btn color="grey-3">
                <img
                  height="15px"
                  src="~assets/images/linkedin.svg"
                >
              </q-btn>
              <q-btn color="grey-3">
                <img
                  height="15px"
                  src="~assets/images/linkedin.svg"
                >
              </q-btn>
              <q-btn color="grey-3">
                <img
                  height="15px"
                  src="~assets/images/linkedin.svg"
                >
              </q-btn>
            </div>
          </div>

        </div>
      </q-page>

    </q-page-container>
  </q-layout>
</template>

<script>
export default {

};
</script>

<style >
.container_bg {
  background: url("~assets/background.jpg");
  background-size: cover;
}
</style>
