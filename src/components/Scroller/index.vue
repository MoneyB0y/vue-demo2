<template>
    <div class="wrapper" ref="wrapper">
       <slot></slot>
    </div>
</template>

<script>
    import BScroll from 'better-scroll';
    export default {
    name:'Scroller',
    props:[''],
    data () {
      return {

      };
    },

    components: {},

    computed: {},

    beforeMount() {},

    mounted() {
        var scroll = new BScroll(this.$refs.wrapper,{ // 第一个参数是最外层dom，第二个参数是配置对象
            tap: true,
            probeType: 1
        });
    },

    methods: {},

    watch: {}

  }

</script>
<style scoped>
    .wrapper{height: 100%;}
</style>