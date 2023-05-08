<template>
	<ion-page>
		<tab-1-header />
		<tab-1-content>
			<ion-list>
				<tab-1-item>
					<template #title>
						<h1>Create Idea</h1>
					</template>
					<template #subtitle> Run Idea By Brandy </template>
					<template #badge> 5 Days </template>
				</tab-1-item>
			</ion-list>
		</tab-1-content>
	</ion-page>
</template>

<script setup lang="ts">
import TabHeader from '../components/TabHeader.vue';
import TabContent from '../components/TabContent.vue';
import TabFooter from '../components/TabFooter.vue';
</script>

<script lang="ts">
export default {
	components: {
		TabHeader,
		TabContent,
		TabFooter,
	},
};
</script>
