<template>
	<view>
		task
		<button @click="addTask">add</button>
	</view>
</template>

<script setup>
	const taskObj = uniCloud.importObject('task')
	
	function addTask() {
		taskObj.addTask(66)
	}
</script>

<style>

</style>
