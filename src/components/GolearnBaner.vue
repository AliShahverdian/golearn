<template>
  <v-row class="linier d-flex justify-space-around align-center py-10 px-4">
    <v-col cols="12" md="5">
      <img src="@/assets/image 23 (2).png" class="girl" />
    </v-col>
    <v-col cols="12" md="5">
      <div class="text-h4 font-weight-bold mb-4">
        Exciting news for all book lovers:
      </div>
      <div class="d-flex align-center">
        <div>
          <img src="@/assets/Rectangle 148.png" />
        </div>
        <div class="font-weight-bold ml-4 introducing">is introducing</div>
      </div>
      <div class="font-weight-bold mb-10 introducing">
        a news for all book lovers!
      </div>
      <div class="text-h6">
        Read over 40 books with amazing stories and life lessons, delve deeper
        into the mysteries of distant lands, meet new characters and follow
        their fascinating lives.
      </div>
      <v-btn color="red" class="mt-10 rounded-pill px-8" @click="showAlert">
        let's go
      </v-btn>
    </v-col>
  </v-row>
  <img src="@/assets/image 4 (2).png" class="absolute" />
</template>
<script>
export default {
  methods: {
    shoeAlert() {
      alert("wellcome");
    },
  },
};
</script>
<style>
.linier {
  background: linear-gradient(90deg, #5674f3 0%, #dc6cf8 100.9%);
  color: white;
}
.girl {
  width: 100%;
}

.introducing {
  font-size: 24px;
}
.absolute {
  position: absolute;
  width: 200px;
  right: 10%;
  bottom: -5%;
}
@media screen and (min-width: 960px) {
  .introducing {
    font-size: 36px;
  }
  .absolute {
    bottom: -10%;
  }
}
</style>
