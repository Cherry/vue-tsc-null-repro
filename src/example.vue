<script setup lang="ts">
import inputExample from './another-component.vue';

type Foo = {
	name: string;
}
type Bar = {
	id: string;
	foo: Foo | null;
};

const example: Bar = {
	id: '1',
	foo: null,
};

</script>
<template>
	<div v-if="example.foo" >
		<inputExample v-model="example.foo.name" />
	</div>
</template>
