<template>
	<div class="home">
		<img alt="Vue logo" src="../assets/logo.png">
		<HelloWorld msg="Welcome to Your Vue.js App"/>
		<ModernTable id="hello">
			<ModernRow>
				<td>1</td>
				<td>2</td>
				<td>3</td>
			</ModernRow>
		</ModernTable>
	</div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import { ModernTable, ModernRow } from '@/components/multi-component-file.vue';

export default {
	name: 'Home',
	components: {
		HelloWorld,
		ModernTable,
		ModernRow
	}
}
</script>
