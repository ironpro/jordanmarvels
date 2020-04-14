<template>
  <div id="top-footer" class="text-left">
    <b-container>
      <b-row>
        <footer-widget>
          <template v-slot:widgettitle>
            Destinations
          </template>
        </footer-widget>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import footerWidget from "./FooterWidget";
export default {
  name: "TopFooter",
  components: {
    "footer-widget": footerWidget
  }
};
</script>

<style lang="scss">
#top-footer {
  background: #4a4642;
  padding: 50px 0;
}
</style>
