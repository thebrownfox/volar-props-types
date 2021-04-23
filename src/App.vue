<template>
	<img alt="Vue logo" src="./assets/logo.png" />
	<HelloWorldWorks msg="Hello Vue 2 + Vite" />
</template>

<script lang="ts">
import HelloWorldWorks from "./components/HelloWorldWorks.vue";
import HelloWorldNotWorking from "./components/HelloWorldNotWorking.vue";
export default {
	name: "App",
	components: {
		HelloWorldWorks,
		HelloWorldNotWorking,
	},
};
</script>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>
