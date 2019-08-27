<template>
  <div id="main">
      <Header title="我的喵喵"/>
      <TabBar />
  </div>
</template>

<script>
  import Header from '@/components/Header';
  import TabBar from '@/components/TabBar';
  export default {
    name:'Mine',
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