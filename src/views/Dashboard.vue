<template>
  <div>
    <Header />
    <div>
      <md-card>
        <md-card-header>
          <div class="md-title">Getting Started With Vue</div>
        </md-card-header>

        <md-card-content>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio itaque
          ea, nostrum odio. Dolores, sed accusantium quasi non.
        </md-card-content>

        <md-card-actions>
          <md-button>Action</md-button>
          <md-button>Action</md-button>
        </md-card-actions>
      </md-card>

      <md-card md-with-hover>
        <md-ripple>
          <md-card-header>
            <div class="md-title">Adding Material CSS to Vue</div>
            <div class="md-subhead">By Rajat</div>
          </md-card-header>

          <md-card-content>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio
            itaque ea, nostrum odio. Dolores, sed accusantium quasi non.
          </md-card-content>

          <md-card-actions>
            <md-button>Action</md-button>
            <md-button>Action</md-button>
          </md-card-actions>
        </md-ripple>
      </md-card>
    </div>
  </div>
</template>

<script>
import Header from "../components/Header";
export default {
  name: "Dashboard",
  components: { Header },
};
</script>

<style scoped>
.md-card {
  /* width: 320px; */
  margin-top: 1em;
  /* display: inline-block; */
  vertical-align: top;
}
</style>
