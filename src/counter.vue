// mon composant
<template>
	<div class="counter">
		 {{count}}
     <div class="counter__bunton" @click="increment">+</div>
	</div>

</template>


<script>
  // import store from './store/notification_store'

	export default {
		data() {
			return {
        count: 0
        // state: store.state
			}
    },

    // computed: {
    //   count: function () {
    //     return this.state.count
    //   }
    // },

		methods: {
			increment () {
        this.count++
        // store.increment
			}
		},
	}
</script>


<style src="./counter.css">

</style>
