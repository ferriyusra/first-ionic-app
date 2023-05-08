<template>
	<ion-content class="ion-justify-content-center ion-align-items-center">
		<ion-card>
			<ion-card-header>
				<ion-card-title>Tab 1 Page</ion-card-title>
			</ion-card-header>

			<ion-card-content class="text-center">
				Tugas 2 dengan Ionic dan Vue</ion-card-content
			>
		</ion-card>
	</ion-content>
</template>

<script lang="ts">
import {
	IonContent,
	IonCard,
	IonCardHeader,
	IonCardTitle,
	IonCardContent,
} from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
	components: {
		IonContent,
		IonCard,
		IonCardHeader,
		IonCardTitle,
		IonCardContent,
	},
});
</script>
