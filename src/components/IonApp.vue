<template>
	<ion-app>
		<TabHeader />
		<TabContent />
		<TabFooter />
	</ion-app>
</template>

<script lang="ts">
import { IonApp } from '@ionic/vue';
import TabHeader from './TabHeader.vue';
import TabContent from './TabContent.vue';
import TabFooter from './TabFooter.vue';

export default {
	components: { IonApp, TabHeader, TabContent, TabFooter },
};
</script>
