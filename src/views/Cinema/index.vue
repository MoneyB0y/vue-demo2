<template>
  <div id="main">
      <Header title="喵喵影院"/>
      <TabBar />
  </div>
</template>

<script>
  import Header from '@/components/Header';
  import TabBar from '@/components/TabBar';
  export default {
    name: 'Cinema',
    props:[''],
    data () {
      return {

      };
    },

    components: {
      Header,
      TabBar
    },

    computed: {},

    beforeMount() {},

    mounted() {},

    methods: {},

    watch: {}

  }

</script>
<style>

</style>