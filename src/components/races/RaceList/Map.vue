<template>
  <div class="col-xs-12 col-sm-12 col-md-3 col-lg-12">
    <div class="panel panel-default">
      <div class="panel-body">
        <img class="img-responsive" v-bind:src="'/uploads/' + image">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Map',
  data() {
    return {
    };
  },
  props: {
    image: {
      type: String,
      required: true,
    },
  },
};
</script>

<style lang="scss" scoped>

</style>
